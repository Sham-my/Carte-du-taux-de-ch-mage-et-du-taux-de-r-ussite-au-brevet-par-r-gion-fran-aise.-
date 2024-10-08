# Cartographie du Chômage et du Taux de Réussite au Brevet par Région Française
![carte chomage reussite](https://github.com/Sham-my/Carte-du-taux-de-ch-mage-et-du-taux-de-r-ussite-au-brevet-par-r-gion-fran-aise.-/blob/main/chomage_et_reussite.png)

Pour réaliser cette carte, j'ai utilisé deux bases de données distinctes : l'une contenant des informations relatives aux établissements réalisant le Diplôme National du Brevet (DNB) pour l'année \2016 (source : data.education.gouv.fr), et l'autre contenant le taux de chômage pour le premier semestre de 2016.

Étapes de Réalisation :

  1. Regroupement des Bases de Données :
    Les données des établissements scolaires et les taux de chômage ont été regroupés par département.
  2. Calcul des Moyennes :
    Une requête SQL a été exécutée pour calculer la moyenne du taux de réussite au brevet par département.
  3. Intégration dans QGIS :
    Les données ont ensuite été intégrées dans QGIS pour une représentation graphique claire et informative.

 Aperçu des Tables Utilisées :
  Tableau des Départements :

 ![tableur departement](https://github.com/Sham-my/Carte-du-taux-de-ch-mage-et-du-taux-de-r-ussite-au-brevet-par-r-gion-fran-aise.-/blob/main/tableur%20departement.PNG)

  Tableau des Établissements :

![tableur etablissement](https://github.com/Sham-my/Carte-du-taux-de-ch-mage-et-du-taux-de-r-ussite-au-brevet-par-r-gion-fran-aise.-/blob/main/tableur%20etablissement.PNG)

  Code SQL Utilisé :

![partie2 2](https://github.com/Sham-my/Carte-du-taux-de-ch-mage-et-du-taux-de-r-ussite-au-brevet-par-r-gion-fran-aise.-/blob/main/partie2.2.jpg)
