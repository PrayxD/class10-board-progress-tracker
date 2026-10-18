# Class 10 Board Journal

A calm, no-account progress tracker for CBSE Class 10 board preparation. Track every chapter across **Theory**, **Questions** and **PYQs**, and see at a glance what is left to study.

**Live site:** https://prayxd.github.io/class10-board-progress-tracker/

## Features

- Chapter-by-chapter tracking for every subject, with three independent controls per chapter: Theory, Questions and PYQs (Not started, In progress, Completed)
- Instant progress for each chapter, each subject and the whole syllabus
- Dashboard with overall progress, per-subject progress, Theory, Questions and PYQs totals, and a "Still to do" list
- Search, filters (All, Not started, In progress, Completed) and collapsible subjects
- Add, rename and delete subjects and chapters
- Pre-filled with the 2026-27 chapter lists for Mathematics, Science, Social Science, English and Hindi (Course A)
- Share a read-only snapshot of your progress with a link
- Export and import your progress as JSON for backup and recovery
- Works on phones, tablets and desktops, and follows light and dark mode

## How progress is calculated

- Each chapter has three parts: Theory, Questions and PYQs. Each part is worth one third of the chapter.
- Completed counts as a full part, In progress counts as half a part, Not started counts as zero.
- A subject's progress is the average of its chapters.
- Overall progress is the average of all chapters, each with equal weight. Empty subjects are ignored.

## Your data and privacy

- There is no server and no account. Everything is saved in your own browser (local storage), so clearing site data erases it. Use **Export** to keep a backup.
- A **Share** link stores a copy of your progress after the `#` in the address. Browsers do not send that part to the server, so the site never receives it. Anyone you give the link to can see your chapter names and progress, so share it only with people you trust.

## Run it locally

Open `index.html` in any modern browser. There is no build step and nothing to install.

## Customising the syllabus

Chapters can be added, renamed and deleted inside the app. To change the defaults for new visitors, edit the chapter lists near the top of the script in `index.html` (the `seed()` function and the `EN` and `HI` lists).

The chapter lists follow NCERT books and the 2026-27 CBSE syllabus where it could be confirmed. Schools can differ, so delete any chapter yours skips.

## Credits

© 2026 PrayxD. All rights reserved.
