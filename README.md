# Aura Living website

A local website for Aura Living, a Virginia residential property management and resident support concept. This project uses Astro, plain CSS, and local SVG artwork. It has no backend and makes no runtime API calls.

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

## Notes before production

- The contact form is intentionally local-only. It prevents submission and shows local confirmation feedback.
- Final business contact information, service scope, legal copy, and any public claims must be reviewed before launch.
- The address and phone number are clearly marked placeholders. The contact email is `hello@auralivingva.com`.
- No EIN, secrets, backend, production form handling, SMS activation, DNS configuration, hosting configuration, or domain deployment is included.
- The Privacy Policy and SMS Terms are drafts for review, not legal advice.
- `public/robots.txt` and `public/sitemap.xml` provide a basic static setup for the intended domain.
