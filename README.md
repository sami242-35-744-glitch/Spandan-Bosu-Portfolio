# Spandhan Basu · Academic Portfolio

A one-page academic portfolio: introduction, education timeline, technical skills, and a folder-style browser for research and project collections. It is plain HTML, CSS and JavaScript in a single file. There is no build step and nothing to install. The only outside resource is Google Fonts.

## Run it locally

Open `index.html` in any browser.

## Publish it with GitHub Pages

1. Create a new repository, for example `spandhan-portfolio`, and upload `index.html` and `README.md` to the root of the repository.
2. Open the repository, then **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, and press **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Change the content

- Name, headline, introduction, skill chips, email, social links and the folders under "Research & project collections" are stored as JSON in the `<script type="application/json" id="state">` block, after the page markup. Edit the values there.
- The education timeline, skill levels, languages and the courses list are plain HTML inside the `<template id="shell">` block.
- Social links go in the `links` array as `{"label": "LinkedIn", "url": "https://..."}`.

## Notes

- The in-page "Owner login" editor only works on the claude.ai-hosted version of this page, so the link is hidden in this copy. Edit the file directly instead.
- Certificate and project files uploaded through that editor are stored on claude.ai and are not part of this repository.
