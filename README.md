# ELEGANT BY YASSEMINA — site vitrine / boutique

## Modifier les photos
Ajoutez les photos originales dans le dossier `images` en gardant exactement ces noms :
- `hero.jpg` : grande photo pour la bannière d'accueil
- `product-01.jpg` à `product-06.jpg` : photos des produits

Pour ajouter d'autres produits, dupliquez une carte `.product-card` dans `index.html` et ajoutez son image dans `images/`. Les photos produits utilisent `object-fit: cover` : elles sont automatiquement cadrées pour avoir une grille régulière. Utilisez des photos verticales (idéalement 4:5) pour le meilleur rendu.

## Modifier WhatsApp
Ouvrez `script.js` et remplacez `212600000000` par le numéro WhatsApp de la boutique, avec l'indicatif du pays, sans `+`, espace ni tiret.

## Instagram
Le site pointe vers : https://www.instagram.com/elegant_by_yassemina/

## Publier sur GitHub Pages
1. Créez un dépôt GitHub public nommé `elegant-by-yassemina`.
2. Téléversez `index.html`, `style.css`, `script.js`, `README.md` et le dossier `images`.
3. Dans le dépôt, ouvrez **Settings → Pages**.
4. Dans **Build and deployment**, choisissez **Deploy from a branch**, puis `main` et `/ (root)`, ensuite **Save**.
5. Attendez la publication, puis ouvrez l'adresse affichée dans la page Pages.

Les six photos fournies dans les captures ont été isolées et ajoutées dans `images/`, sans l'interface Instagram. Vous pouvez les remplacer à tout moment par les photos originales HD en gardant les mêmes noms. Le site est statique et prêt pour GitHub Pages ; la gestion dynamique des commandes ou des stocks nécessite un service supplémentaire.
