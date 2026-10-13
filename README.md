# APPLSX2.github.io

The landing page for APPLSX2, a PlayStation 2 emulator for iPhone and iPad: https://applsx2.github.io

- `index.html` is the landing page and `privacy.html` the privacy policy.
- `assets/` holds the stylesheet, the app icon in several sizes and the social preview image.
- The site is plain HTML and CSS, with no build step.

## Deploying

`.github/workflows/deploy.yml` publishes the site to GitHub Pages on every push to `main`. You can also run it by hand from the Actions tab.

It needs a one-time setting: Settings › Pages › Build and deployment › Source: **GitHub Actions**.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
