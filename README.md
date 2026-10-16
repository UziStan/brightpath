# BrightPath Practice (Grades 3–8)

A first, browser-based prototype for family practice in Canada. It is a static HTML/CSS/JavaScript app; no build tools, account, or paid hosting are required.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Choose a grade, subject, topic, question count, timer, and marking mode.

## Publish free using Cloudflare Pages
1. Create a GitHub account if you do not already have one.
2. Create a new repository named `brightpath-practice`.
3. Upload `index.html` to the repository root (and optionally this README).
4. In Cloudflare, open Workers & Pages, create a Pages project, and connect the GitHub repository.
5. For a plain static HTML site, leave the build command blank and set the output directory to `/` (repository root) if the setup screen asks for it.
6. Deploy. Cloudflare will provide a `*.pages.dev` URL you can open on phones, tablets, and computers over the internet.

Hosting provider interfaces can change; follow the current on-screen prompts. The first version needs no secrets or environment variables.

## Current prototype features
- Grades 3–8; Maths, Quantitative Aptitude, Verbal Aptitude
- Topic selection, Easy/Medium/Challenge/Mixed difficulty
- 10, 20, 30, 50, 100 questions
- Untimed or 5–60 minute timer
- Instant learning feedback or end-of-test scoring
- Question navigation, flag for review, explanations, score summary, topic summary
- Retry missed questions, print/save results, local history on the same browser

## Important prototype limitations
- This is an initial demo question bank, not a complete provincial curriculum resource. Canadian curricula differ by province/territory. Questions should be reviewed and expanded against the learner's province and school expectations before relying on this as a comprehensive curriculum tool.
- Long sessions can repeat questions because the starter bank is intentionally small.
- Progress is stored only in the browser/device used. It does not sync across devices and clearing browser data can remove it.
- The timer is a practice timer, not an official exam timing recommendation.
- There is no account system, remote database, analytics, or teacher/parent dashboard.
