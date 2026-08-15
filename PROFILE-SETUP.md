# One-Page Animated GitHub Portfolio v3

This version replaces CSS keyframe animations with native SVG/SMIL animation.

## Why

GitHub may render CSS animation inside repository SVGs inconsistently.
This version uses `<animate>` directly inside SVG elements.

## Animated elements

- engineering-online status light
- central platform pulse rings
- moving dashed data-flow lines
- capability/focus status dots
- technology telemetry lines
- project activity indicators
- section data-flow indicators
- bottom telemetry heartbeat
- subtle animated page border

No card positions are animated, so the layout remains fixed.

## Install

Replace your current `assets/portfolio.svg` and `README.md`, then:

```bash
git add README.md assets/portfolio.svg
git commit -m "fix: use native SVG animation for GitHub profile"
git push origin main
```

If GitHub still shows the old SVG after pushing, hard-refresh the profile page or rename
`portfolio.svg` to `portfolio-v3.svg` and update the README path to bypass image caching.
