# CIASIE 2018 - Intégration & Documents Web - Rendu du td8

*Le td8 consiste en la création d'un micro-framework à l'aide de sass. Ce micro-framework contient un système de grid, un header, des boutons et des alertes configurables à l'aide de variables. En plus de la version sass du framework, deux versions pré-configurée en css sont également disponibles.*

## Visualiser les différentes versions

3 pages sont disponible dans la racine du répertoire pour visualiser le rendu de la version sass et les deux versions css générées

```td8-sass.html``` pour la version **sass configurable**.
```td8-css-1.html``` & ```td8-css-2.html``` pour les deux versions **css pré-paramètrées**.

## Utilisation du framework dans sa version sass

Avant toute chose il faut installer [Sass](https://sass-lang.com/).

Pour configurer le framework dans sa version sass, il y a deux méthodes possibles :

- Soit en demandant à sass de générer un fichier css à chaque changement grace à la commande **watch** depuis la racine du répertoire :

  ```
  sass --watch ../sass/td8.sass:../css/td8.css
  ```
  puis en modifiant les valeurs des variables dans le fichier ```sass/_variables.sass```

- Ou alors il est également possible de modifier les variables puis de générer le fichier css une fois les modifications faites grâce à la commande **build** depuis la racine du répertoire

  ```
  sass --build ../sass/td8.sass:../css/td8.css
  ```

