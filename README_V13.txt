HandCaption V13 — Liquid Studio UI

V13 is a UI/UX redesign built on the working V12 functionality.

Design direction:
- Frosted glass cards with soft depth and layered shadows.
- Mint, sage, lavender and warm neutral accents inspired by the supplied references.
- Mobile-first navigation and larger touch targets.
- Home dashboard with quick actions.
- Cleaner handwriting, preview, pack and media-studio sections.
- Reduced-motion support and a non-backdrop-filter fallback.

The redesign keeps the existing element IDs and browser-local editor logic so the handwriting, pack, project, photo and video workflows continue to work.

Deployment:
1. Back up the current live files.
2. Replace index.html, style.css and app.js in the GitHub Pages repository.
3. Keep index.html in the repository root.
4. Wait for GitHub Pages to redeploy.

No login is added. Media processing remains local to the browser.
