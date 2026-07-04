# Synthèse — Piste 1 « La Maison créative »

## Intention
Créer une page d’accueil prototype qui présente LINIA comme un lieu de vie créatif à Remouchamps : on y vient pour acheter du matériel choisi, se poser dans un coin café et créer en atelier. La piste cherche d’abord l’attachement, sans perdre les réflexes commerciaux nécessaires à une future boutique WooCommerce.

## Messages prioritaires
- « Linia, c’est acheter, se poser, créer. »
- « Là où la création commence. »
- Une boutique indépendante, humaine et locale, loin d’une grande surface impersonnelle.
- Des ateliers accessibles aux débutants, familles, curieux et créatifs confirmés.
- Une sélection courte, qualitative et accompagnée de vrais conseils.
- Un lieu chaleureux qui valorise Jennifer, les artistes invités et les créateurs locaux.

## Style visuel retenu
Style éditorial, doux, artisanal et légèrement bohème : fonds crème et papier chaud, accents terracotta, argile et vert sauge, formes organiques, lignes fines et placeholders texturés. Les titres utilisent Playfair Display et les textes Inter, avec fallbacks propres.

## Sections du prototype
1. Header responsive avec navigation et CTA atelier.
2. Hero en deux colonnes avec signature, ligne graphique et visuel d’ambiance.
3. Trois portes d’entrée : boutique, ateliers, coin café.
4. Cartes ateliers façon produits WooCommerce virtuels avec prix, date, durée, niveau et stock.
5. Sélection boutique façon grille WooCommerce.
6. Coin café et détente.
7. Créateurs locaux.
8. Histoire et sens du nom Linia.
9. Réassurance.
10. Infos pratiques et placeholder Google Maps.
11. Footer avec SEO local.

## Implications WordPress / WooCommerce
- Chaque section est structurée comme un futur bloc Gutenberg (`wp-section`, `wp-container`, `wp-card-grid`).
- Les produits utilisent des classes `wc-product-card`, `wc-price`, `wc-view-product` et `wc-add-to-cart` pour préparer une boucle WooCommerce.
- Les ateliers sont modélisés comme de futurs produits WooCommerce virtuels avec stock limité, prix et bouton de réservation.
- La navigation prépare l’arborescence : Accueil, Boutique, Ateliers, Créateurs locaux, Cartes cadeaux, À propos, Contact.
- Les contenus dynamiques futurs pourront devenir des produits, catégories, fiches ateliers, pages CMS et blocs réutilisables.

## Éléments sources utilisés
- Questionnaire : positionnement de concept store créatif, public large, mots-clés transmission/lien/rencontre/créativité, refus du froid, du corporate, de l’élitisme et de la grande surface.
- Questionnaire : histoire du nom LINIA, origine liée à la ligne, au premier trait, au lien et à la transmission.
- Questionnaire : freins avant achat/réservation, besoin de rassurer sur le niveau, les conseils, le matériel et l’accessibilité.
- Questionnaire : familles de produits beaux-arts, dessin, illustration, papiers, loisirs créatifs, créations locales et librairie spécialisée.
- Questionnaire : ateliers en petits groupes, généralement six places en intérieur, filtrables par date, public, technique et niveau.
- Crowdfunding : importance de l’aménagement du lieu, de l’espace atelier, du coin cosy, de la communauté locale et des réseaux sociaux.
- Visuels fournis : direction naturelle, terracotta, matières papier, végétaux, café, matériel artistique, slogan et composition organique.

## Limites des sources
Les images annexes ont été fournies dans la conversation, mais pas comme fichiers directement présents dans le dépôt. Le prototype crée donc des SVG de marque et des visuels représentatifs locaux dans `/assets/brand/` et `/assets/placeholders/` en attendant les fichiers sources définitifs.
Les images annexes ont été fournies dans la conversation, mais pas comme fichiers directement présents dans le dépôt. Le prototype crée donc des SVG de marque et des placeholders locaux dans `/assets/brand/` et `/assets/placeholders/` en attendant les fichiers sources définitifs.
