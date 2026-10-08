# 684 Oakcrossing Road · 小镇漫游

This repository is prepared for GitHub Pages. The website is in `site/`; the Actions workflow publishes it on each push to `main`.

## Publish

1. Create a GitHub repository and upload the contents of this folder, including `.github/workflows/pages.yml`.
2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. Push/commit the files to the `main` branch. Open **Actions** and wait for “Deploy to GitHub Pages” to succeed. GitHub will show the published URL in the deployment environment.

The page uses Three.js from its CDN, so visitors need an internet connection. The page loads the detailed courtyard house from `site/house-skp.glb` and the neighborhood layout from `site/town-layout.json`. GitHub Actions rebuilds the complete GLB from the verified binary parts in `site/` before publishing. Keep the workflow and all `house-skp.part-*.bin` files when deploying.

GitHub Pages sites are publicly reachable, including when Pages is enabled for a private repository. Review the address and house layout before publishing.
