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

This is your individual term project repository. You will use it to submit your proposal, a checkpoint every week and your final tool + report (dates: see Deadlines). The project is **individual** and counts for **60% of your final grade**.

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
    plan.md                      ← Your weekly plan: one row per checkpoint (CP1–CP5)
    checkpoints/cp1.md … cp5.md  ← One note per checkpoint
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
| Weekly plan and README v2 | **Mon 16 Nov 2026, 18:00** | `report/plan.md` (your rows for CP1–CP5) and the updated "What the tool does" section of this README |
| Checkpoint 1 | **Sat 21 Nov 2026** (Wk 9), live demo in class **Tue 24 Nov 2026** | Your CP1 row in `report/plan.md`: a working prototype in `src/`, at least one test in `tests/`, `report/checkpoints/cp1.md` |
| Checkpoint 2 | **Sat 28 Nov 2026** (Wk 10) | Your CP2 row in `report/plan.md` |
| Checkpoint 3 | **Sat 5 Dec 2026** (Wk 11) | Your CP3 row in `report/plan.md` |
| Checkpoint 4 | **Sat 12 Dec 2026** (Wk 12) | Your CP4 row in `report/plan.md`; the "Hidden-target run" section of this README states exactly what your tool needs |
| Checkpoint 5 | **Sat 19 Dec 2026** (Wk 13) | Your CP5 row in `report/plan.md`; a first version of `report/final_report.pdf` |
| Final | **Tue 22 Dec 2026** (Wk 14) | Complete tool, test results, `report/final_report.pdf`, this README filled in; hidden-target run and 5-minute defence in class |

Every checkpoint closes on **Saturday at 23:59**. For each one, write `report/checkpoints/cpN.md` (N = 1…5) with the headings **Done · Evidence · Time spent · Next · AI use**, and keep `report/ai_log.md` up to date. Each checkpoint is sized for 6–8 hours of work per week, AI assistance included. Commits after a deadline count for the next checkpoint.

9–13 November is midterm week: no class and no project work is expected.

---

## How your project is graded

Use AI assistants as much as you like, but use them in small steps, not one prompt → one finished tool. Your grade is for the work you add on top: the tests, fixes, design decisions, edge cases and debugging that are yours. Three things make that visible, so keep them:

1. `report/ai_log.md` — for each step, what you asked, what you got, what you changed and why.
2. A commit history that shows your work growing over the weeks, not one large dump. Commit every time you make meaningful progress.
3. Being able to explain and modify any part of your code when asked — at the checkpoints, at the hidden-target run (done live in class) and at the final defence.

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
