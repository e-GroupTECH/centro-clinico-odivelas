# Centro Clínico de Odivelas — Redesign Concept

A modern, conversion-focused redesign concept for [centroclinicoodivelas.pt](https://centroclinicoodivelas.pt/), built as a prospecting/pitch demo.

Uses the clinic's real branding (logo, team photo, service icons, insurance/partner logos) pulled from the live site, restyled into a faster, more polished single-page experience.

## What changed vs. the current site

- Sticky header with click-to-call and a persistent booking CTA
- Hero with the clinic's real team photo, headline and trust stats (45 years, 500+ patients)
- Insurance/partner trust strip (AdvanceCare, Medicare, ADSE, Cheque Dentista)
- "A Clínica" section highlighting the 45-year legacy and central location near Metro Odivelas
- A dedicated callout for the same-day denture repair service — a real differentiator on the live site that had no visual presence
- Services grid for all 9 specialties, using the clinic's own icon set
- "Porquê Escolher-nos" feature band
- Testimonials section
- Contact section with hours, address, phone lines and a booking form
- Fully responsive (mobile nav drawer, fluid grids), fast-loading static HTML/CSS/JS — no build step required

## Structure

```
index.html            Single-page site
assets/css/style.css   All styles (CSS variables for easy re-theming)
assets/js/script.js    Mobile nav, scroll reveal, sticky header, demo form
assets/images/         Logo, team photo, service icons, insurance/partner logos
```

## Running locally

Any static file server works, e.g.:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/`.

## Notes

- The appointment form is a front-end demo only (no backend wired up yet) — ready to connect to a real booking/lead-capture endpoint.
- Testimonials are placeholders in the same spirit as a real dental practice; swap in real, sourced reviews before shipping.
