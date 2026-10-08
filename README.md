# 684 Oakcrossing Road · 小镇漫游

A static interactive 3D neighborhood site. The main house is centered for navigation; surrounding homes are white architectural models. The two walkers and tabby cat can roam the neighborhood.

GitHub Pages deployment is handled by `.github/workflows/pages.yml` and publishes the `site/` directory on pushes to `main`.

The site uses Three.js from its CDN, so browsers need an internet connection. The detailed house and neighborhood data are also included in the HTML; `site/house-skp.glb` and `site/town-layout.json` are source assets.
