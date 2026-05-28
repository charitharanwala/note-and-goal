To Do List and Goals App Source

This folder is for modifying and sharing the app.

Main file to edit:
github-todo-goals.html

Desktop app files:
main.js
package.json
Run_App.bat
Build_Windows_App.bat

PWA / GitHub Pages files:
todo-goals.webmanifest
todo-goals-sw.js
todo-goals-icon.svg
icon.png

How to run the desktop app:
1. Install Node.js if it is not installed.
2. Double-click Run_App.bat.

How to build a portable Windows EXE:
1. Double-click Build_Windows_App.bat.
2. Look in the dist folder when it finishes.

How to use as a GitHub Pages PWA:
1. Upload github-todo-goals.html, todo-goals.webmanifest, todo-goals-sw.js, todo-goals-icon.svg, and icon.png.
2. Open github-todo-goals.html from the GitHub Pages HTTPS URL.
3. On iPhone or iPad, tap Share, then Add to Home Screen.

How to deploy to Cloudflare Workers:
1. Keep wrangler.jsonc in the project root.
2. Keep the website files inside the public folder.
3. Use this deploy command:
   npx wrangler deploy

If Cloudflare asks for an output/static folder, use:
public
