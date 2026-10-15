# Hydrangea House

A responsive, one-page static website for Hydrangea House. No installation or build step is required.

## Publish with GitHub Pages

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose the **main** branch and **/ (root)** folder.
4. Click **Save** and wait for the Pages deployment to finish.
5. Open the published URL shown in Pages settings. The default project URL is https://edgardonjuan.github.io/hydrangea-house/.

GitHub Pages branch publishing supports the repository root or a `docs` folder. This repository keeps `index.html` at the root so it can be published directly. The empty `.nojekyll` file disables Jekyll processing.

[GitHub's Pages setup instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Files

- `index.html`: page content, links, and metadata.
- `styles.css`: responsive layout and colors.
- `assets/hydrangea-house-logo.jpg`: supplied logo.
- `assets/thoughtfully-arranged.png`: supplied blue flower drawing.
- `assets/beautiful-blooms.png`: supplied orange flower drawing.
- `assets/made-for-you.png`: supplied yellow flower drawing.
- `assets/instagram-reference.jpg`: original Instagram reference, retained for reference.

All CSS and image links are relative so they work under the GitHub Pages project path. Edit the root files and commit to `main` to update the site after Pages is enabled.

## Content notes

Instagram: [@_hydrangeahouse](https://www.instagram.com/_hydrangeahouse/). The HoneyBook URL in the supplied screenshot is truncated, so inquiry buttons lead to Instagram until the full booking URL is available.

Gallery images are stored unchanged in `assets/` and displayed in full with `object-fit: contain`.
