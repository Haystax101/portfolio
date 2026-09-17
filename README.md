# george hastings — personal site

Plain HTML + CSS, no build step. Edit `index.html`, push to `main`, GitHub Pages redeploys.

Placeholders to fill are in square brackets: search the file for `[`.

## Custom domain

1. Add a file named `CNAME` at the repo root containing just the domain (`georgehastings.me`, already added).
2. At the registrar, add DNS records:
   - `A` records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` record for `www` → `georgeh1066.github.io`
3. Domain is attached to this repo already; tick "Enforce HTTPS" under Settings → Pages once the certificate is issued.
