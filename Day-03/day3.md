# Day 3 — Role-Based Prompting

## 🎯 Objective

The goal of Day 3 was to understand how assigning different roles to an AI can change the way it approaches the same problem.

I asked Claude the same question three times:

> How can I build a successful AI-powered product as a computer science student?

The only major change was the role given to Claude:

1. No specific role
2. Startup Founder
3. Senior Software Developer

---

## 1. No Role

### Prompt

> How can I build a successful AI-powered product as a computer science student?

### Approach

Claude provided a balanced and practical roadmap covering:

- Finding a real problem
- Building a small MVP
- Keeping AI as a thin layer initially
- Getting real users
- Treating AI products as systems
- Using student status as an advantage
- Tracking meaningful metrics

### Key Observation

The response was broad and balanced. It covered both product development and technical considerations without strongly favoring one perspective.

---

## 2. Founder Role

### Prompt

> Act as a startup founder and mentor with experience building AI-powered products.
>
> How can I build a successful AI-powered product as a computer science student?

### Approach

The response shifted strongly toward a business and product perspective.

It focused on:

- Problem validation
- Finding a specific niche
- Product-market fit
- Distribution
- UX and trust
- Defensibility
- User feedback
- Fast experimentation
- Building a moat
- Evaluating AI systems

One statement that stood out was:

> "AI is a feature, not a business."

### Key Observation

Giving Claude a founder role made the response more strategic and business-oriented. Instead of focusing mainly on how to build the product, it emphasized **why people would use it, how to validate it, and what could make the product defensible.**

---

## 3. Developer Role

### Prompt

> Act as a senior software developer who specializes in building AI-powered applications.
>
> How can I build a successful AI-powered product as a computer science student?

### Approach

The response became significantly more technical.

It focused on:

- Data pipelines
- RAG and embeddings
- Evaluation systems
- Failure handling
- Hallucinations
- Retries and fallbacks
- Cost and latency
- Logging and instrumentation
- Understanding AI fundamentals
- End-to-end engineering

### Key Observation

The developer role shifted the response toward **technical architecture, reliability, debugging, and engineering fundamentals**.

---

## 🔍 Comparison

| Aspect | No Role | Founder | Developer |
|---|---|---|---|
| Main Focus | Balanced roadmap | Business & product strategy | Technical engineering |
| Problem Validation | High | Very High | High |
| Business Strategy | Moderate | Very High | Moderate |
| Distribution | Moderate | Strong | Low |
| UX & Trust | Moderate | Strong | Moderate |
| Technical Depth | Moderate | Moderate | Very High |
| AI Architecture | Moderate | Moderate | Very High |
| Evaluation | Mentioned | Important | Detailed |
| Cost & Latency | Mentioned | Less emphasis | Strong emphasis |
| User Feedback | Important | Very Important | Important |

---

## 🧠 What I Learned

The biggest takeaway from this experiment was:

> **Changing the role doesn't change the question — it changes the lens through which the AI approaches the question.**

The No-Role response gave me a balanced perspective.

The Founder role made Claude think more like a product strategist, focusing on users, distribution, business value, and differentiation.

The Developer role made Claude think more like an engineer, focusing on architecture, reliability, evaluation, cost, latency, and implementation details.

---

## 💡 Key Takeaways

### 1. Role provides context

A role tells the AI what perspective it should prioritize when generating an answer.

### 2. Same question can produce different useful answers

The question remained almost identical, but the priorities changed significantly based on the assigned role.

### 3. Role-based prompting is useful for decision-making

For a product decision, I could ask Claude to respond as:

- A founder
- A developer
- A researcher
- A recruiter
- A product manager
- A user

Each perspective could reveal different aspects of the same problem.

### 4. The best answer may require multiple perspectives

Instead of relying on a single AI response, combining different roles can provide a more complete view of a problem.

---

## 🚀 Personal Learning

As a Computer Science student, I found the Developer perspective especially useful because it highlighted areas beyond simply connecting an AI API — such as evaluation, failure handling, latency, cost, logging, and understanding the underlying technology.

At the same time, the Founder perspective reminded me that building a technically impressive product is not enough. The product needs to solve a real problem and provide value to actual users.

---

## 📌 Conclusion

Day 3 showed me that **prompt engineering is also about perspective engineering**.

By assigning the right role to Claude, I can make the same AI tool approach a problem from completely different angles.

**Day 3/60 — Learning to change the lens, not just the question.**
