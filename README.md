# Personnalisation avancée d'un bouton avec CSS

Dans ce segment, nous allons explorer comment styliser un bouton Bootstrap en utilisant du CSS personnalisé pour le rendre plus attrayant et distinctif.

## Contenu

1. [Objectif](#objectif)
2. [Création de la classe "btn-xl"](création-de-la-classe-"btn-xl")
3. [Modification des classes existantes](#modification-des-classes-existantes)
4. [Personnalisation de la classe “btn-primary”](#personnalisation-de-la-classe-“btn-primary”)
5. [Fichiers dans ce dépôt](#fichiers-dans-ce-dépôt)

## Objectif

Apprenez à personnaliser davantage les boutons Bootstrap avec du CSS pour leur donner une allure unique.

## Ajout de la classe "btn-xl"

- Nous introduisons une nouvelle classe `btn-xl` qui n'est pas une classe Bootstrap standard.
- Cette classe est définie avec un padding de 1 REM sur les côtés et 2 REM en haut et en bas pour obtenir un bouton de taille "extra-large".

## Modification des classes existantes

- La classe `btn` est modifiée pour inclure un `font-weight` de 700, ce qui rend le texte un peu plus épais.
- Elle est également modifiée pour avoir un `border-radius` de 300 pixels, arrondissant davantage les bords du bouton.
- De plus, nous utilisons `text-transform: uppercase` pour mettre le texte du bouton en majuscules.

## Personnalisation de la classe “btn-primary”

- Pour changer la couleur de fond de notre bouton, nous utilisons le code hexadécimal `#F05F44`.
- Pour s'assurer que la bordure du bouton correspond à la couleur de fond, nous utilisons la même couleur pour la propriété `border-color` dans notre fichier CSS.

## Fichiers dans ce dépôt

- `index.html` : La page principale de notre site.
- `style.css` : Fichier où toutes nos personnalisations CSS sont ajoutées, y compris les modifications de bouton
- `header.jpg` : Image d'en-tête du site web.

---

Ce tutoriel vous permet de pratiquer et d'expérimenter avec différentes propriétés CSS pour créer des styles de bouton uniques. N'hésitez pas à jouer avec le code et à essayer différentes couleurs et styles. Bon apprentissage !
