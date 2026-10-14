# OWB Podcast Studio

Ready for GitHub Pages. Includes the updated Flint guide (10 questions), episode planning, browser-local saving, editable guides, Word export, and PDF printing. No installation, build step, server, or API key is required. AI title suggestions are not enabled.

## Publish in a few minutes

1. Extract this ZIP on your computer.
2. On GitHub, create a new public repository named `owb-podcast-studio`.
3. Choose **uploading an existing file** (or **Add file > Upload files**). Upload the extracted files themselves, not the ZIP or the enclosing folder. `index.html` must be at the repository's top level. Commit the files to `main`.
4. Open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/(root)**. Click **Save**.
5. Wait for deployment. The Pages settings will show the website link, usually `https://YOUR-USERNAME.github.io/owb-podcast-studio/`.

Official directions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Moving existing episode drafts

On your original Podcast Studio, click **Export backup**. On the new GitHub-hosted site, click **Import backup** and select that JSON file. Do not upload your personal backup to the GitHub repository. Drafts are saved per browser and website address, so they do not transfer automatically. The updated Flint example is already included in this packet.

## Access and storage

This public GitHub Pages setup makes the app and its included Flint example publicly accessible. It does not carry over the original site's private sign-in protection. Episodes you create remain in your browser's local storage; they are not uploaded to GitHub. Export backups periodically, because clearing browser data removes local drafts. The backup includes your private host notes; guest-facing Word and PDF exports exclude them.

## Files

- index.html — app interface
- style.css — interface and OWB print layout
- engine.js — guide patterns and updated Flint example
- app.js — editing and browser storage
- export.js — editable Word export
- .nojekyll — serves the site as static files

All app paths are relative, so repository-based GitHub Pages URLs work. The interface optionally loads Google Fonts; system fonts provide fallbacks.

To update the app later, replace the changed files in the repository and commit. GitHub Pages redeploys automatically.
