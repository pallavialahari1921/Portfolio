# Pallavi Alahari – Portfolio

A static portfolio website (HTML, CSS, JavaScript). No build step, no backend.

## Files
| File | Purpose |
|---|---|
| `index.html` | The whole page: Hero, About, Experience, Skills, Highlights, Education, Contact |
| `css/styles.css` | All styling, responsive breakpoints (900px, 600px), print styles |
| `js/main.js` | Mobile menu, current-section highlight in the nav, footer year |
| `assets/images/portrait.jpg` | Hero portrait (replace with a new photo of the same name to update) |
| `assets/images/favicon.svg` | Browser-tab icon ("PA") |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |
| `README.md` | This guide |

## Publish on GitHub Pages
1. Sign in at github.com and click **New repository**. Name it e.g. `Portfolio`, set it to **Public**, click **Create repository**.
2. On the new repo page click **uploading an existing file**.
3. Unzip the project and drag the **contents** (index.html, css, js, assets, .nojekyll, README.md) into the upload area. `index.html` must be at the top level of the repo, not inside an extra folder. Click **Commit changes**.
   - If `.nojekyll` is hidden on your computer it can be skipped; the site still works.
4. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch **main**, Folder **/ (root)**, then **Save**.
5. Wait 1–2 minutes. Your site will be at `https://YOUR-USERNAME.github.io/Portfolio/`.
6. To update later: open a file in the repo, click the pencil icon, edit, and commit.

All paths are relative, so the site works at `/Portfolio/` or at a user site (`YOUR-USERNAME.github.io`).

## Before publishing – replace/confirm
- `index.html`: search for `TODO` and `REVIEW` comments.
- Finance Intern dates shown as `[Dates to be added]`.

## Links that use your own details (verify each works)
- Email: `mailto:pallavialahari1921@gmail.com`
- Phone: `tel:+447553819965`
- LinkedIn: `https://www.linkedin.com/in/pallavialahari`
