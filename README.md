# PSY 6703 — Work Motivation and Emotions

Public syllabus hosting for PSY 6703 (Work Motivation and Emotions), a graduate
seminar in the Department of Psychology, The University of Oklahoma.
Instructor: JeongJin Kim, Ph.D.

Student-facing page: https://psy6703.jeongjinkim.com/

## Structure

- `index.html` — root landing page listing offerings
- `f26/` — Fall 2026 offering
  - `index.html` — landing page with embedded syllabus
  - `syllabus.pdf` — current syllabus (stable URL; superseded versions live in git history)

## Updating the syllabus

Run `update-syllabus` locally. The script copies the newest finalized PDF export
from the course folder into `f26/syllabus.pdf`, refreshes the "Last updated"
date on the landing page, commits, and pushes. GitHub Pages redeploys
automatically; the student URL never changes.
