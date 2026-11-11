# Codex handoff: publish Cole Pylant portfolio with GitHub Pages

Goal: publish this static portfolio as Cole's professional recruiting website.

## Preferred URL
If the GitHub username is `coledpylant`, use a user-site repository named exactly:

`coledpylant.github.io`

This yields the clean URL:

`https://coledpylant.github.io/`

If that repository already exists or the username differs, use the actual GitHub username and follow GitHub Pages conventions.

## Instructions
1. Create or use the GitHub repository `<username>.github.io`.
2. Put the CONTENTS of this folder at the repository root. `index.html` must be at the root, not inside another directory.
3. Preserve the current directory structure and relative links:
   - `index.html`
   - `styles.css`
   - `projects/`
   - `assets/images/`
   - `assets/docs/`
4. Commit and push to the repository's default branch.
5. In GitHub Pages settings, publish from the default branch root if the user site does not publish automatically.
6. Confirm every page loads and every local artifact link resolves.
7. Check desktop and mobile layouts.
8. Do not rewrite project claims or add metrics that are not already in the site/source materials.
9. Do not add a personal-story-heavy biography. Keep the site broadly positioned around analytics, data science, economics, optimization, visualization, and applied problem solving.
10. Do not add ParKing yet; it is unfinished.

## Quality checks before declaring the site live
- Home page loads at the root URL.
- TrialSignal, CVaR, Steam Recommender, Marriage Outcomes, EV Adoption, and Tableau case-study pages all load.
- PDF/DOCX/IPYNB/TWBX download links work.
- No broken images.
- Email and LinkedIn links work.
- Page title/description render correctly.
- No secrets, API keys, tokens, local paths, notebook credentials, or private data are published.

## Important notebook safety check
Before committing `.ipynb` files, scan notebook metadata, markdown, code, and outputs for API keys, access tokens, private URLs, local credentials, or personally sensitive data. Remove secrets if any are present while preserving the analytical work.
