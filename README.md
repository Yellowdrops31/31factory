# 31FACTORY — Netlify package (v3, z obrazami)
Data: 2025-10-29

## Co jest
- index.html — strona główna z realnymi obrazami (zrzuty jako placeholdery), gotowe sekcje.
- contact.html — formularz.
- connect.html — "Integracja w toku" + ikony (nasze, czarno-białe) z linkami.
- styles.css — style.
- assets/ — obrazy i ikony (do podmiany na finalne).

## Deploy
1) app.netlify.com → Add → Drag&drop cały folder.
2) Domains → Add custom domain → www.31factory.pl.
3) OVH: CNAME dla `www` → twoja-nazwa.netlify.app.
4) HTTPS → Provision certificate.

## Podmiana grafik
- Hero: zamień `assets/strona1.png` na własne zdjęcie (zachowaj nazwę `hero.jpg` albo zmień ścieżkę w index.html).
- Podobnie `about.jpg`, `features.jpg`.
- Ikony w connect.html możesz zamienić na SVG/PNG portfeli (MetaMask, Phantom, itd.).
