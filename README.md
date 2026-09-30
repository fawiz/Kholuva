# Kholuva website

React + Tailwind CSS v4 (Vite).

## Run

```bash
npm install
npm run dev
```

Open the local URL Vite prints (usually http://localhost:5173).
Requires Node 20.19+ (or 22.12+).

## Where things live

- `src/content/site.js`   all homepage text, nav links, product data (edit copy here)
- `src/index.css`         colour, font, shadow and animation tokens
- `src/components/`       layout, ui, home sections and placeholder artwork
- `src/pages/Home.jsx`    the homepage (compose sections here)

## Replacing placeholder artwork with real photos

1. Put images in `public/images/` (e.g. `hero-bottle.png`).
2. In `src/content/site.js` set `hero.image = "/images/hero-bottle.png"`
   and each product's `image` (e.g. `"/images/black-mustard-oil.jpg"`).
The illustrated placeholders switch off automatically once an image path is set.
