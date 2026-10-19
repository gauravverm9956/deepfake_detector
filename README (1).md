# Veridex – Deepfake Detection Prototype

## Run locally
Open `index.html` in a modern browser (Chrome, Edge, Firefox, or Safari). The page uses browser APIs for media decoding and local history.

## Publish with GitHub Pages
1. Create or open a GitHub repository.
2. Upload `index.html` to the repository's **root** (top level), not inside another folder.
3. Commit the file to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose branch `main` and folder `/(root)`, then click **Save**.
7. Wait for the Pages deployment to finish. The website URL will be:
   `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/`
   Replace the placeholders with your actual GitHub username and repository name.

## Important limitation
This is a heuristic prototype, not a trained deepfake detector. Scores are estimates and must not be treated as proof that media is authentic or fake. It analyzes files locally in the browser; history is stored in that browser's local storage.
