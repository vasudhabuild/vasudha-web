# vasudha-web

Official website for [vasudha.build](https://vasudha.build) — the VASUDHA Regenerative Built Environment Certification Framework.

## About VASUDHA

VASUDHA is a Global South certification framework for regenerative built environments, rooted in civilisational knowledge rather than Western industrial baselines. A counter-standard to LEED and GRIHA, built from the ground up.

**Six-Tag Taxonomy:** Vastu · Agro-climatic · Āyurvedic · Ecological · Hydrological · Ethnoscientific  
**Fourteen Certification Domains**  
**Pilot Project:** Dharma Spaces, Varanasi (Exhibit A)

## Stack

Pure HTML + CSS — no build step, no dependencies, no framework.  
Fonts loaded via Google Fonts (Libre Baskerville + DM Sans).

## Structure

```
vasudha-web/
├── index.html        # Main page
├── src/
│   └── style.css     # All styles
├── public/           # Static assets (favicon, og image, etc.)
└── README.md
```

## Local Development

```bash
# Any static server works — e.g.
npx serve .

# Or simply open index.html in a browser
```

## Deployment

Deployed via [DigitalOcean App Platform](https://cloud.digitalocean.com) as a static site.

- **Branch:** `main`
- **Build command:** _(none — static site)_
- **Output directory:** `/` (root)

DigitalOcean auto-deploys on every push to `main`.

## Custom Domain

Point `vasudha.build` to DigitalOcean App Platform via CNAME or A record as instructed in the DO dashboard.

## Roadmap

- [ ] Favicon + OG image
- [ ] Framework detail pages (per domain)
- [ ] Pilot project case study (Dharma Spaces)
- [ ] Certification application portal (Phase 2)
- [ ] VASUDHA standards documentation (public)

---

© VASUDHA · vasudha.build
