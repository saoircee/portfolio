Project asset images

Place the image files used by `index.html` into the `assets/images/` folder and commit them to your repository before deploying to GitHub Pages.

Expected filenames (as referenced in `index.html`):
- IMG_20240810_181132.jpg
- IMG_20241230_135324.jpg
- IMG_20250312_181100.jpg
- IMG_20251123_123542.jpg

Notes:
- Filenames are case-sensitive on GitHub Pages (Linux servers). Make sure the names match exactly.
- Avoid spaces in filenames and folder names. If your images currently live outside the repo (e.g. `C:\Users\...\my pics`), copy them into `assets/images/`.
- After adding images, run: `git add assets/images/* && git commit -m "Add gallery images" && git push` to publish changes.
