# LINIA — Piste 1 « La Maison créative »

Prototype statique responsive pour présenter LINIA comme un concept store créatif chaleureux à Remouchamps : boutique beaux-arts, ateliers, coin café, créations locales, conseils personnalisés et histoire de Jennifer.

## Objectif
La piste 1 crée l’attachement autour d’un lieu humain : **acheter, se poser, créer**. Elle reste compatible avec une future transformation WordPress, Gutenberg et WooCommerce.

## Fichiers créés
- `index.html` : page complète du prototype.
- `css/styles.css` : design system, responsive, cartes WooCommerce-like et placeholders.
- `js/main.js` : menu mobile et apparition progressive légère.
- `assets/brand/linia-logo.svg` : logo local de présentation.
- `assets/brand/linia-hero.svg` : visuel d’ambiance local de présentation.
- `assets/placeholders/` : visuels SVG représentatifs pour la boutique, les ateliers, le café, les créateurs locaux, Jennifer et les produits.
- `docs/synthese-piste-1.md` : synthèse stratégique avant conception.

## Ouvrir en local
Double-cliquer sur `index.html` ou l’ouvrir dans un navigateur moderne.

## Lancer un serveur local simple
Depuis la racine du projet :

```bash
python3 -m http.server 8000
```

Puis ouvrir : `http://localhost:8000`.

## Tester sur smartphone via le même Wi-Fi
1. Connecter l’ordinateur et le smartphone au même réseau Wi-Fi.
2. Trouver l’adresse IP locale de l’ordinateur :
   ```bash
   hostname -I
   ```
3. Lancer le serveur :
   ```bash
   python3 -m http.server 8000 --bind 0.0.0.0
   ```
4. Ouvrir sur le smartphone : `http://ADRESSE-IP:8000`.

## Publier sur GitHub Pages
1. Pousser le dépôt sur GitHub.
2. Aller dans **Settings > Pages**.
3. Choisir la branche de publication et le dossier racine `/`.
4. Enregistrer, puis ouvrir l’URL GitHub Pages fournie.

## Transposition WordPress / WooCommerce
- Transformer chaque `section.wp-section` en bloc Gutenberg ou pattern.
- Créer un thème léger ou thème enfant sur Hostinger.
- Migrer les cartes produits vers une boucle WooCommerce.
- Créer les ateliers comme produits WooCommerce virtuels avec stock limité correspondant aux places disponibles.
- Ajouter les cartes cadeaux comme produits WooCommerce dédiés.
- Prévoir pages : Accueil, Boutique WooCommerce, Ateliers, Créateurs locaux, Cartes cadeaux, À propos, Contact.

## Points à adapter plus tard
- Vraies photos du lieu, de Jennifer, des ateliers et produits.
- Adresse complète, horaires et coordonnées.
- Produits réels, prix, stocks et catégories.
- Ateliers réels, dates, animateurs, niveaux et conditions.
- Intégration WooCommerce complète.
- Paiements Stripe ou Mollie.
- Google Maps.
- Formulaires de contact et inscription newsletter.

## Sources et limites
Les annexes textuelles et visuelles ont été exploitées depuis le brief et les images fournies dans la conversation. Les fichiers photos d’origine n’étant pas présents dans le dépôt, des visuels SVG représentatifs locaux ont été créés pour éviter toute dépendance externe ; ils devront être remplacés par les vraies photos de Linia dès qu’elles seront disponibles.
