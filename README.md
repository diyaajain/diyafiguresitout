# Diya Jain — Portfolio Site

My personal portfolio site — a "field journal" themed single-page site covering my projects, skills, certifications, experience, and a bit about what I'm into outside of code.

🔗 **Live site:** _add your deployed link here (e.g. GitHub Pages / Netlify / Vercel URL)_

## Built with

Plain HTML, CSS, and JavaScript — no frameworks, no build step.

- **HTML5** for structure
- **CSS3** — custom properties (design tokens), CSS Grid & Flexbox for layout, no external UI library
- **Vanilla JavaScript** for interactivity (no dependencies)
- **Google Fonts** — Fraunces (display/italic accents) and Nunito (body text)

## Features

- Light / dark ("day" / "night") theme toggle, saved to `localStorage`
- Fully responsive layout, with a collapsible mobile nav
- An ink-drop cursor trail on desktop (respects `prefers-reduced-motion`)
- A tiny pixel-art duck that wanders the page
- Sections for projects, skills, certifications, what I'm currently learning, work/education timeline, off-duty interests, and contact info

## Project structure

```
.
├── index.html        # all page content/markup
├── styles.css         # design tokens + all styling
├── script.js          # theme toggle, mobile nav, cursor trail, scroll-to-top, photo zoom
├── diya-photo.png     # hero portrait (cutout)
└── resume.pdf          # downloadable/viewable resume
```

## Running it locally

No build tools required. Either:

- Open `index.html` directly in a browser, **or**
- Serve the folder locally for the most accurate experience (some browsers restrict local file access):

  ```bash
  python3 -m http.server 8000
  ```

  then visit `http://localhost:8000`.

## Deploying

Since it's static files, it can be hosted anywhere — GitHub Pages, Netlify, Vercel, etc. For GitHub Pages: push this repo, then enable Pages in the repo settings (serve from the `main` branch root).

## Contact

- **Email:** diyadeepi.jain@gmail.com
- **LinkedIn:** [linkedin.com/in/diyajain08](https://www.linkedin.com/in/diyajain08/)
- **GitHub:** [github.com/diyaajain](https://github.com/diyaajain)
