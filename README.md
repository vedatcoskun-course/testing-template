# Testing & Quality Assurance — Term Project

**Course:** 1413002043 Software Testing and Quality Assurance  
**Semester:** 2026–2027 Fall  
**Instructor:** Prof. Dr. Vedat Coşkun  
**Institution:** Atlas University

---

## How to create your repository (do this once)

1. On this page click **Use this template → Create a new repository**.
2. Owner: your own account (not the organization).
3. Repository name: **`testing-qa-<yourname>`**, lower case, no spaces — for example `testing-qa-ahmedhagy`.
4. Visibility: **Private** — the repository carries your student number and name.
5. Go to **Settings → Collaborators → Add people** and add **`VedatCOSKUN`**.
6. First commit: fill in `student.json` with your student number and your GitHub username.
7. Fill in `proposal/Project_Proposal_Form.docx` and commit it. **The form in this repository is your submission**, not the one on Moodle.

---

## What this repository is for

This is your individual term project repository. You will use it to submit your proposal, your checkpoint and your final tool + report. The project is **individual** and counts for **60% of your final grade**.

---

## Repository structure (keep it exactly like this)

```
student.json                     ← Your student number and GitHub username (fill in first)
proposal/
    Project_Proposal_Form.docx   ← Your proposal
src/                             ← Your tool's source code (any language)
tests/                           ← Your tool's own tests
report/
    ai_log.md                    ← Your AI log (see "How your project is graded")
    checkpoint.md                ← Checkpoint note
    final_report.pdf             ← Final report
README.md                        ← This file: fill in the "Your project" section below as you build
```

Do not rename or move these folders. The instructor's tools read every repository with this layout.

---

## Deadlines

This table is the only place where dates are kept. Issues refer to it; if a date changes, it changes here.

| Milestone | Date | What to commit |
|-----------|------|----------------|
| Proposal | Thu 29 Oct 2026 (Wk 6) | Completed `proposal/Project_Proposal_Form.docx` |
| Proposal revisions | before the next class after your evaluation issue | The changes listed in your evaluation issue |
| Checkpoint | commit by **Sun 22 Nov 2026**, live demo in class **Tue 24 Nov 2026** | Working prototype in `src/`, at least one test in `tests/`, `report/checkpoint.md`, `report/ai_log.md` up to date |
| Final | **Tue 22 Dec 2026** (Wk 14) | Complete tool, test results, `report/final_report.pdf`, this README filled in; hidden-target run and 5-minute defence in class |

9–13 November is midterm week: no class and no project work is expected.

---

## How your project is graded

Use AI assistants as much as you like, but use them in small steps, not one prompt → one finished tool. Your grade is for the work you add on top: the tests, fixes, design decisions, edge cases and debugging that are yours. Three things make that visible, so keep them:

1. `report/ai_log.md` — for each step, what you asked, what you got, what you changed and why.
2. A commit history that shows your work growing over the weeks, not one large dump. Commit every time you make meaningful progress.
3. Being able to explain and modify any part of your code when asked — at the checkpoint, at the hidden-target run (done live in class) and at the final defence.

A large AI-generated tool with little of your own work scores low; a modest tool with a lot of your own work scores high.

---

## How to submit

1. Make sure your work is on the `main` branch before each deadline.
2. The instructor clones your repository on the deadline date.
3. Questions: open a GitHub Issue in this repository. The instructor monitors all repositories and answers there.

---

# Your project (fill in as you build)

## What the tool does

_Two or three sentences: the testing problem, what the tool produces._

## How to run it (one command)

```bash
# e.g.  python src/main.py --config examples/demo.json --out reports/
```

_Prerequisites: language version, how to install dependencies._

## How to run the tests

```bash
# e.g.  pytest tests/
```

## Hidden-target run: what you need from the instructor

_Exactly what input your tool needs for a target it has never seen (a config file? a URL? a schema? a Python file?) and in what format._

## AI assistance

_Which AI tools you used, for what, and how you verified their output. The step-by-step record is in `report/ai_log.md`._
