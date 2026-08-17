# Fire & Ice Associate Rally — Food & Beverage Trivia

Projector-first HTML trivia show with 100 food & beverage questions for the Fire & Ice associate rally.

## Files
- `index.html` — projector presentation and primary controls
- `operator.html` — separate compact control window for the person running trivia
- `questions.js` — all 100 questions and answers
- `app.js` — timer, randomization, saved session, keyboard controls, ticket counter, and remote sync
- `fire-and-ice-logo.png` — official Fire & Ice logo used by the presentation

## Rally controls
- **Space / Enter** — reveal or hide answer
- **Right / Left Arrow** — next / previous
- **R** — random unused question
- **T** — start or pause timer
- **Shift + T** — reset timer
- **O** — hide/show projector controls
- **F** — fullscreen
- **Q** — question picker
- **+ / -** — ticket count
- **Esc** — title screen

Progress, ticket count, question order, and randomized answer positions are saved in the browser.

## Operator remote
Open `operator.html` in a second window on the same computer/browser. Keep it on the laptop display while `index.html` is on the projector. The two windows synchronize automatically.

## Fire & Ice logo
The official Fire & Ice logo is already included in the repository as `fire-and-ice-logo.png`.

## GitHub Pages
Publishing source: **main** branch, **/(root)**.

Project site URL: `https://ryangivans.github.io/Trivia/`

The capital **T** in `/Trivia/` matches the repository name.

Deployment refresh triggered after GitHub reported Actions and Pages operational on August 17, 2026.
