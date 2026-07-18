Reveal.js version of the presentation

How to view locally:

1. From the workspace root, run a simple HTTP server (so images load correctly):

```bash
python3 -m http.server 8000
```

2. Open the presentation in your host browser:

```bash
$BROWSER http://127.0.0.1:8000/index.html
```

Notes:
- The deck uses Reveal.js from CDN and KaTeX for math. No extra install required.
- Slides reuse images from `images/` in the repository; if any images are missing, replace or adjust paths in `index.html`.
