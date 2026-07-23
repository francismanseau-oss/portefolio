# Portefolio — Francis Manseau

Site portfolio professionnel orienté recrutement (mobile, carrousel projets, thème jour/nuit).

## Identité visuelle

Symbole **Maillage Modular** — fichiers dans `assets/brand/` (SVG) ; PNG favicon/nav via `generate-brand-assets.bat` ou `python scripts/generate-brand-assets.py`. Voir `assets/brand/CONCEPT.md`.

## Première installation

Double-clic ou exécution :

```
C:\Projets\portefolio\setup-init.bat
```

Ce script copie la base depuis `weidlerstudio.github.io` si nécessaire.

## Structure (portfolio recruteur)

| Section | Fichier |
|---------|---------|
| **Accueil** | `index.html` — photo, présentation, CTA projets |
| **Projets** | `projects/index.html` — carrousel + fiches détaillées |
| **Compétences** | `competences/index.html` — conception, direction de projets IA, architecture fonctionnelle, validation |
| **Contact** | `contact/index.html` — courriel uniquement |

Navigation centralisée dans `js/site-nav.js`.

Sections retirées (redirection vers l'accueil) : Services, À propos, Soumission.

## Contact

Courriel : `francismanseau@videotron.ca`

Emplacements prévus pour GitHub / LinkedIn : commentaires HTML dans `contact/index.html`.

## Modifier les projets

Liste dans `projects/index.html` (tableau `projects` en bas de fichier).
