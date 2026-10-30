# thechaifactor.com

Static export of Cheryl Chai's portfolio, moved off Webflow.

- `index.html`, `about/`, `work/<project>/` — one folder per page, so URLs stay the same as on Webflow.
- `assets/css/site.css` — the original Webflow stylesheet.
- `assets/js/` — Webflow's runtime (mobile menu + scroll animations) and jQuery.
- `assets/images/` — all images, with smaller `-p-<width>` copies for faster loading.

No build step: any static host (Cloudflare Pages, GitHub Pages, Netlify) can serve the repo root as-is.
