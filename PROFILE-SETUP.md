# One-Page GitHub Portfolio

This version fixes the card-overlap problem in the previous animated profile.

## Why the old version broke

The previous SVG files animated CSS `transform` on groups that also used SVG `transform="translate(...)"`.
GitHub/browser SVG rendering can replace the original transform during animation, causing cards to move to the SVG origin and overlap.

This version avoids transform animation completely.

Animations are limited to:

- opacity pulsing
- subtle background breathing
- animated dashed connector lines
- glow effects

All portfolio components now live inside a single:

`assets/portfolio.svg`

## Structure

```text
ChaminduAttanayaka/
├── README.md
├── PROFILE-SETUP.md
└── assets/
    └── portfolio.svg
```

## Install

Copy these files into the special GitHub profile repository:

`ChaminduAttanayaka/ChaminduAttanayaka`

Then run:

```bash
git add README.md PROFILE-SETUP.md assets/portfolio.svg
git commit -m "feat: add one-page animated engineering portfolio"
git push origin main
```

## Important

Keep the `portfolio.svg` path unchanged because `README.md` loads:

`./assets/portfolio.svg`

The links below the SVG remain regular Markdown links because individual areas inside an SVG embedded through an `<img>` tag are not reliably clickable on GitHub.
