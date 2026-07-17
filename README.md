# BetterHealth Hallmark Website

Static BetterHealth website deployed from `index.html`.

## Run locally

Open `index.html` directly in a browser, or run a local static server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

The repository includes a GitHub Pages workflow and a `gh-pages` branch.

For the one-time repository setting, open **Settings → Pages** and choose either:

- **Source: GitHub Actions**, using `.github/workflows/deploy-pages.yml`; or
- **Deploy from a branch → `gh-pages` → `/ (root)`**.

The expected public address is:

`https://hendrivi.github.io/BetterHealth-hallmark-website/`

## Contact form

The current consultation form is a front-end demonstration. It changes the button text after submission but does not transmit or store enquiries. Connect it to a secure form service or backend before accepting real messages.
