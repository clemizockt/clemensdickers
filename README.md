# Clemens Dickers — Portfolio

Interactive Product Experience Table — concept case study portfolio.

Single-file static site (`index.html`), all images embedded as base64.
Only external asset: `Clemens-Dickers-CV.pdf` (linked via the CV download button).

## Deploy via GitHub Pages

1. Push/upload all files in this folder to the repository root (or `/docs` if preferred — adjust Pages source setting accordingly).
2. Repo → Settings → Pages → Source: Deploy from a branch → `main` → `/ (root)`.
3. Save. Site goes live at `https://<username>.github.io/<repo>/` within a few minutes.

## Custom domain (optional)

To point a purchased domain (e.g. from Strato) at this GitHub Pages site:
1. Add a file named `CNAME` (no extension) to the repo root containing just the domain, e.g.:
   ```
   clemensdickers.de
   ```
2. At the domain registrar (Strato), set DNS records to point to GitHub Pages:
   - `A` records for the apex domain → GitHub Pages IPs (185.199.108.153, .109.153, .110.153, .111.153)
   - or a `CNAME` record for a `www` subdomain → `<username>.github.io`
3. In repo → Settings → Pages, enter the custom domain and enable "Enforce HTTPS" once DNS has propagated.
