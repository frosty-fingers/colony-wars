# Colony Wars

A GBC-style territory control strategy game. Ants vs Wasps — deploy units, attack territories, and dominate the map.

**[▶ Play it live](https://YOUR_USERNAME.github.io/colony-wars/)** ← update this link once deployed

## How to Play

- **Move:** Arrow keys (desktop) or D-pad buttons (mobile)
- **Deploy unit:** Z key or "Deploy" button
- **Attack adjacent enemy:** X key or "Attack" button
- **End turn:** Enter key or "End Turn" button

Control 6 of 9 territories to win.

## Setup: Deploy to GitHub Pages

1. Create a new GitHub repo (public), e.g. `colony-wars`
2. Upload `index.html` and `.nojekyll` to the repo root
   - Easiest way: on the repo page, click **Add file → Upload files**, drag both files in, commit
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Branch: `main`, folder: `/ (root)` → click **Save**
6. Wait ~1 minute, then visit `https://YOUR_USERNAME.github.io/colony-wars/`
7. On iPhone: open that URL in Safari → tap **Share** → **Add to Home Screen** for an app-like experience

## Files

- `index.html` — the entire game (self-contained, no build step, no dependencies to install)
- `.nojekyll` — tells GitHub Pages to serve the file as-is

## Notes

This is a proof-of-concept. Current scope:
- 3x3 territory grid
- 2 tribes (Ant vs Wasp AI)
- Basic deploy/attack/resource loop

Planned next: more unit types, tribe synergies, map generation variety.
