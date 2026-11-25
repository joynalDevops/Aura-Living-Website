# Aura Living LLC website

A local static website for Aura Living LLC, a Virginia residential and commercial property management company. This project uses Astro, plain CSS, and local SVG artwork. It has no backend and makes no runtime API calls.

## Run locally in Windows PowerShell

From the project directory:

```powershell
npm install
npm run dev
```

Open the local URL printed by Astro, usually `http://localhost:4321`.

Build the static site:

```powershell
npm run build
```

Preview the production build locally:

```powershell
npm run preview
```

## Notes

- The contact form is intentionally local-only. It prevents submission and shows local confirmation feedback.
- Official contact details are `info@auralivingva.com`, `+1 703-828-4040`, and `Woodbridge, Virginia, USA`.
- No secrets, backend, production form handling, SMS activation, DNS configuration, hosting configuration, or domain deployment is included.
- `public/robots.txt` and `public/sitemap.xml` provide a basic static setup for `https://auralivingva.com/`.
