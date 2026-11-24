# Jasier's Space

Personal productivity PWA: an Eisenhower matrix for tasks and a buy list (Amazon cart / wish list).

- Plain HTML/CSS/JS, no build step. Data is stored in the browser (localStorage); use Menu → Export backup to move it.
- Hosted on Vercel: https://jasiers-space.vercel.app
- Service worker cache name is in `sw.js` (`space-v5`); bump it when shipping changes.

## Deploys
Pushing to `main` deploys to production on Vercel automatically.
