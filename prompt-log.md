# Prompt Log — Activity 12

Every prompt below was sent to the AI assistant in order. Each entry notes
what changed in the output as a result.

---

## Prompt 1 — initial generation (sent 2026-10-11)

> Build a one-page personal portfolio blog as a single self-contained
> index.html file (all CSS inline in a `<style>` block, no external
> dependencies except system fonts, no JavaScript frameworks — plain HTML/CSS
> only, small vanilla JS allowed for mobile nav if needed).
>
> SUBJECT: Pavan B S — 2nd-year B.Tech CSIT student at REVA University,
> Bengaluru. Works in Python (coursework, DSA) and C (systems projects).
>
> SECTIONS (in this order):
> 1. Hero — name "Pavan B S", headline "2nd Year CSIT Student | Python & Data
>    Structures", one-line subhead about building foundations through
>    project-based coursework, and two buttons: "View Projects" (anchor) and
>    "GitHub" (https://github.com/20pavangowda06-png).
> 2. About — 3-4 sentences: who he is, what he's learning (Python, C, DSA
>    through hands-on coursework), and that he's looking for software
>    development internships and collaborations.
> 3. Projects — exactly these three, each as a card with name, one-line
>    description, tech tags, and a link:
>    - "LeetCode Solutions (Python)" — 9 documented Python DSA solutions with
>      complexity analysis — https://github.com/20pavangowda06-png/leetcode-solutions
>    - "Line Editor in C" — team-built CLI line editor (~700 lines,
>      warning-free with -Wall -Wextra), dynamic array of char*, multi-level
>      undo — https://github.com/20pavangowda06-png/line-editor-
>    - "HackerRank — 3-Star Problem Solver" — 19/19 Python problems accepted,
>      220 pts, Silver badge — https://github.com/20pavangowda06-png/HackerRank-3rdSem-Portfolio
> 4. Skills — as pill/tag chips: Python, C, Git, GitHub, Data Structures,
>    Algorithms.
> 5. Contact — GitHub, LinkedIn
>    (https://www.linkedin.com/in/pavan-gowda-922798379/), HackerRank
>    (https://www.hackerrank.com/profile/20pavangowda06) links.
>
> TONE: professional but approachable — confident student, no hype, no
> buzzwords, no invented achievements. Only use facts given here.
>
> STYLE: modern, clean, readable. Dark slate/navy page background, one warm
> amber accent colour, generous whitespace, cards with subtle borders and
> rounded corners, responsive (single column on mobile). System font stack.

**What changed:** produced v1 of index.html — all five sections present,
all three project cards with correct links, skills as chips, contact links
correct.

---

## Prompt 2 — follow-up refinement (sent 2026-10-11)

> In the About section, add a sentence about building the line editor with
> my teammate Pavan Srujan and the lesson it taught me (small, well-tested
> commits), and end with my concrete next goal: earning the 4th HackerRank
> Problem Solving star (475 points).

**Before:** About ended at the generic "looking for internships" line —
no mention of the collaboration or a concrete goal.
**After:** About now names the teammate, states the key lesson, and ends
with the measurable next goal. The page feels personal instead of
template-like.

---

## Prompt 3 — follow-up refinement (sent 2026-10-11)

> Under the hero subhead, add a single "Currently:" line — "Currently:
> pushing toward the 4th HackerRank star · looking for a software
> development internship." Style it subtly in the muted colour with the
> "Currently:" label in the amber accent.

**Before:** hero had no signal of what he's doing *right now* — a recruiter
skimming the top couldn't see direction.
**After:** hero carries a one-line status in muted text with an amber
"Currently:" label; new `.now` CSS class added. Direction is visible in the
first screen.

