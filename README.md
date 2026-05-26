# HWYL — Editorial Posters & Commissions

Static portfolio + commission landing for HWYL Studio.

## Run locally

Open `index.html` in any browser, or serve the folder:

```bash
npx serve .
```

## Stack

- Vanilla HTML + CSS (OKLCH design tokens, CSS custom properties)
- Vanilla JS + [Motion One](https://motion.dev) via ESM CDN for hero scroll dissolve and thumbnail FLIP swap

## Deploy

Static site — drop the repo into Vercel, Netlify, or GitHub Pages. Entry point is `index.html`. No build step.

## Structure

```
index.html                 Main page
logo-*.png                 Brand marks
*-poster.jpg               Live editions (hero + shop)
bg-abstract-texture.jpg    Fixed body texture
reference/                 Unused artwork + early prototypes (not shipped in deploy)
CLAUDE.md / DESIGN.md      Design system + project notes
```
