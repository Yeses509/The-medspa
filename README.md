# The MedSpa by RayRay — Website Deployment Package (EN/ES)

## Contents
- `index.html` — the complete bilingual (English/Spanish) website
- `images/` — all photos and videos (58 files), referenced by relative paths

Every single file is under 25MB for easy uploading.

## Deploy via GitHub → Hostinger
1. On GitHub, create a new repository (e.g. `rayray-medspa-website`).
2. Upload `index.html` AND the `images` folder to the repository root
   (drag & drop on github.com — you can drag the whole folder; then Commit).
   Keep the structure: `index.html` next to the `images/` folder.
3. In Hostinger hPanel: Websites → Git → connect the repository, branch `main`,
   install path `public_html` (or your domain's folder).
4. Deploy. The site is served from `index.html`.

## Notes
- Bilingual EN/ES with navbar language switcher (default English).
- The booking flow is an on-page 5-step request wizard (incl. consent + signature)
  ending in SMS/WhatsApp/Email handoffs (no backend).
- Business: The MedSpa by RayRay, 6200 Chase Oaks Blvd #101, Plano, TX 75023 ·
  (682) 521-6752 · rayraybeauty6@gmail.com
