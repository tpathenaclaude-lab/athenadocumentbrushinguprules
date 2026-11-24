---
title: AthenaSummary Handbook – Start Here
author: AthenaSummary summary team
date: 2026-11-19
version: 1.0 (house style v0.11, quality checks v0.2)
description: >
How to turn a writer's draft into a 10/10 AthenaSummary, for people and
for AI assistants. Start here, then use the house style and the quality
checklist.
AthenaSummary Handbook – Start Here
This handbook teaches you, or your AI assistant, to turn a writer's draft
into a 10/10 AthenaSummary. It covers the form (house style) and the content
(quality and grading). You need only these three Markdown files.
Contents
What is in this handbook
The four golden rules
When sources disagree
Workflow: from draft to 10/10
Using an AI assistant
Sample prompts
File naming
Glossary
See also
---
What is in this handbook
File	What it covers	Use it when
`00-START-HERE.md`	Rules of the game, workflow, AI prompts	First, and to brief an AI
`01-HOUSE-STYLE.md`	Layout, headings, spacing, boxes, tables, images	Formatting a summary
`02-QUALITY-CHECKLIST.md`	Content checks, grading rubric, feedback	Checking and grading content
Every rule in this handbook comes from four sources. They are listed here
from highest to lowest priority:
the summary lead's decisions (Adrian, AthenaSummary)
the gold-standard example summaries, i.e. summaries graded 10/10
the Writer Manual (August 2026)
the master Word template (August 2026)
---
The four golden rules
Never change the writer's wording.
Formatting changes how text looks, not what it says.
Content feedback goes into Word comments. Missing pieces, such as a
tip, example or checklist, may be drafted inside a comment. The
writer decides whether to use them.
Spelling is reported, not silently fixed.
Spacing comes from paragraph settings, never from empty lines.
Delete blank "spacer" paragraphs and manual page breaks inside a week.
Use the spacing table in `01-HOUSE-STYLE.md` instead.
Nothing may break across a page in an ugly place.
No paragraph, bullet point or table row is split over two pages.
A heading never sits alone at the bottom of a page.
Use the five standard boxes, often and with variety.
Tip, Example, Please note, Stop and think, Mnemonic.
Aim for at least one per page, and 2+ per page for a 10.
---
When sources disagree
Follow the priority list above.
Do: follow a decision that is written in this handbook, even when the
Writer Manual says otherwise. Example: week titles use an en dash
(`Week 1 – Title`), not a colon.
Do: take only the header, footer and logo from the master template.
Don't: copy formatting from the template's sample text. It is not a
formatting reference.
The one exception: box icons come from the template and are always
used, although the gold examples don't have them.
---
Workflow: from draft to 10/10
Save a copy. Never edit the writer's original. Name the copy as in
File naming.
Check the structure (`01-HOUSE-STYLE.md` §3):
title page
table of contents
Exam Analysis on page 3
one block per week
Format the form (`01-HOUSE-STYLE.md` §1–§10):
page setup, headers and footers
headings
spacing and page flow
lists
boxes
tables and images
Update the table of contents. Right-click it, choose Update Field, then
Update entire table.
Check the content (`02-QUALITY-CHECKLIST.md`): go through the
checklist and add your findings as Word comments.
Grade the summary with the rubric in `02-QUALITY-CHECKLIST.md` §2.
Final pass: scroll every page and check the layout points in
`01-HOUSE-STYLE.md` §12, the final layout checklist.
Export only when the writer has processed the comments
(`01-HOUSE-STYLE.md` §11).
---
Using an AI assistant
An AI assistant (for example Claude) can check, report and, with document
tools, apply the formatting. Brief it like this:
Give it all three files at the start of the conversation.
State its role: an AthenaSummary editor who formats and checks, but
never writes or rewrites the summary text.
Ask for a fixed output format: a findings table with location, rule,
problem and fix, plus a grade per rubric column.
Feed it the course material if you have it: syllabus, literature list,
old exams. Without it the AI cannot judge completeness or exam fit, and it
should say so.
Do:
Ask for findings per week, so long summaries stay manageable.
Ask it to quote the first words of the paragraph it means.
Ask it to mark each finding as "form" or "content".
Don't:
Let the AI "improve" or rewrite paragraphs. Only drafted additions in
comments are allowed.
Accept a grade without evidence: each grade needs examples from the text.
---
Sample prompts
1. Format check
```text
# Role
You are an AthenaSummary editor. You know the attached files
00-START-HERE.md, 01-HOUSE-STYLE.md and 02-QUALITY-CHECKLIST.md.
You never change the writer's wording.

# Task
Check the attached summary against 01-HOUSE-STYLE.md.
Work week by week.

# Output format
A Markdown table with the columns:
| Week | Location (first 6 words) | Rule (§) | Problem | Fix in Word |
Then a short list of the 5 most important fixes.
```
2. Content check and grade
```text
# Role
You are an AthenaSummary quality reviewer. Use 02-QUALITY-CHECKLIST.md.
Never rewrite the summary text. Where something is missing (a tip,
example, mnemonic, hook or checklist), you may draft it as a suggestion.

# Input
- The summary (attached).
- Optional: syllabus, literature list, old exams (attached).

# Task
1. Go through every item of the checklist (§3 and §4).
2. Grade the summary with the rubric (§2), per column, with evidence.

# Output format
## Findings
| Week | Location (first 6 words) | Checklist item | Finding | Suggestion |
## Drafted additions
One block per addition: where it goes, which box type, the drafted text.
## Grade
| Rubric column | Grade (1–10) | Evidence |
## Could not check
List the checks that need course material you did not get.
```
3. One week only (for long summaries)
```text
Apply prompts 1 and 2 to Week 3 only. Same output format.
```
---
File naming
Use dashes, no dots or spaces:
`<UNI>-<PROG>-<SKU>-<YEAR>[-<SCOPE>]-<STAGE>`
Example: `TIU-IBA-1027-2627-FORMATTED.docx`
`YEAR` is the academic year, e.g. `2627` for 2026/27.
`SCOPE` is optional, e.g. `WEEK1`.
Common stages: `DRAFT`, `FORMATTED`, `REVIEWED`, `FINAL`.
Course material for a summary uses the same code:
`TIU-IBA-1027-2627-SYLLABUS`, `-LITERATURE`, `-EXAMS`, `-TERMS`.
---
Glossary
Term	Meaning
Box	A one-cell table with a label (Tip!, Example: …) and an icon
Hook	The grey box with the exam question at the start of each week
Checklist	"After studying this week, I know:" + ☐ items, at the start and end of each week
Exam Analysis	Page 3: how the exam is built, with a pie chart and study tips
Gold example	A summary graded 10/10, used as the reference
H1–H4	Heading 1 to Heading 4 (Word styles)
Keep with next / Keep lines together	Word paragraph settings that control page breaks
STYLEREF	A Word field that shows the current Heading 1 in the header
---
