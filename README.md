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

## Repository structure

```
student.json                     ← Your student number and GitHub username (fill in first)
proposal/
    Project_Proposal_Form.docx   ← Fill this and commit it
src/
    (your tool's source code goes here)
tests/
    (your test files go here)
README.md                        ← Update this as you build
```

---

## Deadlines

| Milestone | Date | What to commit |
|-----------|------|----------------|
| Proposal  | 29 Oct 2026 (Wk 6)  | Completed `proposal/Project_Proposal_Form.docx` |
| Checkpoint | 15 Nov 2026 (Wk 8) | Working prototype in `src/`, at least one test in `tests/` |
| Final | 22 Dec 2026 (Wk 14) | Complete tool, test results, final report |

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
