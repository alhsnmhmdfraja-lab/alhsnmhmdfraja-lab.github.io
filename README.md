# Alhassan Mohammed Farraj — Data Analyst Portfolio V17

This version is a wide, dark, animated public portfolio with:
- AM brand mark and full navigation
- Real profile photo
- Nike dashboard used subtly as the hero background
- About, Skills, Projects, Education, Experience, Certificates and Contact sections
- Five project cards with the supplied dashboard images and direct GitHub repository links
- No Python or SQL presented as current project skills
- Working GitHub, LinkedIn, Gmail, phone and CV links

GitHub Pages: upload all files in this folder to the repository root and publish from `main` / root.

## V18 update
This version fixes the image MIME/path issue by storing the Nike dashboard as a real JPG, adds the original IBM SkillsBuild certificate image, includes a short loading screen, responsive mobile navigation, scroll reveal animations, direct GitHub/LinkedIn/Gmail/Phone/CV links, and separates Home/About/Skills/Projects/Education/Experience/Certificates/Contact into distinct sections.


## V19 asset fix
The public `index.html` is self-contained: the profile photo, five project dashboard images, hero dashboard, and IBM certificate are embedded directly in the HTML so they display even when the page is opened locally. The same image files are also kept in `assets/` for editing and reuse.


## V20 update
- Hero photo is now a circular crop of the supplied photo (assets/profile-photo.jpg); floating caption and hero dashboard background removed.
- AM logo fixed to sit horizontally (A M) in the header and loader.
- Subtle animated grid/orbital background (respects prefers-reduced-motion).
- Project cards: image, title, description, tools, link; hover lift, glow and image zoom; touch/focus supported.
- Education moved to its own section; certificate button reads 'Verify Certificate'.

## V24
- Removed extra rings behind the profile photo.
- Open CV: relative link kept, plus embedded-PDF fallback so it opens even if the PDF file is missing next to index.html.
- Background: smooth analytical curves with faint area fill and connected points.

## V25
- Card borders: a bright gradient arc now travels around each card edge (per-card speed/direction; speeds up on hover).
- Floating analytical shapes (two parallax layers) + particles traveling along the data curves.

## V26
- Decorative shapes and cards now physically float (translate+rotate, 8-18s, unique timing).

## V27
- Softened color intensity of the rectangular/square background decorative shapes (kpi/chart/table) only — darker, slightly desaturated. Nothing else changed.
