# For Itishree

A small interactive surprise page (plain HTML, CSS and JavaScript, no build step).

## Files
- `index.html` the whole page
- `assets/song.mp3` music (starts at 0:27 of the original track)
- `assets/photo.jpg` photo shown in the final letter

## Edit the words
Open `index.html` and search for `Edit these to personalize`. Change `FRIEND`, `FROM`, `REASONS` and `LETTER`.

## Publish on GitHub Pages
1. Create a new repository on GitHub (for example `for-itishree`).
2. Upload everything in this folder, keeping the `assets` folder.
3. Go to Settings > Pages, set Source to "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. After a minute your link will be `https://<your-username>.github.io/<repo-name>/`.

Test locally by running `python3 -m http.server` in this folder and opening http://localhost:8000.
