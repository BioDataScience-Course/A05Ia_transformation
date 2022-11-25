# Importation et traitement des données

## Objectifs

Ceci est un projet **individuel**, **court** et **cadré**. Il permettra de démontrer que vous avez acquis les compétences suivantes :

-   Être capable d'importer des données depuis différents formats et différentes sources avec la fonction `read()`.

-   Maîtriser le remaniement de données, filtrer un tableau et le résumer afin d'en extraire l'information importante.

-   Comprendre et utiliser l'opérateur `%>.%` pour le chaînage des instructions.

## Consignes

Complétez le fichier `coral.Rmd` du dossier `docs` en suivant les instructions qui s'y trouvent. Le tableau de données est disponible via le lien suivant :

> <https://filedn.com/lzGVgfOGxb6mHFQcRn9ueUb/coral/corals.csv>

Le jeu de données reprend des mesures de croissance de différentes espèces de coraux. La masse des coraux est mesurée au début de l'expérience (temps t0) puis une seconde fois après 7 jours (temps t7). Les variables du jeu de données sont :

-   **localisation :** aquarium dans lequel la bouture de corail est placée. Les installations sont composées de deux unités indépendantes (A et B) et de plusieurs aquariums par unité, reliés entre eux,
-   **species :** espèce étudiée,
-   **id :** code de la bouture de corail,
-   **salinity :** salinité mesurée en t7, grandeur sans unité,
-   **temperature :** température mesurée dans l'eau en t7, en °C,
-   **date :** date de la mesure en t7,
-   **time :** nombre de jours écoulés entre la mesure initiale et finale,
-   **gain :** gain de masse entre t0 et t7, en g,
-   **gain_std :** gain/masse initiale, sans unité.

Le template associé à ce projet est le suivant : <https://github.com/BioDataScience-Course/A05Ia_transformation>

