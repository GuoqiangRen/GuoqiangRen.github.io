# Deploy to GitHub Pages

## Recommended: personal homepage at `https://USERNAME.github.io/`

1. Sign in to GitHub.
2. Create a new repository named exactly `USERNAME.github.io` (replace `USERNAME` with the GitHub username that will own the site).
3. Use a public repository for GitHub Free.
4. Open the repository and choose **Add file → Upload files**.
5. Upload the **contents of this folder** so that `index.html` is directly at the repository root. Do not upload an extra outer folder.
6. Commit the upload to the `main` branch.
7. Go to **Settings → Pages**.
8. Under **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/(root)`
9. Click **Save**.
10. Wait for deployment, then open `https://USERNAME.github.io/`.

## Critical directory structure

The repository root should look like:

```text
USERNAME.github.io/
├── index.html
├── styles.css
├── .nojekyll
├── assets/
│   ├── profile.png
│   └── ...
├── README.md
└── LINK-AUDIT.md
```

Do not make it look like:

```text
USERNAME.github.io/
└── ren-academic-website-github-pages-ready/
    └── index.html
```

That extra folder is the most common reason the homepage returns 404.
