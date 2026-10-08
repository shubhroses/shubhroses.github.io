# shubhroses.github.io

Source for my personal site, <https://shubhroses.github.io>.

The site is one static file, `index.html`, with its styles inline. It has no build step, no scripts and makes no external requests. GitHub Pages serves the `master` branch as it is; the empty `.nojekyll` file tells Pages not to run Jekyll.

To preview it locally:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.
