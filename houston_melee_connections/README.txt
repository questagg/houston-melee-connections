Houston Melee Connections

PUBLIC WEBSITE FILES:
- index.html
- puzzle.json

Upload those two files to Netlify, GitHub Pages, or any static website host.
Friends can play the game, toggle dark mode, reset, shuffle, and reveal.
They cannot edit the hosted puzzle from the public page.

PRIVATE EDITOR FILE:
- admin_editor.html

Keep admin_editor.html on your own computer. Open it locally when you want to make a new puzzle.
Use Export Puzzle File, save it as puzzle.json, and re-upload puzzle.json to your website.

Important:
This is a static website. Friends cannot permanently change your live site unless you give them access to your Netlify/GitHub account or upload permissions.
Any browser changes they make, such as progress or dark mode, only save on their own device.


Latest changes:
- Public game page has no Reveal button.
- Dark mode is toggleable from the public page.
- Edit Fun fact of the week in admin_editor.html, then export your puzzle JSON and upload it as puzzle.json.

This version has a redesigned public page inspired by the provided mockup, including a centered title divider, fun fact card, footer, sleek dark-mode gradient, and a puzzle date field. Edit the date in admin_editor.html, export puzzle.json, and upload it with index.html.


LOCAL PREVIEW NOTE
If you open index.html by double-clicking it, some browsers block index.html from reading puzzle.json. This is normal browser security.

For local testing, either:
1. Open index.html and use the Local preview helper to select your exported puzzle.json, or
2. Run a tiny local server from this folder, then open http://localhost:8000
   Windows/Mac: if Python is installed, open Terminal/Command Prompt in the folder and run:
   python -m http.server 8000

On Netlify/GitHub Pages, index.html will read puzzle.json automatically as long as puzzle.json is uploaded in the same folder.
