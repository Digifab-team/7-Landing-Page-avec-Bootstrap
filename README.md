# Alignement du contenu avec Flexbox

Dans ce tutoriel, nous explorerons l'alignement du contenu en utilisant Flexbox, particulièrement avec l'aide de Bootstrap.

## Contenu

1. [Introduction](#introduction)
2. [Activer Flexbox](#activer-flexbox)
3. [Centrage vertical avec Bootstrap](#centrage-vertical-avec-bootstrap)
4. [Centrage horizontal](#centrage-horizontal)
5. [Ajout d'espace entre les éléments](#ajout-despace-entre-les-éléments)
6. [Prochaines étapes](#prochaines-étapes)
7. [Fichiers dans ce dépôt](#fichiers-dans-ce-dépôt)

## Introduction

L'objectif de ce tutoriel est de montrer comment centrer correctement du contenu en utilisant Flexbox, une fonctionnalité puissante de Bootstrap.

## Activer Flexbox

Pour activer Flexbox, nous utilisons la classe `d-flex` dans Bootstrap. En ajoutant cette classe à la div `container`, nous activons Flexbox pour ce conteneur.

## Centrage vertical avec Bootstrap

Après avoir activé Flexbox, nous voulons centrer nos éléments verticalement. Pour cela, nous utilisons la classe `align-items-center`. Cependant, il est essentiel de comprendre que cela aligne les éléments au centre du conteneur. Si le conteneur ne couvre pas toute la hauteur de la page, l'effet attendu ne sera pas atteint. Pour résoudre cela, nous utilisons la classe `h-100` de Bootstrap pour garantir que le conteneur couvre 100% de la hauteur de la page.

## Centrage horizontal

Si votre titre ou tout autre élément est court, il peut apparaître aligné à gauche. Pour garantir un centrage horizontal, nous ajoutons la classe `justify-content-center`.

## Ajout d'espace entre les éléments

Pour ajouter de l'espace entre certains éléments, comme du texte et un bouton, nous pouvons introduire une div avec une nouvelle classe, comme `buffer`. Cette classe peut avoir une hauteur définie pour garantir un espacement approprié. L'utilisation de l'unité `REM` au lieu de pixels est recommandée pour garantir la scalabilité et la flexibilité.

## Prochaines étapes

Bien que nous ayons réussi à bien centrer notre contenu, il reste encore du travail à faire. Dans l'étape suivante, nous explorerons comment rendre notre bouton fonctionnel, permettant aux visiteurs d'ouvrir une nouvelle page pour saisir leurs e-mails.

## Fichiers dans ce dépôt

- `index.html` : Le fichier principal du site web.
- `style.css` : Ce fichier contient les styles nécessaires pour la mise en forme de notre page.
- `header.jpg` : L'image d'en-tête utilisée dans le tutoriel.

---

Rejoignez-nous pour le prochain tutoriel et continuez à explorer les capacités puissantes de Bootstrap et de Flexbox.
