# 'Ori Tahiti Tāne Montréal

Site vitrine statique en HTML, prêt pour GitHub Pages.

## Fichiers
- `index.html` : page du site
- `assets/logo.png` : logo fourni
- `assets/photo_nous_2.png` : photo des deux danseurs

## Tester en local
Ouvrir `index.html` dans un navigateur. Le site charge Tailwind CSS, Google Fonts et Font Awesome depuis leurs CDN : une connexion Internet est nécessaire pour ces éléments.

## Publier avec GitHub Pages
1. Créer un dépôt GitHub (par exemple `ori-tahiti-tane-montreal`).
2. Téléverser le contenu de ce dossier à la racine du dépôt : `index.html`, `assets/`, `.nojekyll` et `README.md`.
3. Dans le dépôt, ouvrir **Settings → Pages**.
4. Sous **Build and deployment**, choisir **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`, puis **Save**.
5. Attendre la fin du déploiement. GitHub affichera l'adresse publique dans **Settings → Pages**.

## À vérifier avant diffusion
- Le formulaire d'inscription actuel valide les champs et affiche une confirmation dans le navigateur, mais n'envoie pas encore les renseignements par courriel ni vers une base de données.
- La zone administrateur et son code PIN sont gérés côté navigateur (`localStorage`) : ce n'est pas une protection sécurisée et les photos/tarifs ajoutés ne sont pas partagés entre les appareils. Ne pas y stocker d'informations sensibles.
- Le code PIN initial affiché dans la page est `1234` ; il ne faut pas considérer ce mécanisme comme une authentification réelle.
