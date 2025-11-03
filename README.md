# Blog and Sandboxes

This folder contains my blog posts and small interactive sandboxes/demos. The site is served as a static site (GitHub Pages). Below is a short guide to what's here and how to view it.

- `home.html` — the blog index (posts list).
- Individual post pages (e.g. `building-a-custom-html5-audio-player-with-javascript.html`, `binary-search-tree.html`, etc.).
- `cp/` — collection of codepen-style sandbox pages and small experiments.

How to view locally
- Open the files in a browser (double-click `home.html` or any post) to preview static HTML.
- For a closer match to GitHub Pages, serve the repository root with a simple local server (Python):

```bash
# from the repository root
python3 -m http.server 8000
# then open http://localhost:8000/blog/home.html
```

Notes
- Some internal links point to `/blog/home.html` to keep paths consistent when deployed.
- I keep images under `/img/` and CSS under `/css/` at the repository root — keep that structure when moving files.

Contact
- If you need changes or want me to tidy/normalize links or dates, open an issue or send me a message.

Enjoy exploring the demos and posts!
