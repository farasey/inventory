# Retro Inventory (GitHub Pages)

Single-file web app that reads your **Google Sheets (Publish to web → CSV)** and renders a retro "terminal" inventory.

## Deploy on GitHub Pages
1. Create a new **public** repository, e.g. `inventory`.
2. Upload `index.html` to the root of that repo.
3. Go to **Settings → Pages**, choose **Deploy from branch**, branch `main`, folder `/ (root)`.
4. Your site will be live at: `https://YOURNAME.github.io/inventory/` (takes ~30–60 seconds).

## Embed on your site
```html
<iframe src="https://YOURNAME.github.io/inventory/" style="width:100%;height:80vh;border:0" loading="lazy" title="Inventory"></iframe>
```

## Sheet URL
Hardcoded in the page:
https://docs.google.com/spreadsheets/d/e/2PACX-1vTOImwV6nqaSvxQx06Mu5b-gOBkFrvMENj9r3pd_ewznnPHjmRkkI4gGTNPaFxT3D8mZAUTeYcaIMhM/pub?gid=1851981689&output=csv

Generated: 2025-08-09T01:23:02.826801
