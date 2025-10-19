# Shaan Bhakta — Personal Site (DSC 106 Lab 1)

Minimal static site suitable for DSC 106 Lab 1. Plain HTML5 + CSS. No build step required.

Files created
- `index.html` — homepage
- `style.css` — shared stylesheet
- `images/` — images folder (add `me.jpg` here)
- `projects/index.html` — projects page
- `contact/index.html` — contact page with mailto form
- `cv/index.html` — CV page

Run locally with VS Code Live Server

1. Open this folder in VS Code.
2. Install the Live Server extension if you don't have it.
3. Right-click `index.html` and choose "Open with Live Server" (or use the status bar button).

Publish on GitHub Pages

1. Create a new repository on GitHub and push this folder's contents to the `main` branch.
2. In the repository settings > Pages, set the source to the `main` branch (root). Save.
3. Your site will be available at `https://<your-username>.github.io/<repo>/` (allow a few minutes for the first publish).

Notes

- Replace `https://github.com/YOUR_USERNAME` in the nav links with your GitHub profile URL.
- Add a `images/me.jpg` portrait image if desired; the pages use a relative path `images/me.jpg`.
- The subpages (`/projects/`, `/contact/`, `/cv/`) assume a folder-per-page layout so links use `/projects/` etc. This works on GitHub Pages and Live Server.
