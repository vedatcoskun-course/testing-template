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

This is your individual term project repository. You will use it to:

1. Submit your project proposal (Week 6)
2. Submit your checkpoint deliverable (Week 8 — 15 November)
3. Submit your final tool + report (Week 14 — 22 December)

The project is **individual** and counts for **60% of your final grade**.

---

## Repository structure (keep it exactly like this)

```
student.json                     ← Your student number and GitHub username (fill in first)
proposal/
    Project_Proposal_Form.docx   ← Your proposal (Week 6)
src/                             ← Your tool's source code (any language)
tests/                           ← Your tool's own tests
report/                          ← Checkpoint note (Week 8) and final report (Week 14)
README.md                        ← This file: fill in the "Your project" section below as you build
```

Do not rename or move these folders. The instructor's tools read every repository with this layout.

---

## Deadlines

| Milestone | Date | What to commit |
|-----------|------|----------------|
| Proposal  | 29 Oct 2026 (Wk 6)  | Completed `proposal/Project_Proposal_Form.docx` |
| Checkpoint | 15 Nov 2026 (Wk 8) | Working prototype in `src/`, at least one test in `tests/`, a one-page `report/checkpoint.md` |
| Final | 22 Dec 2026 (Wk 14) | Complete tool, test results, `report/final_report.pdf`, this README filled in |

---

## How to submit

1. Commit your work regularly — **commit history is checked**.
2. Make sure your final submission is on the `main` branch before the deadline.
3. The instructor will clone your repo on the deadline date.

---

## Commit often

A project with only one or two commits looks suspicious. Commit every time you make meaningful progress:

```bash
git add .
git commit -m "Add boundary value test cases for login endpoint"
git push
```

---

## Questions?

Open a GitHub Issue in this repository. The instructor monitors all repositories and answers there.

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

_Which AI tools you used, for what, and how you verified their output._
