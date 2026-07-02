GitHub Pages upload instructions

1. Upload these files to the root of your GitHub repository:
   - index.html
   - styles.css
   - app.js
   - .nojekyll

2. Do not upload the ZIP file itself to GitHub Pages. Extract it first.

3. In GitHub repository:
   Settings > Pages > Build and deployment > Source: Deploy from a branch
   Branch: main
   Folder: /root
   Save.

4. Wait 1-3 minutes, then open the Pages URL.

If GitHub shows "Timeout reached, aborting!" while deploy is running, retry the workflow after a few minutes. The generated site is static and small, so this is usually a GitHub Pages deployment-side timeout, not a code problem.
