# westbound.app

The public website for Westbound, an iPhone app for Colorado's I-70 mountain corridor: home page, roadmap, privacy policy and support page. Plain HTML served by GitHub Pages at https://westbound.app.

- When the policy in `privacy/index.html` changes, update its "Effective" date.
- Fonts (Alfa Slab One, Zilla Slab, Work Sans, Space Mono; SIL Open Font License, texts in `assets/OFL-*.txt`) are self-hosted in `assets/` so pages make no third-party requests.
- `roadmap/index.html` is the public roadmap. It lives only here: update it here when a build ships.
- `CNAME` holds the custom domain. Don't delete it.
- The homepage's I-70 map is traced from the app's `Corridor/westbound_segments.json`. Its sticker art and screenshots are copies from the app repo.
- `robots.txt` and `sitemap.xml` are hand-written. Add any new page to `sitemap.xml`. When the app's price, availability or iOS version changes, update the homepage's "The basics" list and the JSON-LD block in its `<head>`.
