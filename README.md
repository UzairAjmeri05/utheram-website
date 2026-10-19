# Utheram LLC — company website

Single static page for utheram.com. No framework, no build step.
Exists so Apple can verify the legal entity (Individual → Organization
developer account migration), so it stays minimal and professional.

## Files

- `index.html` — the whole site. Edit the two `<!-- EDIT ME -->` spots
  (contact email, business address) directly in the file.
- `vercel.json` — security headers and clean URLs. No changes needed.

## Preview locally

Double-click `index.html`, or from this folder run:

```
npx serve .
```

## Deploy

Vercel project: connected to this repo, root directory = repo root,
framework preset = **Other**, no build command, no output directory.
Every push to `main` deploys automatically.

Domain: `utheram.com` (Namecheap DNS, A + CNAME records pointing at
Vercel). `www.utheram.com` redirects to the apex.
