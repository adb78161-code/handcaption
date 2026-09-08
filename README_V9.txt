HandCaption V10
================

V10 is based on the working V9.2 multi-stroke handwriting build.

Main additions
---------------
1. Handwriting creator
- 62 characters: A-Z, a-z, 0-9
- Multiple strokes per character
- Undo/redo for the current character
- Redraw, Back, Next, checklist navigation
- Saved packs remain local

2. Pack backup
- Export a handwriting pack as JSON
- Import a previously exported pack
- Existing V5-V9 packs are migrated when all 62 glyphs are valid

3. Caption editor
- Multiple caption layers (up to 15)
- Add/update, duplicate, delete
- Drag captions on photos
- Size, color, rotation, spacing, shadow, opacity
- Fade, slide, pop and write-on animations
- Undo/redo editor history
- Video start/end timing per caption

4. Photo export
- Local PNG export
- No media upload

5. Video export
- Local WebM export when MediaRecorder + canvas capture are supported
- Video audio track is preserved when the browser exposes it
- MP4 export is not guaranteed by Android browsers

Security/privacy notes
----------------------
- No login and no external JS libraries
- LocalStorage is used for handwriting packs
- Object URLs are revoked when media is removed/page is left
- File types and sizes are checked before opening
- CSP meta policy is included
- GitHub Pages hosting is static; a meta CSP is not the same as an HTTP response header
- LocalStorage is not encrypted

Files
-----
index.html
style.css
app.js
README_V10.txt

Deployment
----------
Replace the existing index.html, style.css and app.js in the GitHub Pages repository with these V10 files. Keep the repository root structure so index.html is at the top level of the Pages publishing source.
