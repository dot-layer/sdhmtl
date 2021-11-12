# SDHMTL

Site web pour la conférence science des données appliquée au hockey de Montréal (édition 2022).

## Compiler le site

Ce site statique est compilé avec la version 0.78.2 de [Hugo](https://gohugo.io/). Bien qu'on puisse
simplement installer Hugo en suivant les instructions suggérées, on conseille d'utiliser le
*package* R [`blogdown`](https://pkgs.rstudio.com/blogdown/) puisque celui-ci va gérer
automatiquement l'installation de la bonne version de Hugo au besoin.

Pour compiler et afficher le site en local avec Hugo, on exécute à la ligne de commande

```
hugo server
```

Pour compiler et afficher le site en local avec `blogdown`, on exécute dans la console R

```
blogdown::serve_site()
```

Prendre note que la version publiée du site se compile et se déploie automatiquement à chaque fois
qu'un nouveau commit est poussé sur la branche `main`.
