# EDF_Simulateur_Prix
Un outil pour simuler les différents Tarifs EDF depuis un export Linky de la consommation.

Basé sur une idée de [Nicolas 'Automnen'](https://twitter.com/autommen/) et [Malory Bouvier](https://twitter.com/MaloryBouvier/).

Derniers tarifs: 1 Aout 2023

## Utilisation
### Depuis le site d'EDF
1) Récupérez sur le site d'EDF votre consommation [https://equilibre.edf.fr/comprendre?dashboardOpenRequired=true](https://equilibre.edf.fr/comprendre?dashboardOpenRequired=true)
![Bouton télécharger](https://user-images.githubusercontent.com/1168432/216930725-d3af991d-7761-40bc-892f-285d11390fd8.png)
2) Dézippez ce répertoire
3) Téléchargez ce projet en cliquant sur le bouton code puis "Download zip"
![Comment récupérer le projet](https://user-images.githubusercontent.com/1168432/216541398-0d862d3f-30d6-4b08-9e79-7e3d5a1cdfef.png)
4) Dézippez-le
5) Double-cliquez sur le fichier index.html. Il devrait s'ouvrir dans votre navigateur.
6) Cliquez sur parcourir et sélectionné votre fichier "mes-puissances-atteintes-30min-XXXXX-YYYYY.csv" **(Ne modifiez pas le nom du fichier!)**
7) A partir de là, vous pouvez choisir les différentes tarifications que vous voulez expérimenter !

### Depuis le site d'Enedis
1) Depuis le site d'Enedis: [https://mon-compte-particulier.enedis.fr/mes-telechargements-mesures/](https://mon-compte-particulier.enedis.fr/mes-telechargements-mesures/)
2) Cliquez sur "Nouveau Téléchargement" en haut à droite
3) Sélectionnez "Consommation horaire"
4) Cliquez sur Date de début et cherchez la date la plus ancienne
5) Cliquez sur Télécharger mes données
6) Revenez plus tard sur la page "Mes téléchargements". La génération du fichier n'est pas immédiate
7) Quand une nouvelle ligne apparaît sur cette page, cliquez sur la flèche pour télécharger

## A venir
- [ ] Amélioration de Tempo. Actuellement les jours rouges sont pris aléatoirement.
  - [ ] Sélectionner les pires jours rouges de l'année
  - [ ] Autoriser l'utilisateur à sélectionner ses jours rouges et blancs

## A propos de l'auteur
[Jean-Christophe VASSELON](https://www.linkedin.com/in/jvasselon/), responsable produit chez un éditeur de PLM le jour, éditeur [d'un outil pour gérer la patientèle des diététicien(ne)s](https://www.patientailes.com) la nuit.