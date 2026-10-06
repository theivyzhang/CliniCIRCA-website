# CliniCIRCA project page

Project page for **CliniCIRCA: A Modular LLM Framework for Constructing Longitudinal Mental Health Patient Journeys from Raw EHR Narratives** (Calendar-anchored, Imprecision-aware Reconstruction of Clinical Annals).

Live site: https://theivyzhang.github.io/CliniCIRCA-website/
Code: https://github.com/theivyzhang/CliniCIRCA

## Structure

- `index.html` — the whole page (inline CSS and JS, no build step)
- `static/images/CliniCIRCA_images/` — logo, method overview (Fig. 1), example pipeline output (Fig. 2)
- `static/images/affiliations/` — institution logos
- `.nojekyll` — serve files as-is on GitHub Pages

Chart data for the interactive results (Tables 1 and 4 of the paper) lives in the `MODELS`, `METRICS`, and `TASKS` arrays in the `<script>` block at the bottom of `index.html`.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `main`, then enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

Website template adapted from [Nerfies](https://nerfies.github.io/) and the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template).
