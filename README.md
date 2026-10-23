# Little AI Library

An interactive beginner AI textbook built with HTML, CSS, and vanilla JavaScript. Contains 28 lessons across 7 chapters, worked examples, multiple-choice and fill-in exercises, two interactive controls, an interview notebook, saved progress, bookmarks, dark mode, and page-turn animation.

## Run locally

From this directory, run `python3 -m http.server 5173 --directory dist` and open http://localhost:5173.

## Structure

- `dist/index.html`: semantic app shell
- `dist/style.css`: responsive book layout and animations
- `dist/content.js`: original lesson and interview content
- `dist/app.js`: interactions and browser-local persistence

No package installation or compilation is required. Google Fonts are optional; system fonts are used if unavailable. Lessons and application code are bundled locally. Storage does not sync between devices. There is no code execution service or automated grading of interview notes: fill-in exercises validate expected answers.

This is an introductory learning companion, not an exhaustive university textbook or guarantee of interview success. Further reading and project recommendations are available in the app. A native macOS wrapper can be added later.
