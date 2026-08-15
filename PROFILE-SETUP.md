# One-Page Animated GitHub Portfolio v2

This enhanced version keeps the stable one-page layout while adding more GitHub-safe animation.

## Added animation

- animated outer border flow
- additional network/data-flow lines
- pulsing status nodes
- live telemetry indicators
- central platform glow rings
- activity lights on project cards
- animated technology-row signals
- subtle footer heartbeat/data line

## Safe animation rule

No CSS transform animation is used on positioned SVG groups.

That avoids the overlap bug seen in the earlier multi-section design.

## Files

```text
README.md
PROFILE-SETUP.md
assets/
  portfolio.svg
```

## Update your GitHub profile

```bash
git add README.md PROFILE-SETUP.md assets/portfolio.svg
git commit -m "feat: enhance animated GitHub portfolio"
git push origin main
```
