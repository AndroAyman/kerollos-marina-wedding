# Kerollos & Marina — Wedding Invite

## Add your photos
Put files named `couple.jpg` (hero photo) and `1.jpg` through `6.jpg` (gallery) into the `photos/` folder. They'll show up automatically — no code changes needed.

## Set your WhatsApp number
Open `index.html`, find this line near the bottom (search for `TEMPORARY`):
```
var phone = '201000000000';
```
Replace it with your number, digits only, country code first, no `+` or spaces (e.g. Egypt number 01001234567 → `2010012345678`... i.e. `20` + the number without the leading 0).

## Publish on GitHub Pages
1. Go to https://github.com and create a new repository (e.g. `our-wedding`), public.
2. On the repo page, click **Add file → Upload files**, then drag in `index.html`, `README.md`, and the `photos` folder (with your photos inside).
3. Commit the changes.
4. Go to the repo's **Settings → Pages**.
5. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** (or **master**), folder **/ (root)**, then Save.
6. Wait ~1 minute, then your site will be live at:
   `https://<your-github-username>.github.io/<repo-name>/`

Any time you edit `index.html` or add photos, just re-upload/commit and the live site updates automatically within a minute or two.
