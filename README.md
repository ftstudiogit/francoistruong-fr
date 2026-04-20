# francoistruong.fr

Site vitrine de **FT Studio** — Conseil IA par François Truong.

Site statique une page, à servir tel quel depuis n'importe quel hébergement HTTP (GitHub Pages, Netlify, Cloudflare Pages, OVH, etc.).

## Structure

- `index.html` — la page (HTML + CSS inline, aucune dépendance de build)
- Fonts Google : Libre Baskerville + DM Sans (chargées via CDN)

## Développement local

```bash
python3 -m http.server 8000
# puis ouvrir http://127.0.0.1:8000
```

## Déploiement

Ce dépôt est publié via **GitHub Pages** avec le domaine custom `francoistruong.fr`.
Le fichier `CNAME` pointe vers ce domaine ; la config DNS se fait chez OVH.
