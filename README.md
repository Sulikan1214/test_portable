
# Réussir son Entretien d'Embauche — Desktop identique, Mobile adapté

Ce dossier garde **à l’identique le rendu Desktop** (PC) de votre atelier,
et ajoute un fichier **`mobile.css`** chargé *uniquement* sur les petits écrans
(`media="(max-width: 899.98px)"`).

## Fichiers
- `index.html` — Votre fichier d’origine **conservé** (avec l’ajout d’un bouton “Plein écran”).
- `mobile.css` — Petites surcouches **uniquement mobile** (pile verticale, nav collante, etc.).
- `images/` — Placez vos images (logo, etc.) ici.

## Déploiement GitHub Pages
1. Poussez ces fichiers sur la branche `main` de votre dépôt.
2. *Settings → Pages → Deploy from a branch* : choisissez `main` et `/ (root)`.
3. Attendez le build, votre site sera en ligne.

> **Note** : le bouton “⛶ Plein écran” ne modifie pas la mise en page ; il demande seulement au navigateur d’afficher la page en plein écran.
