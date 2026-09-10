# Muscu 6 semaines — GitHub Pages

Dossier prêt à être publié tel quel avec GitHub Pages.

## Publication

1. Créer un dépôt GitHub, par exemple `muscu-6-semaines`.
2. Copier **le contenu de ce dossier** à la racine du dépôt (pas le dossier lui-même dans un sous-dossier).
3. Dans GitHub : **Settings → Pages**.
4. Dans **Build and deployment**, choisir **Deploy from a branch**.
5. Choisir la branche `main` et le dossier `/ (root)`.
6. Enregistrer puis attendre la publication.

GitHub fournira une adresse HTTPS, typiquement :
`https://TONPSEUDO.github.io/muscu-6-semaines/`

## Installation sur Android

1. Ouvrir l'adresse HTTPS avec Chrome sur le Pixel 9.
2. Ouvrir le menu Chrome.
3. Choisir **Installer l'application** ou **Ajouter à l'écran d'accueil**.
4. L'appli peut ensuite être lancée comme une application autonome.

## Important

- `manifest.webmanifest` est déjà configuré.
- `sw.js` active le cache hors ligne.
- `.nojekyll` évite que GitHub Pages applique Jekyll aux fichiers statiques.
- Les données des séances sont stockées localement dans le navigateur (`localStorage`). Aucun compte n'est requis.
- Pour mettre à jour l'appli après une modification du code, augmenter la valeur `CACHE` dans `sw.js` (par exemple `muscu-6s-v2`).
