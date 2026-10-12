# deep-robotics.us

Static company site for Deep Robotics, Inc. No build step: Vercel serves the files as they are.

- `index.html` — the whole page (markup, styles and a few lines of script)
- `img/` — hero image (WebP) and the logo mark and wordmark (SVG)
- `favicon.svg`, `robots.txt`
- `vercel.json` — clean URLs, long cache on images, basic security headers

Every push to `main` deploys to production once the repo is connected to the `deep-robotics` Vercel project.


Images are cached for a year, so a changed image must get a new file name.
