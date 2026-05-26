# Mister Estate — Disponibilité des services

Page de disponibilité publique pour l'écosystème [Mister Estate](https://mister-estate.ai/), propulsée par [Upptime](https://upptime.js.org) et GitHub Actions.

## Services surveillés

| Service | URL |
| --- | --- |
| Site vitrine | https://mister-estate.ai/ |
| Application web | https://app.mister-estate.ai/ |
| Documentation | https://docs.mister-estate.ai/ |

## Page publique

- **URL** : https://status.mister-estate.ai/
- **Branche de déploiement** : `master`
- **Configuration** : `.upptimerc.yml`

## Déploiement

1. Activer **GitHub Pages** sur ce dépôt (source : branche `gh-pages`, générée par le workflow *Static Site CI*).
2. Ajouter un enregistrement DNS **CNAME** : `status.mister-estate.ai` → `mister-estate.github.io` (ou l'URL Pages du dépôt `Mister-Estate/web-status`).
3. Les workflows GitHub Actions (`Uptime CI`, `Response Time CI`, etc.) collectent automatiquement les métriques après chaque push sur `master`.

## Personnalisation

Thème et identité visuelle : `assets/mister-estate-theme.css`, `assets/logo.svg`, `assets/favicon.svg`.

Palette alignée sur le site vitrine : navy `#14415A`, or `#C9A84C`, fond crème `#FAF6EE`, texte `#1D1D1D`.
