# EcomHub

Landing page for **EcomHub**, an e-commerce platform for online businesses.

## Project structure

```
.
├── index.html     # Main page (HTML with inline CSS)
├── external.html  # Shown for links to pages that weren't downloaded
├── backblue.gif   # Background image for the content area
├── fade.gif       # Background tile for table cells
└── README.md
```

## Viewing locally

The site is static HTML with no build step. Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Site content

The EcomHub link in `index.html` points to `www.ecomhubtheme.com/index.html`, a folder that sits next to `index.html`. That folder isn't in the repo yet, so the link returns "not found" until it's added.

## Publishing with GitHub Pages

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Select the branch and the `/ (root)` folder, then save.

GitHub shows the published URL on that settings page once the first deploy finishes.

## License

© 2024 EcomHub Platform. All rights reserved.
