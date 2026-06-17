# Haleema Fatima — Portfolio

Personal portfolio website built from my CV. Single-file, no build step, deployable anywhere.

## Stack

- Pure HTML + CSS + Vanilla JS
- [Inter](https://fonts.google.com/specimen/Inter) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

## Features

- Cinematic intro loader with incrementing counter and orange wipe reveal
- Scroll-triggered slide-in animations (IntersectionObserver, no libraries)
- McLaren-inspired black & orange theme
- Fully responsive

## Sections

- Hero
- About (education, languages, interests)
- Projects (7 projects with tech tags)
- Skills (grouped by category)
- Leadership & Volunteering
- Contact

## Deploy

**Vercel (recommended)**
```bash
npm i -g vercel
vercel --prod
```

**GitHub Pages**

1. Push `index.html` to the `main` branch
2. Go to Settings → Pages → Source: `main` / `root`
3. Done — live at `https://haleemafatima.github.io/portfolio`

**Netlify**

Drag and drop the `index.html` file at [app.netlify.com/drop](https://app.netlify.com/drop).

## Local Preview

```bash
# Any of these work
open index.html
python3 -m http.server 3000
npx serve .
```

## Contact

- Email: halimahere7@gmail.com
- GitHub: [github.com/HaleemaFatima](https://github.com/HaleemaFatima)
- LinkedIn: [linkedin.com/in/haleema-fatima-271336326](https://linkedin.com/in/haleema-fatima-271336326)
