# thespinMR Studio — site vitrine

Page d'accueil statique (HTML + Tailwind CSS via CDN), prête pour GitHub Pages.

## À renseigner avant la mise en ligne
1. `index.html`, bloc `const SITE = { ... }` en bas de fichier : lien de téléchargement, page d'achat, e-mail de contact, e-mail devis.
2. `mentions-legales.html` : remplacer chaque zone `[À COMPLÉTER]`, puis supprimer l'encadré jaune d'introduction.

## Structure
- `index.html` : la page d'accueil
- `mentions-legales.html`, `404.html`
- `assets/img` : logo, icônes, images du fantôme (générées par le logiciel)
- `assets/fonts` : police Inter hébergée localement (pas de requête vers Google Fonts)
- `.nojekyll` : demande à GitHub Pages de servir les fichiers tels quels
