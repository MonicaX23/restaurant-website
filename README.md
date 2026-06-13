Olivetta — Seasonal Mediterranean Kitchen (static website)

OVERVIEW
A five-page static restaurant website, redesigned with a distinct visual
identity: an olive-green-led palette with terracotta and saffron accents on a
warm limewash background, Fraunces (display) paired with DM Sans (body), and a
printed-menu treatment with dotted leader lines as the signature element.

FILES
- index.html ............ Home: hero, featured plates, values band, booking CTA
- menu.html ............. Menu: printed-menu board with dotted leaders
- reservations.html ..... Reservation enquiry form (+ "good to know" panel)
- about.html ............ Story and values
- contact.html .......... Hours, details, contact form, location map
- css/style.css ......... Full design system (colour, type, layout, motion)
- js/app.js ............. Mobile nav, scroll reveal, header shadow, form handling
- images/ ............... Cohesive SVG illustrations (dishes, interior, map, sprig)
- evidence_screenshots/ . Folder for your own testing screenshots


NOTE ON FONTS
The display/body fonts load from Google Fonts via a <link> in each page's head,
so an internet connection shows the intended typography. A system serif/sans
fallback is defined, so the site still looks correct offline.

RUN LOCALLY
1. Open a terminal in this folder.
2. Run: python -m http.server 8000
3. Open http://localhost:8000 in your browser.

DEPLOY (GitHub Pages)
Upload the full folder to a GitHub repository, then enable GitHub Pages from the
repository settings using the main branch as the publishing source.
