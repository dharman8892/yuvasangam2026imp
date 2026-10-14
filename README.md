# YUVA SANGAM Digital Cultural Welcome Website

## Folder structure
- `index.html` — complete responsive HTML, CSS and JavaScript
- `assets/ministry-education.jpeg` — supplied Ministry of Education logo
- `assets/ek-bharat-shreshtha-bharat.jpeg` — supplied Ek Bharat Shreshtha Bharat logo
- `assets/iim-sambalpur.jpeg` — supplied IIM Sambalpur logo
- `assets/iit-hamirpur.jpeg` — supplied image labelled National Institute of Technology Hamirpur
- `assets/gallery-fallback.svg` — local fallback illustration if a gallery image fails to load

## Important logo note
The Imperial College logo was not included among the uploaded images, so the page displays a clearly identified placeholder in its required fourth position. Replace it with the original logo file when available; do not stretch or redraw it. The fifth uploaded logo image reads **National Institute of Technology Hamirpur**, not IIM Himachal Pradesh. Confirm with the event organiser whether this is the intended fifth logo before the ceremony.

## Run locally
1. Keep `index.html` and the `assets` folder together.
2. Open `index.html` in a modern browser. For best results, use a local static server (for example, VS Code Live Server) rather than opening the file directly.
3. The login stores the visitor name in `sessionStorage` for the current browser tab session only. No account, password, email or phone number is collected.
4. The interactive map uses Leaflet and OpenStreetMap tiles. Internet access is required for the map tiles and Leaflet CDN.
5. Gallery images are linked from Wikimedia Commons and require internet access. If a link fails, a local sample illustration is shown instead.

## Event display checklist
- [ ] Replace the Imperial College placeholder with the original logo.
- [ ] Confirm the intended fifth logo; supplied image is NIT Hamirpur.
- [ ] Have a knowledgeable speaker verify the Kangri/Mandeali greeting; it is deliberately marked pending.
- [ ] Test the site and internet on the event computer and projector.
- [ ] Open the site, enter a test name, check the personalized greeting, and reload within the same tab to verify session persistence.
- [ ] Check map markers, popups, gallery images and mobile layout.
- [ ] Use full-screen browser mode for the ceremony and keep a local copy of the project folder.
