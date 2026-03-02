# haimantika.github.io
Portfolio of myself, that includes my social media links, talks, and other information.

## Run locally

1. **Install [Hugo](https://gohugo.io/installation/)** (extended version recommended).

2. From the repo root, start the dev server (content lives in the theme):

   ```bash
   hugo server --contentDir themes/charlolamode/content
   ```

3. Open **http://localhost:1313** in your browser. The site reloads when you change content, layouts, or config.

## Deploy to production (GitHub Pages)

**Do not run the server before pushing.** Use the build command only so that `docs/` is generated with the correct production URLs (no localhost).

1. From the repo root, build the site (no `hugo server`):

   ```bash
   hugo --contentDir themes/charlolamode/content
   ```

2. Commit and push the updated `docs/` folder. GitHub Pages will serve the site from `docs/`.

To preview locally, use `hugo server ...` as above; that does not update the committed `docs/` and is only for local viewing.
