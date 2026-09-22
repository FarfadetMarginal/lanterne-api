# Lanterne API

Lanterne est une API REST Express qui référence des curiosités locales : lieux discrets, détails architecturaux et petites histoires de quartier.

## Pré-requis

- Node.js 20 ou supérieur
- pnpm 11 ou npm compatible

## Installation et lancement local

```text
pnpm install
pnpm run check
pnpm test
pnpm start
```

L’API est disponible sur `https://lanterne-api.vercel.app`.

## Routes principales

- `GET /health`
- `GET /curiosities`
- `GET /curiosities?q=canal&limit=5`
- `GET /curiosities/:slug`

Le déploiement cible Vercel. Les variables d’environnement sont listées dans `.env.example`. Aucune donnée sensible ne doit être ajoutée au dépôt.

## Liens
GitHub : https://github.com/FarfadetMarginal/lanterne-api
URL publique : https://lanterne-api.vercel.app