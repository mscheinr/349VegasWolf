# Vegas Wolf

Deployment-ready static site for GitHub Pages.

## Files
- `index.html` — the app
- `.nojekyll` — tells GitHub Pages to serve the site as-is

## Publish on GitHub Pages
1. Create a new public repository on GitHub. A simple name like `vegas-wolf` is fine.
2. Upload both files in this folder to the repository root.
3. In GitHub, open **Settings** > **Pages**.
4. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Save. Wait about 1–3 minutes.
6. Your site will appear at:
   `https://<your-github-username>.github.io/<repo-name>/`

## Notes
- This is a static HTML app, so GitHub Pages is a good fit.
- Local save data uses browser localStorage, so each device/browser keeps its own saved state.
