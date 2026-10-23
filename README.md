# Exam Binary

Marketing website for Exam Binary, the AI-powered education management system, and Dokkho AI.

Live site: https://jakariyasamim.github.io/exam-binary-site/

## Files

- `index.html` — the whole site (styles and scripts inline).
- `assets/sky.webp` (+ `sky-1400.webp` for phones) — the hero picture: sky, hill, the man at his desk.
- `assets/sky-far.webp` — the same picture with the man painted out, used only for the blurred far-cloud layer.
- `assets/figure.webp` — the man and his desk, cut from the same picture so the headline passes behind him.
- `assets/logo-white.webp` — the logo with a white wordmark, for the hero.
- `assets/founder-rakib-sky.webp` + `assets/founders-sky.webp` (+ `-1200`), and `assets/founder-shadab-sky.webp` +
  `assets/founders-sky2.webp` (+ `-1200`) — each founder cut out of their blue-sky poster on the full 1672×941
  canvas, and that poster's empty sky and hill. Each pair is shown as two matching full-stage layers.
- The names, roles and quotes live in the Founders section of `index.html`.
- `assets/og.png` — the social preview (a 1200×630 render of the hero).

The hero is laid out on a 1672 × 941 "stage" (`--u` in the CSS = one stage pixel); every position in the
hero's CSS is a measurement on that stage, so the picture and the words scale together.

## Updating

Edit `index.html` or the files in `assets/`, then commit and push to `main` — GitHub Pages redeploys in a minute.
