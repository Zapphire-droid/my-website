# Infinitum — Your Private Archive

📝 My personal digital journal space. Just a 1st-year student building cool things on the internet, tracking ideas, and experimenting with web design. Powered by coffee and AI. ☕✨

This repository contains a single-page HTML app (index.html) — a beautiful, local-first journaling UI with themes, a doodle canvas, an audio ambiance player, and a 3D "reader" overlay.

Quick links

- Demo: (you can enable GitHub Pages for this repository and it will serve the root `index.html`)
- File: `index.html`

Quick start (local)

1. Clone the repo:

   git clone https://github.com/Zapphire-droid/my-website.git
   cd my-website

2. Open locally in your browser:

   - Option A (double-click): open `index.html` in your browser.
   - Option B (simple HTTP server):
     - Python 3: `python -m http.server 8000` then visit `http://localhost:8000`
     - Node (http-server): `npx http-server . -p 8000`

What I added in this commit

- A friendly README to explain the project and how to run it locally.
- A simple GitHub Actions workflow (pages deploy) so you can enable Pages and get a live demo.
- An MIT license file.

Recommended next improvements (I can implement any of these for you):

- Add a short, focused `<meta name="description">` and Open Graph/Twitter meta tags to `index.html` for better social previews and SEO.
- Move styles and scripts into separate `assets/css/` and `assets/js/` files to improve maintainability and enable bundling/minification.
- Add accessibility improvements (skip links, proper ARIA roles where needed, and run axe/lighthouse audits).
- Convert the site to a static-site-generator (Eleventy/Hugo) if you plan to publish posts.
- Add image optimization, responsive `srcset` images, and lazy-loading for better performance.
- Add an automated Lighthouse CI check in GitHub Actions.

If you want, tell me which of the items above to apply next and I will create the files and open a PR (or push directly) with the changes.