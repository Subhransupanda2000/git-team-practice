🚀 How This Will Work

You = Dev A (Account 1)

You = Dev B (Account 2)

Same repo → simulate real team

We’ll do 50 scenarios in levels
👉 Start with Level 1 (today)
👉 Don’t jump ahead

🧱 LEVEL 1 — BASIC REAL WORKFLOW (10 Tasks)

👉 Goal: Understand push, pull, branch, conflict

✅ Task 1 — Create Repo (Dev A)

Create repo: git-practice

Clone in IntelliJ

Create file:

app.txt

Add:

Hello World

Commit + push

✅ Task 2 — Dev B Clone

Using second account:

Clone same repo

Check file exists

✅ Task 3 — Dev A Update Code

Dev A:

Hello World
Login Feature

Commit + push

✅ Task 4 — Dev B Pull Latest

Dev B:

git pull

👉 Understand: code sync

✅ Task 5 — Dev B Make Change

Dev B edits:

Hello World
Payment Feature

Commit + push

💥 Task 6 — Dev A Conflict (IMPORTANT)

Dev A (without pulling):

Edit same file:

Hello World
Search Feature

Now push → ❌ FAIL

✅ Task 7 — Resolve Conflict

Dev A:

git pull

👉 Conflict happens

Manually fix:

Hello World
Search Feature
Payment Feature

Commit

✅ Task 8 — Create Branch (Dev A)
git checkout -b develop
git push -u origin develop
✅ Task 9 — Feature Branch
git checkout -b feature/login

Add:

Login Page Added

Push

✅ Task 10 — Merge Feature

Merge:

feature/login → develop
🧱 LEVEL 2 — TEAM WORKFLOW (10 Tasks)

👉 Goal: Work like real company

Task 11 — Dev B create feature/payment
Task 12 — Dev A create feature/search
Task 13 — Both modify same file
Task 14 — Merge first branch
Task 15 — Merge second → conflict
Task 16 — Resolve manually
Task 17 — Delete feature branch
Task 18 — Pull latest develop
Task 19 — Push clean code
Task 20 — Create Pull Request (GitHub UI)
🧱 LEVEL 3 — REAL PROBLEMS (10 Tasks)

👉 Goal: Handle mistakes

Task 21 — Wrong commit → fix using revert
Task 22 — Wrong commit → fix using reset
Task 23 — Forgot file → amend commit
Task 24 — Push wrong code → revert
Task 25 — Work not complete → stash
Task 26 — Apply stash
Task 27 — Delete branch
Task 28 — Recover deleted branch
Task 29 — Check commit history
Task 30 — Compare branches
🧱 LEVEL 4 — ADVANCED TEAM FLOW (10 Tasks)

👉 Goal: Think like senior dev

Task 31 — Rebase feature branch
Task 32 — Rebase conflict resolve
Task 33 — Squash commits
Task 34 — Clean commit history
Task 35 — Avoid unnecessary commits
Task 36 — Sync fork (simulate)
Task 37 — Work on multiple branches
Task 38 — Switch branches safely
Task 39 — Resolve multi-file conflict
Task 40 — Release flow (develop → main)
🧱 LEVEL 5 — PRODUCTION LEVEL (10 Tasks)

👉 Goal: Company-level mastery

Task 41 — Hotfix branch from main
Task 42 — Fix production bug
Task 43 — Merge hotfix → main + develop
Task 44 — Tag release
Task 45 — Rollback using revert
Task 46 — Handle big conflict
Task 47 — Code review via PR
Task 48 — Protect main branch (concept)
Task 49 — CI/CD trigger (basic)
Task 50 — Full workflow simulation
