# euromillions-git

> 📆 02/2026.

## Description du projet 

* Importer les fichiers d'historique des tirages Euromillions à partir du site [FDJ.fr](https://www.fdj.fr/jeux-de-tirage/euromillions-my-million/historique).
* Créer une API vérifiant si une combinison est déjà sortie.   

## Environnement technique

* Python
* Pandas
* Notebook JupyterLab (Anaconda)
* FastAPI

## Phase 1 : initialisation du projet

* Définition d'une arborescence "standard" de projet IA.
* Importation des fichiers d'historique :
  * Décompression des fichiers (_.csv_ au format _.zip_).
  * Suppression des colonnes inutiles, uniformisation des noms de colonnes (renommage). 
* Correction de données erronées ou manquantes.
* Vérification des donnés manquantes.
* Fusion des différents fichiers dans un dataframe Pandas.
* Uniformisation du formatage des dates.  
* Export du dataframe Pandas unique dans un fichier csv (_global.csv_).

## Phase 2 

* Versioning de données avec DVC.
* Mise en oeuvre de FastAPI. (⌛ en cours 02/2026, pas encore sur Github) 

## Phase 3 (⌛ à venir)

* Statistiques et probabilités de sorties (sur un malentendu ça peut marcher de gagner 220 millions d'euros 😃).

## ⌛ TODO 

* Correction problème formatage de dates erronées (valeur : 01/01/1970, unix timestamp).
* Procédure d'installation de ce projet à partir du clonage du repository.