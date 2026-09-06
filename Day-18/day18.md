# Day 18 — Custom Skill: Brain Dump Action Planner

## Objective

Today's task was to create and test a custom Claude Skill called `brain-dump-action-planner`.

The purpose of the skill is to transform messy notes, meeting transcripts, voice memos, brainstorming sessions, and stream-of-consciousness thoughts into structured and actionable information.

The skill was designed to organize information without inventing, assuming, or filling missing details.

## Skill Created

**Skill Name:** `brain-dump-action-planner`

### Core Function

The skill converts unstructured notes into a structured interactive HTML dashboard containing:

- Summary
- Key Takeaways
- Action Items
- Open Questions
- Risks / Blockers
- Conflicts
- Additional Notes

It also uses status badges such as:

- 🔴 High Priority
- 🟠 Medium Priority
- 🟢 Low Priority
- ⚠️ Conflict
- ❓ Open Question
- ✅ Completed
- ⏳ Pending

A key instruction was to display **"Not specified"** whenever information such as an owner, deadline, status, or other required detail is missing rather than inventing a value.

## Test 1 — Meeting Notes

The skill was first tested using a team meeting note covering portfolio development and upcoming hackathon work.

The generated dashboard correctly identified:

- Portfolio deployment as an action item
- GitHub README review as an action item
- Owners and deadlines where they were provided
- The unresolved choice between Vercel and Netlify as an open question
- Missing API credentials as a blocker
- The next meeting date as additional information
- No conflicts where none were specified

The output was generated as a complete interactive HTML dashboard.

## Test 2 — Brainstorming Notes

The skill was then tested with a brainstorming session about portfolio improvements.

The notes contained ideas such as:

- Adding a project showcase
- Adding GitHub links
- Adding a contact form
- Improving mobile responsiveness
- Adding dark mode

The generated dashboard correctly organized these ideas as key takeaways.

It also identified:

- The single-page vs. multiple-page decision as an open question
- Project prioritization as another open question
- Backend integration for the contact form as a potential blocker
- Missing owners, deadlines, and statuses as **"Not specified"**
- The fact that no final decisions had been made

## Key Learnings

### 1. Custom Skills reduce repeated prompting

Once the skill was created, its detailed instructions did not need to be entered again for every test.

### 2. Structured output makes messy information easier to use

The dashboard transformed unstructured notes into clearly separated summaries, tasks, questions, and blockers.

### 3. Missing information should not be invented

The skill correctly used **"Not specified"** when owners, deadlines, or statuses were not present in the source notes.

### 4. The same skill can handle different note formats

The skill successfully processed both meeting notes and brainstorming notes without changing its core instructions.

### 5. Prompt instructions can control both content and presentation

The skill instructions specified not only what information to extract but also how the final output should be presented as an interactive HTML dashboard.

## Overall Result

The `brain-dump-action-planner` custom skill was successfully created and tested with multiple note formats.

The tests demonstrated how a reusable Claude Skill can turn unstructured information into a consistent, actionable, and visually organized dashboard while preserving the information actually provided in the source notes.

### Day 18 Status: Completed ✅
