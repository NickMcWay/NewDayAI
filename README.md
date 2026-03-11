# NewDay GitHub Page

This folder contains a standalone static website for **NewDay**.

## Preview locally

```bash
cd newday-github-page
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Publish on GitHub Pages

Use one of these approaches:

1. **Branch root strategy**: push this folder's contents to a dedicated Pages branch root.
2. **/docs strategy**: copy these files into your repository `docs/` folder and set Pages source to `/docs`.
3. **GitHub Actions strategy**: deploy this folder as the artifact in a Pages workflow.
