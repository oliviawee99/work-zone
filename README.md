# work-zone
# Portfolio — Liv

Personal portfolio site showcasing AI-powered HR automation tools.

Built with plain HTML, CSS, and Google Fonts. No frameworks, no build step. 

## Pages

- **Home** (`index.html`) — hero, featured tools, brand statement
- **Portfolio** (`portfolio.html`) — all four projects with details
- **About** (`about.html`) — background, skills, positioning

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `yourname.github.io` for a root site, or any name for a project site)
2. Upload all four files:
   - `index.html`
   - `portfolio.html`
   - `about.html`
   - `style.css`
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch, `/ (root)` folder → Save
6. Your site will be live at `https://yourusername.github.io` (or `https://yourusername.github.io/repo-name` for a project site)

## Customization

All colors are CSS variables at the top of `style.css`:
- `--black`, `--white`, `--red` — primary palette
- `--gray-*` — neutral scale

To update project content, edit the relevant sections in `portfolio.html`.
To update your bio, edit `about.html`.

## Fonts

Uses Google Fonts: DM Serif Display, DM Sans, DM Mono.
No self-hosting required — loads from CDN.
