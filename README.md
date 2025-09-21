# js-dos GitHub Pages Example

This repository is a minimal example you can upload to GitHub to host **js-dos** on GitHub Pages.

## Steps to use

1. Replace the placeholder file in `bundle/` with your js-dos bundle:
   - A *js-dos bundle* can be a `.jsdos` directory zipped, or a `.zip` that follows js-dos bundle conventions.
   - Name it `mygame.jsdos` (or change the default path in `index.html` / the input box on the page).
2. Commit & push the repository to GitHub.
3. Enable GitHub Pages for the repository:
   - Go to **Settings → Pages** and choose the branch (e.g. `main`) and folder (`/ (root)`).
   - Save and wait a minute for deployment. Your site will be at `https://username.github.io/repo-name/`.
4. Open the site, and the emulator will try to load `/bundle/mygame.jsdos`.

## Notes & troubleshooting

- Browsers require files to be served over HTTP(s) for WASM and fetch to work — GitHub Pages works fine.
- If loading fails, open the browser console (F12) to see fetch/CORS errors or 404s.
- If you have a game that uses copyrighted game data (e.g., commercial DOS titles), **do not** upload copyrighted files unless you have the right to distribute them.

## References

- js-dos docs: https://js-dos.com
- GitHub Pages docs: https://pages.github.com
