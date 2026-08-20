# 30-Day Python Learning Roadmap (Beginner-Friendly)

**Goal:** Go from zero Python knowledge to being able to build small, real programs — scripts, simple automations, and a couple of portfolio-worthy projects.

**Time commitment:** ~1–2 hours/day. Consistency beats intensity — a short daily session beats one long weekend cram.

**Final Outcome:** By Day 30, you will have built and understand:
- Core Python syntax, data structures, functions, and OOP basics
- File handling and error handling
- Working with external libraries and APIs
- 3 complete projects for your portfolio (a CLI app, a data-driven script, and a small web-connected tool)

---

## How This Roadmap Is Structured
Each week has a **milestone** (what you should be able to do by week's end), daily tasks (30–90 min of learning + practice), and suggested resources. Projects are built progressively so you're always applying what you just learned.

---

## Week 1: Python Fundamentals
**Milestone:** Understand core syntax — variables, data types, control flow, and basic input/output. Be able to write short scripts confidently.

| Day | Topic | Task |
|---|---|---|
| 1 | Setup + Basics | Install Python & VS Code. Learn `print()`, variables, data types (int, float, str, bool). Write 3 tiny scripts (e.g., temperature converter). |
| 2 | Operators & Input | Arithmetic/comparison/logical operators, `input()`. Build a simple calculator. |
| 3 | Strings | String methods, slicing, f-strings. Build a text formatter (e.g., name capitalizer, palindrome checker). |
| 4 | Conditionals | `if/elif/else`. Build a grade calculator or simple decision-based script (e.g., BMI checker). |
| 5 | Loops | `for`, `while`, `break`, `continue`. Build a number guessing game. |
| 6 | Lists & Tuples | Creating, indexing, slicing, common methods. Build a to-do list manager (in-memory). |
| 7 | **Review + Mini Project** | Combine everything: build a **"Simple Quiz Game"** using loops, conditionals, and lists of questions. |

**Resources:**
- [Python.org official tutorial](https://docs.python.org/3/tutorial/)
- freeCodeCamp "Python for Beginners" (YouTube)
- [W3Schools Python](https://www.w3schools.com/python/)
- Practice: [Exercism Python Track](https://exercism.org/tracks/python), [HackerRank Python domain]

---

## Week 2: Data Structures & Functions
**Milestone:** Write reusable, organized code using functions and Python's core data structures (dicts, sets). Understand scope and basic debugging.

| Day | Topic | Task |
|---|---|---|
| 8 | Dictionaries | Key-value pairs, methods, nested dicts. Build a contact book (dict-based). |
| 9 | Sets & Data Structure Recap | When to use list vs. dict vs. set vs. tuple. Practice problems combining structures. |
| 10 | Functions | `def`, parameters, return values, default args. Refactor earlier scripts into functions. |
| 11 | Functions (Advanced) | `*args`, `**kwargs`, scope (local/global), lambda functions. |
| 12 | Modules & Packages | `import`, using `random`, `math`, `datetime`. Build a random password generator. |
| 13 | Error Handling | `try/except/finally`, custom exceptions. Add error handling to earlier projects. |
| 14 | **Project: CLI To-Do App** | Build a command-line to-do list app with add/remove/mark-complete, using functions + dicts/lists. |

**Resources:**
- Corey Schafer's Python YouTube series (functions, error handling episodes)
- [Real Python](https://realpython.com/) articles on functions & exceptions
- Practice: LeetCode "Easy" problems (arrays/strings/dicts)

---

## Week 3: Files, OOP & Intermediate Concepts
**Milestone:** Understand object-oriented programming basics and file I/O. Be able to structure a small multi-file program.

| Day | Topic | Task |
|---|---|---|
| 15 | File Handling | Reading/writing `.txt` and `.csv` files. Save your to-do app data to a file. |
| 16 | JSON | `json` module — read/write JSON. Convert to-do app storage to JSON. |
| 17 | OOP Basics | Classes, objects, `__init__`, attributes/methods. Model a real-world object (e.g., `Book`, `Car`). |
| 18 | OOP Continued | Inheritance, class vs instance variables. Build a small class hierarchy (e.g., `Animal` → `Dog`, `Cat`). |
| 19 | List/Dict Comprehensions | Write cleaner, Pythonic code. Refactor old scripts using comprehensions. |
| 20 | Virtual Environments & pip | Learn `venv`, installing packages with `pip`. Install and try one new library (e.g., `requests`). |
| 21 | **Project: Expense Tracker** | Build an OOP-based expense tracker that reads/writes to a JSON file (classes for `Expense`, `Tracker`). |

**Resources:**
- Corey Schafer's OOP series (YouTube) — widely considered the best free OOP explainer
- [Real Python: OOP in Python 3](https://realpython.com/python3-object-oriented-programming/)
- Practice: rebuild Week 1–2 mini-projects using classes

---

## Week 4: Libraries, APIs & Final Projects
**Milestone:** Use external libraries and APIs to build something connected to real-world data. Finish with a polished portfolio piece.

| Day | Topic | Task |
|---|---|---|
| 22 | Working with APIs | `requests` library, GET requests, parsing JSON responses. Pull data from a free public API (e.g., weather, jokes). |
| 23 | Intro to Data Handling | Basics of `pandas` (optional but valuable) — reading CSVs, simple analysis. |
| 24 | Web Scraping (Intro) | Basics of `BeautifulSoup` for scraping a simple static page (respect robots.txt / ToS). |
| 25 | Testing & Debugging | Intro to `assert`, basic unit testing with `unittest` or `pytest`. Add tests to one earlier project. |
| 26 | Project Planning | Choose your capstone project (see ideas below) and plan its structure/features. |
| 27 | Capstone — Build Day 1 | Start building the capstone project. |
| 28 | Capstone — Build Day 2 | Continue building; add error handling, file/API integration. |
| 29 | Capstone — Polish | Clean up code, add comments/README, test edge cases. |
| 30 | **Wrap-up & Showcase** | Finalize capstone, push all projects to GitHub, write a short README for each. Reflect on what you learned and pick your next learning direction (web dev, data science, automation, etc.). |

**Capstone project ideas (pick one):**
- **Weather CLI app** — fetches live weather via API, saves search history to a file
- **Personal finance dashboard** — combines your expense tracker with simple charts (using `matplotlib`)
- **Quiz/trivia app with API data** — pulls questions from a trivia API, tracks scores in JSON

**Resources:**
- [Real Python: API integration guide](https://realpython.com/api-integration-in-python/)
- [Public APIs list (free, no auth needed)](https://github.com/public-apis/public-apis)
- `pytest` official docs (quick start section)

---

## Tips for Success
- **Code every day**, even if just 20 minutes — momentum matters more than duration.
- **Type code yourself** rather than copy-pasting; mistakes are where learning happens.
- **Build before you feel ready.** You'll learn more from a messy working project than a perfect tutorial.
- **Use GitHub from Day 1** — commit your daily/weekly work, even small scripts. It becomes your portfolio.
- **When stuck:** read the error message fully, Google it, check Stack Overflow — this is normal, professional developers do this constantly.

## By Day 30, You Should Have
- 3 GitHub repos: CLI To-Do App, Expense Tracker, and your Capstone project
- Working knowledge of Python syntax, functions, OOP, file/JSON handling, and API usage
- Comfort reading documentation and debugging independently
- A clear next step (e.g., Flask/Django for web, pandas/numpy for data, or automation scripting)
