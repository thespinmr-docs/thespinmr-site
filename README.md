# thespinMR Studio — site vitrine

Site statique (HTML + Tailwind CSS via CDN), prêt pour GitHub Pages, en 5 langues :

| Page | Langue |
|---|---|
| `index.html` | Français (langue par défaut, redirige une fois vers la langue du navigateur si EN/ES/DE/IT) |
| `en/index.html` | English |
| `es/index.html` | Español |
| `de/index.html` | Deutsch |
| `it/index.html` | Italiano |

## À renseigner avant la mise en ligne
1. Dans **chacune des 5 pages** `index.html`, bloc `const SITE = { ... }` en bas de fichier : lien de téléchargement, page d'achat, e-mail de contact, e-mail devis (mêmes valeurs partout).
2. `mentions-legales.html` : remplacer chaque zone `[À COMPLÉTER]`, puis supprimer l'encadré jaune d'introduction. Cette page reste en français (elle est liée depuis toutes les langues).

## Structure
- `index.html`, `en/`, `es/`, `de/`, `it/` : les pages d'accueil par langue
- `mentions-legales.html`, `404.html`
- `assets/img` : logo, icônes, images du fantôme (générées par le logiciel)
- `assets/fonts` : police Inter hébergée localement
- `assets/video` : vidéo de démonstration (partagée par toutes les langues)
- `.nojekyll` : demande à GitHub Pages de servir les fichiers tels quels

## Si l'adresse du site change (domaine personnalisé)
Remplacer `https://thespinmr-docs.github.io/thespinmr-site/` dans les balises `hreflang` des 5 pages et dans `404.html`.
