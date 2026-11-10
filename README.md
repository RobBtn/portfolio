# Portfolio — Robin Baton

Un portrait à traverser plutôt qu'à lire : la page ne descend pas, la molette fait avancer une scène 3D.

## Structure

Le site tient dans un seul fichier, `index.html`. Il n'y a ni dépendance à installer ni étape de build.

Three.js et les polices sont chargés depuis un CDN, donc une connexion internet est nécessaire.

## Voir le site en local

Ouvrir `index.html` dans un navigateur.

## Déploiement sur Vercel

Importer le dépôt dans Vercel avec les réglages par défaut :

- Framework Preset : `Other`
- Build Command : vide
- Output Directory : vide (racine du dépôt)

Chaque `git push` sur `main` redéploie le site.
