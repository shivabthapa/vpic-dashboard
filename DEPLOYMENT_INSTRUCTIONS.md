# Deploy this site with GitHub Pages

No repository, account, or publishing action was performed. Do not upload this folder until you are ready to make its research content public.

1. Sign in to GitHub and create a new repository. Choose a name such as `vpic-dashboard`; do not add a README or other files if you will upload this folder as-is.
2. Upload the **contents** of `github_pages_site/` to the repository root (the repository root must contain `index.html` and `.nojekyll`). Alternatively, from a local clone, copy these files into its root, commit, and push using your normal Git workflow.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**. Choose the `main` branch and `/ (root)` folder, then save.
5. Wait for GitHub Pages to finish its first deployment. The shareable URL will follow this form:

   `https://GITHUB_USERNAME.github.io/REPOSITORY_NAME/`

Replace both placeholders with your GitHub username and repository name. For a repository named `GITHUB_USERNAME.github.io`, the site is normally served at the domain root.

All five bundled movies are H.264 MP4 files and below GitHub's 100 MB per-file limit. No Git LFS dependency is used. The site uses relative paths and has no external CDN requirement.
