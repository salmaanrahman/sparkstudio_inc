SPARKSTUDIO TECH SOLUTION — COMPLETE MULTI-PAGE WEBSITE

START
1. Extract this ZIP.
2. Open the extracted sparkstudio-final folder in VS Code.
3. Run index.html with VS Code Live Server (recommended).
4. Use the top-right four-square menu to navigate between pages.

PAGES
- index.html — landing page (hero, studio intro, motion reel, 13 services, featured case studies, process, stack and animated finale)
- about.html — studio story and values
- services.html — all 13 service descriptions
- case-studies.html — four project briefs with a sliding cover gallery and Behance links
- process.html — Think / Design / Develop workflow
- technologies.html — design and development toolkit

DESIGN / MOTION
The site uses the supplied ivory/bone (#EEEBE4), ink (#121212), orange (#FF5A1F), lilac (#B8A6FF) palette, General Sans and JetBrains Mono. The landing page includes a loader, responsive popover menu, Three.js hero object field, pointer interaction, scroll-driven ribbon, expanding reel card, service grid/index toggle, featured case slider and a scroll-assembled 3D finale. The site gracefully falls back to static styling if WebGL or Three.js is unavailable.

CASE STUDY COVER ART
The four local SVG files in assets/case-studies/ are designed placeholders in the same visual style. Behance blocks direct page retrieval from this environment, so the official project cover images could not be embedded automatically. To use your exact Behance covers, export/download each cover image from your own Behance project and replace the matching SVG path in case-studies.html and index.html with the new image filename. The Behance buttons already point to the exact project URLs you supplied.

CONTACT
The email shown in the footer is a placeholder: hello@sparkstudio.example. Replace it with the studio's official email before publishing. Newsletter forms are front-end demos and need an email service endpoint to collect subscriptions.

TECHNOLOGIES
Three.js and Lenis load from their public CDNs; the font files load from Fontshare and Google Fonts. An internet connection is required for these external libraries and fonts.
