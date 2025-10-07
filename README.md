# Aarav Sharma — Portfolio (GitHub Pages)

This is a single‑page personal website you can host **for free** via GitHub Pages.

## Quick start

1. Create a new public repo named `aaravsharma1.github.io` (or any repo; for user sites, use `username.github.io`).
2. Download `site.zip`, unzip it, and copy all files into the repo.
3. Commit & push.
4. If not using the `username.github.io` pattern, enable Pages:
   - Settings → Pages → Deploy from branch → `main` / `/root`.
5. Visit your site at `https://<username>.github.io/` or the repo’s Pages URL.

## Update your resume

Replace `assets/resume.pdf` with your latest PDF. The header and footer links update automatically.

## Add work samples (PDFs)

1. Drop your PDFs into `assets/work-samples/`.
2. Edit `assets/work-samples.json` to list each sample:
   ```json
   [
     {
       "title": "My Project — One‑Pager",
       "description": "What the PDF covers.",
       "file": "assets/work-samples/my-project.pdf",
       "tags": ["tag1","tag2"]
     }
   ]
   ```

## Customize

- Edit `index.html` to change sections.
- `assets/site.css` holds a couple of print/smooth‑scroll tweaks.
- Tailwind is included via CDN for convenience.

## Local preview

Just open `index.html` in a browser. No build step required.
