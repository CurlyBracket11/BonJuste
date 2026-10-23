# Bhumi Aggarwal — Portfolio

A portable Vite project wrapping the original standalone HTML portfolio. The page's HTML, CSS, SVG artwork, and JavaScript are kept together in `index.html` to preserve the supplied design and interactions as closely as possible.

## Requirements

- Node.js 20.19+ or 22.12+ recommended
- npm

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite in your terminal.

## Production build

```bash
npm run build
npm run preview
```

The production output is generated in `dist/`.

## Publish on GitHub

1. Create a new empty repository on GitHub.
2. Extract this project folder.
3. In a terminal opened inside this folder, run:

```bash
git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the remote URL with your own repository URL.

## Before making it public

Review `index.html` and replace the placeholder email (`you@example.com`), `#` project/GitHub/LinkedIn links, and any project or experience details that aren't accurate for you. Keep only claims you can explain and verify. Google Fonts currently loads from the internet, so those fonts may fall back if offline.
