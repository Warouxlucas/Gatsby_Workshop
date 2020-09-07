# Gatsby_Workshop
This is an intro about gatsby.js


## Prerequis 
A priori pas grand chose de spécial : 
  * Avoir un ordinateur, de preference avec un os
  * Y avoir node.js installé 
                                      
## Que va-t-on aborder lors de ce Workshop ? 
Et bien Gastby pardi ! 

Ok, plus serieusement, on va créer un petit site statique tout simple, pour cela on va faire un tour rapide d'un stack composé de : 
 
  * Gatsby (basé sur React)
  * Un headless cms (strapi)
  * Requetes graphQL (trés brievement, vous aurez l'occasion d'en voir plus avec Thomas)

Dans un premier temps, je vais essayer de vous réexpliquer ce qu'est gatsby.js et pourquoi c'est [magnifique](https://giphy.com/gifs/great-gatsby-matt01ss-sp685iuIEGuys/tile).

Ensuite, On va se "quick starté", en utilisant un starter de base proposé par gatsby et y explorer un peu l'environnement. 

Puis, on va se faire un petit headless cms oklm 

## Pourquoi Gatsby ? 

La performence. 


Gatsby est un framework React qui permet de créer des sites statiques perfomants, qui adhère aux principes des Progressives web apps sans même devoir y penser, qui nous apporte un tas de plugin et outils pour optimiser nos performences ainsi que notre SEO. 

Il nous permet egalement d'utiliser des sources de contenu varié comme des API provenant d'un cms, des fichier Markdown, du Json recuperable via GraphQL.

Les pages sont préchargées, les requetes, les fichiers javascript et css sont décomposés par page ce qui permet de charger que le strict minimum nécéssaire à la bonne éxecution de la page. 

La cerise sur le gateau, Gatsby nous offres un environement de travail express, il nous permet de compiler l'ensemble des fichiers crée une version prête pour la production et de lancer un serveur de développement en une ligne de commande

## Quick Start !

#### 1. installer le CLI Gatsby
```

npm install -g gatsby-cli

```
> afin d'installer le cli gatsby globalement sur votre machine





