# rpk - Redémarrer un processus sous Linux

Ce dépôt contient un exécutable **rpk** qui permet de redémarrer facilement un processus sous Linux via la ligne de commande.

## Fonctionnalité

La commande s'utilise de la manière suivante :

rpk "nom_du_processus"

Elle recherche le processus indiqué par son nom, le termine proprement, puis le relance automatiquement. Cela permet un redémarrage rapide d’un service ou d’une application.

## Installation

1. Clonez ce dépôt.
2. Placez l’exécutable **rpk** dans un dossier inclus dans votre variable d’environnement PATH (.local/bin).
