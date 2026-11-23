# The Fount of Knowledge and Wisdom: A-level Sociology

A free revision site for AQA A-level Sociology, built on the same engine and design as the A-level psychology Fount.

- **2,682 questions** across Key concepts, Theories, Research methods, Education, Methods in context, Families and households, Beliefs in society, Crime and deviance, and Exam skills.
- Flashcards (multiple choice, type it, gap fill), quick quizzes, spaced repetition and a mistakes bank.
- Writing: 10-, 20- and 30-mark essays with Items and self-marking plans, Plan the research, and mini mock papers for Papers 1–3.
- Arcade: Daily 10, Sociodle, Weekly Challenge, Boss Battles, Data Skills, Study Detective, Who Am I?, Connections, Sort It, Timeline, Put It in Order, Spot the Flaw, Higher or Lower, Build the Paragraph, Be the Examiner and more.
- XP, 120 ranks, badges, themes, and **Professor Acorn the sociology squirrel**, who grows as students revise.

It's a static site (`index.html` plus a few small files) with no build step and no accounts. Progress is saved in each student's browser.

## Things to set before going live

- **Exam dates:** edit `EXAMS` in `index.html` (currently placeholder dates in May/June 2027).
- **Year 12 / 13 unlocks:** `Y12_OPEN` hides Crime and Beliefs from Year 12 games; add dates if you want topics to unlock mid-year.
- **Usage stats (optional):** set `ANALYTICS_URL` to your own Google Apps Script web app. It is blank, so nothing is sent.
- **Class leaderboard (optional):** fill in `LB_CONFIG` if you want the Firebase leaderboard. It is off by default.
- **Teacher tool:** `teacher.html` reads progress-report codes from students.

When you update `index.html`, bump `VERSION` in `sw.js` so installed copies pick up the change.
