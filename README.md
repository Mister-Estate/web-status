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

1. **Branche `gh-pages`** : publiée par les workflows *Setup CI*, *Static Site CI* et *Deploy Status Page* (`peaceiris/actions-gh-pages`, CNAME `status.mister-estate.ai`).
2. **GitHub Pages** (une fois) : [Paramètres → Pages](https://github.com/Mister-Estate/web-status/settings/pages) → Source **Deploy from a branch** → branche **`gh-pages`** → dossier **`/ (root)`**.
3. **Permissions Actions** : *Settings → Actions → General* → *Workflow permissions* → **Read and write**.
4. **DNS** : enregistrement **CNAME** `status` → `mister-estate.github.io` (ou l’hôte Pages indiqué par GitHub).
5. **Déclencher un déploiement** : onglet [Actions](https://github.com/Mister-Estate/web-status/actions) → *Deploy Status Page* ou *Setup CI* → **Run workflow**.
6. Les workflows `Uptime CI` et `Response Time CI` alimentent ensuite `history/` et `api/` sur `master`.

## Personnalisation

Thème et identité visuelle : `assets/mister-estate-theme.css`, `assets/logo.svg`, `assets/favicon.svg`.

Palette alignée sur le site vitrine : navy `#14415A`, or `#C9A84C`, fond crème `#FAF6EE`, texte `#1D1D1D`.
