# Importation et traitement des données

## Avant-propos

Les consignes sont reprises dans ce document, ainsi que sous forme de commentaires dans les différents fichiers. Elles sont susceptibles d'évoluer. N'hésitez pas à vérifier le lien suivant afin de voir si des modifications n'y ont pas été apportées : https://github.com/BioDataScience-Course/A05Ia_transformation.

## Objectifs

Ceci est un projet **individuel**, **court** et **cadré** qui doit être **terminé pour la fin du module 5**. Il permettra de nous démontrer que vous avez acquis les compétences suivantes :

- Être capable d'importer des données depuis différents formats et différentes sources avec la fonction `read()`.

- Maîtriser le remaniement de données, filtrer un tableau et le résumer afin d’en extraire l’information importante.

- Comprendre et utiliser l'opérateur `%>.%` pour le chaînage des instructions.

## Consignes 

### Partie I : coral

- Dans le script `coral_import.R` qui se trouve dans le dossier `R`, importez les données sur la croissance des coraux depuis l'url suivante : 

```
https://docs.google.com/spreadsheets/d/e/2PACX-1vSxqegwJVjO0PxIs7mObr0syeYwNdpvd25AWUoWkwocQexYUqQUK0hC57NwsypQQUDnsJLiR-hxzSFA/pub?output=csv
```

- Ajoutez ensuite le code nécessaire pour enregistrez une copie locale de ce jeu de données au format natif de R (RDS) dans le dossier `data` que vous allez créer préalablement pour l'occasion.

- Complétez le fichier `coral.Rmd` du dossier `docs` en suivant les instructions qui s'y trouvent.

Le jeu de données reprend des mesures de croissance de différentes espèces de coraux. La masse des coraux est mesurée au début de l'expérience (temps t0) puis une seconde fois après 7 jours (temps t7). Les variables du jeu de données sont :

- **localisation :** aquarium dans lequel la bouture de corail est placée. Les installations sont composées de deux unités indépendantes (A et B) et de plusieurs aquariums par unité, relés entre eux,
- **species :** espèce étudiée,
- **id :** code de la bouture de corail,
- **salinity :** salinité mesurée en t7, grandeur sans unité,
- **temperature :** température mesurée dans l'eau en t7, en °C,
- **date :** date de la mesure en t7,
- **time :** nombre de jour écoulés entre la mesure initiale et finale,
- **gain :** gain de masse entre t0 et t7, en g,
- **gain_std :** gain/masse initiale, sans unité.


### Partie II : biometry

- Complétez le document `biometry.Rmd` du dossier `docs` en fonction des consignes qui s'y trouvent. Pensez bien à utiliser un chaînage des opérations avec l'opérateur `%>.%` à chaque fois que cela se justifie.
