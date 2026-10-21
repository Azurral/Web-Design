# Web Design Contest — Working Agreement

This repo is for a timed web design contest. The actual task/theme is
**announced on-site**; until then, nothing is built.

## How Claude must report to the user

1. **Every new release** (every push that changes the site) ends with a
   **"How to test this release"** section: short, numbered steps the user can
   follow on their phone or laptop (open the page, what to click, what they
   should see, and how to check mobile/desktop sizes).
2. **Whenever the user has to do something themselves** (open a file, enable
   GitHub Pages, upload an image, paste the task text, present to judges…),
   give a numbered **"What you need to do"** guide. One action per step, no
   jargon, say exactly where to tap/click.
3. Keep both guides short. The contest is timed.

## Contest rules that shape the work

- Any tools allowed (HTML, CSS, JS, Bootstrap, Tailwind, AI). Must finish
  within the time limit, then stop and submit.
- AI agents allowed but **free tier only**.
- Contestants may have to **present** design choices and how requirements
  were met, and may show the **AI prompt history**.
- Facilitator may change rules on-site.

## Judging criteria (optimize in this order)

| Criteria | Points | What it means for us |
|---|---|---|
| Visual Design & UX | 40 | Layout, colour harmony, typography, consistency, readability, easy navigation |
| Creativity & Innovation | 30 | Original concept, unique ideas, creative visuals, fresh way to present content |
| Relevance to Task | 20 | Hits the theme, objectives, target audience, required features |
| Functionality & Responsiveness | 10 | Interactions work; looks right on phone, tablet, desktop |

## Build defaults

- Plain static site (`index.html` + CSS/JS), no build step, so it opens by
  double-clicking and works offline at the venue.
- Mobile-first, test at 375px, 768px and 1280px widths.
- Keep a short `PRESENTATION.md` of design choices and how each requirement
  is met, so the user can present it.
