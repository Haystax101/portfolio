# george hastings — personal site

Plain HTML + CSS, no build step. Edit `index.html`, push to `main`, GitHub Pages redeploys.

Placeholders to fill are in square brackets: search the file for `[`.

## Custom domain

1. Add a file named `CNAME` at the repo root containing just the domain (e.g. `georgehastings.me`).
2. At the registrar, add DNS records:
   - `A` records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` record for `www` → `haystax101.github.io`
3. Repo → Settings → Pages → Custom domain → enter the domain, wait for the DNS check, tick "Enforce HTTPS".
