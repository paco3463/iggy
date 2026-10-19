# Healthy Solutions for Children and Families — hscfdoral.com

Bilingual (English / Spanish) website for a psychology practice in Doral, FL.
Plain HTML, CSS and JavaScript. No build step and no frameworks: upload the files and it works.

## Publish on GitHub Pages

1. Create a repository and upload **everything in this folder** (keep the folder structure).
2. Go to *Settings → Pages → Build and deployment → Deploy from a branch*, choose `main` and `/ (root)`, and save.
3. The `CNAME` file is set to `hscfdoral.com`. Point the domain's DNS at GitHub Pages, or delete `CNAME` to use the free `username.github.io/repo` address.
4. Submit `https://hscfdoral.com/sitemap.xml` in Google Search Console.

## Pages (51)

- English: `index.html`, `about.html`, `services.html`, `team.html`, `areas.html`, `contact.html`
- English subpages: `services/` (8 services), `team/` (5 clinicians), `areas/` (6 cities)
- Spanish: the same pages under `es/` with Spanish URLs (`es/servicios/terapia-infantil.html`, etc.)
- `404.html`, used automatically by GitHub Pages

Every page links to its twin in the other language through the language button in the header.

## Before launch

- **Contact form:** create a free form at formspree.io and replace `YOUR_FORM_ID` in `contact.html` and `es/contacto.html`. Until then the form opens the visitor's email app.
- **Sample content:** the 5 clinicians, office hours and insurance wording are samples to replace.
- **Photos:** the team portraits and lifestyle photos load from OpenArt's image server. To host them yourself, save each image into `assets/img/` and update the `src`/`srcset` links.
- **Workshop popup:** "Hablemos sobre Ansiedad" (Sat Oct 24, 2026) removes itself automatically after the event ends.

## Files

| Path | Purpose |
|---|---|
| `assets/css/styles.css` | All styles. Every color is defined once at the top as a token. |
| `assets/js/main.js` | Splash screen, hero video controls, finder, breathing exercise, team filter, workshop popup, contact form |
| `assets/media/` | Hero video loop (1080p for desktop, 720p for phones) and its first-frame poster |
| `assets/fonts/` | Fraunces and Figtree, self-hosted (SIL Open Font License) |
| `assets/img/` | Logo, icons, workshop flyer, social share images |
| `sitemap.xml`, `robots.txt`, `site.webmanifest` | Search and app metadata |

If someone is in crisis: call or text 988, or call 911. This website is informational and not an emergency service.
