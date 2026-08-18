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

## Where the syllabus is authored

This repo hosts the published PDF only. The syllabus itself is authored in Word,
in the course folder:

    Dropbox/OU/Teaching/03. F26/F26_PSY 6703-001 - Work Motivation and Emotions/

The newest `PSY_WorkMotivationEmotion_Fall2026_syllabus_v*.docx` is the source of
truth. Revisions are made by editing that file directly and saving a new version
number. An earlier Markdown-to-docx build pipeline was retired on August 18, 2026
and now lives in `_archive/` in the course folder; it is three versions stale and
should not be run against the current document.

## Updating the syllabus

1. Edit the newest `.docx` in Word, saving it under a new version number.
2. File > Save as > PDF, into the same course folder, matching the docx name.
3. Run `update-syllabus` locally.

The script copies the newest finalized PDF export from the course folder into
`f26/syllabus.pdf`, refreshes the "Last updated" date on the landing page,
commits, and pushes. GitHub Pages redeploys automatically; the student URL never
changes.

Note that step 3 selects the most recently modified `*syllabus*.pdf` in the
course folder, so make sure the export in step 2 actually succeeded before
running it.
