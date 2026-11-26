# Aditya Games

An expandable static game arcade for GitHub Pages.

## Add a game
1. Put its standalone HTML, CSS, JavaScript and assets in `games/<game-id>/` with an `index.html` entry point.
2. Append an entry to `games.js` with `title`, `category`, `description`, `path` and optional `image`. Use relative paths. The homepage automatically renders the catalog.
3. Commit the game and catalog together where possible. No homepage edits needed.

## Hosting
In repository Settings > Pages, select Deploy from a branch, main, / (root), and Save. The public site is expected at https://srisriSVM.github.io/aditya_games/ once deployment succeeds. Do not include personal details or secrets in public game files.
