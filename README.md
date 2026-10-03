# EcomHub

Landing page for **EcomHub**, an e-commerce platform for online businesses.

## Project structure

```
.
├── index.html   # Main page (HTML with inline CSS)
└── README.md
```

## Viewing locally

The site is static HTML with no build step. Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Assets

`index.html` references two background images that need to sit next to it in the repo root:

- `backblue.gif`: background for the main content area
- `fade.gif`: background for table cells

The page still renders without them; only the background images are missing.

## Publishing with GitHub Pages

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Select the branch and the `/ (root)` folder, then save.

GitHub shows the published URL on that settings page once the first deploy finishes.

## License

© 2024 EcomHub Platform. All rights reserved.
