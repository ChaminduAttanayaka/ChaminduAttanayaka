# Final Animated GitHub Portfolio

## Design

This package uses one continuous GitHub-native SVG dashboard.

The background has been changed to:

- clean deep navy
- very subtle blue engineering grid
- restrained top hero glow
- no large purple/blue background blobs

Animations use native SVG `<animate>` elements and do not move card positions.

## Package

```text
README.md
PROFILE-SETUP.md
assets/
└── portfolio.svg
```

## Install

Copy the files into:

`ChaminduAttanayaka/ChaminduAttanayaka`

Then run:

```bash
git add README.md PROFILE-SETUP.md assets/portfolio.svg
git commit -m "feat: finalize animated GitHub engineering portfolio"
git push origin main
```

## GitHub cache

If GitHub displays an older version of the SVG, rename:

`assets/portfolio.svg`

to:

`assets/portfolio-final.svg`

and update README.md:

```html
<img src="./assets/portfolio-final.svg" width="100%" alt="Chamindu Attanayaka - DevOps Cloud Platform Engineering Portfolio" />
```
