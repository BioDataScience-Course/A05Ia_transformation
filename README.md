# Module 5 : importation et au traitement des données

## Avant-propos

Les consignes sont reprises dans ce document, ainsi que sous forme de commentaires dans les différents fichiers. Elles sont susceptibles d'évoluer. N'hésitez pas à vérifier le lien suivant afin de voir si des modifications n'y ont pas été apportées : https://github.com/BioDataScience-Course/A05Ga_transformation.

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

- Enregistrez une copie locale du jeu de données dans le dossier `data` que vous allez créer préalablement pour l'occasion, toujours dans `coral_import.R`.

- Complétez le fichier `coral.Rmd` du dossier `docs` en suivant les instructions qui s'y trouvent.

Le jeu de données reprend des mesures de croissance de différentes espèces de coraux. La masse est mesurée en t0 puis une seconde fois après 7 jours de suivi.

- localisation : aquarium dans lequel la bouture est placée. Les installations sont composées de deux unités (A et B)et de plusieurs bacs par unité.
species : espèce étudiée
- id : code de l'individu
- salinity : salinité mesurée en t7
- temperature : température mesurée en t7
- date : date de la mesure en t7
- time : nombre de jour entre la mesure initiale et finale
- gain : gain de masse en g entre le jour t0 et t7
- gain_std : gain/masse initiale

### Partie II : biometry

- Complétez le document `biometry.Rmd` du dossier `docs` en fonction des consignes qui s'y trouvent. Pensez bien à utiliser un chaînage des opérations avec l'opérateur `%>.%` à chaque fois que cela se justifie.
