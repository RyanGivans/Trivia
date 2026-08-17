# Fire & Ice Associate Rally — Food & Beverage Trivia

Projector-first HTML trivia show with 100 food & beverage questions for the Fire & Ice associate rally.

## Files
- `index.html` — projector presentation and primary controls
- `operator.html` — separate compact control window for the person running trivia
- `questions.js` — all 100 questions and answers
- `app.js` — timer, randomization, saved session, keyboard controls, ticket counter, and remote sync
- `fire-and-ice-logo.png` — add the official Fire & Ice logo using this exact filename

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

## Add the official logo
Upload the Fire & Ice logo to the repository root as `fire-and-ice-logo.png`. Until then, the presentation uses a text fallback.

## Publish with GitHub Pages
Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)** and save.