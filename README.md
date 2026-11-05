# Personal site

A single-page site (plain HTML/CSS, a few lines of JS). No build step.

## Files
- `index.html`: all content. Look for `EDIT:` comments.
- `styles.css`: colors and fonts are variables at the top.
- `script.js`: mobile menu and footer year.
- `assets/`: favicon; drop `resume.pdf` here.

## Adding a project
In `index.html`, copy one `<article class="card"> ... </article>` block, paste it, and edit it.
Status badge classes: `status-live` (Delivered), `status-transit` (In transit), `status-planned` (Planned).

## Preview locally
Open `index.html` in a browser.

## Publish on GitHub Pages
1. On GitHub, create a new public repository named `<your-username>.github.io`
   (this gives you the address `https://<your-username>.github.io`).
2. Upload these files to the repository root: "Add file" > "Upload files",
   drag in everything (including the `assets` folder and `.nojekyll`), then "Commit changes".
3. Go to Settings > Pages. Under "Build and deployment", pick Source: "Deploy from a branch",
   Branch: `main`, folder `/ (root)`, and Save.
4. After a minute or two the site is live at `https://<your-username>.github.io`.

Any later change you commit to `main` republishes automatically.
