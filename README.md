# Happy Teachers' Day — Loving Message Generator

A lightweight, single‑page web app to generate a warm, personalized Teachers' Day message. Built with Tailwind CSS (CDN) and vanilla JavaScript — no build step required.

## Features
- Random, heartfelt message templates
- Personalization with title (Sir/Madam) and name
- Clean, responsive UI with glassmorphism
- Smooth fade‑in animation for the generated message

## Quick Start
1. Ensure you have an internet connection (Tailwind loads from a CDN).
2. Open `index.html` in your browser (double‑click the file).
3. Select a title, enter the teacher’s name, and click “Generate Loving Message”.

## Project Structure
```
.
├── index.html   # App UI + JS logic + Tailwind via CDN
└── README.md
```

## Customization
- Add or edit message templates:
  - In `index.html`, find the `lovingMessages` array in the `<script>` block and add your own strings.
  - Use `{name}` and `{title}` placeholders to auto‑insert inputs.
- Add more titles:
  - In `index.html`, update the `<select id="teacherTitle">` with new `<option>` entries.
- Tweak styles:
  - Tailwind classes are used throughout; adjust classes in the HTML to change spacing, colors, and layout.
  - The background gradient and fade‑in animation are defined in the `<style>` tag near the top of the file.

## Troubleshooting
- Tailwind styles not loading? Confirm you’re online or replace the CDN link with a local build of Tailwind.
- Special characters in names: Most are supported; ensure your file is saved as UTF‑8 (default here).

## Notes
- This page is fully static and can be hosted anywhere (GitHub Pages, Netlify, static file server).
- No analytics or external scripts beyond Tailwind CDN.

## License
This project is provided as‑is for personal/educational use. Add your preferred license if you plan to redistribute or modify publicly.
