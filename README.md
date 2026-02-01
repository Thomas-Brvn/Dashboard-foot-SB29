# Dashboard foot SB29

Dashboard Power BI et visualisations de donnees pour le Stade Brestois 29.

L'objectif : creer un reporting visuel propre et rapide a partir des donnees Transfermarkt, sans y passer trop de temps. Le projet permet de visualiser les stats des joueurs du club (poste, age, taille, matchs joues, buts marques, valeur marchande) et d'explorer quelques visualisations avancees comme les heatmaps de tirs.

<p align="center">
  <img src="images/ajorque.png" width="90%" />
</p>
<p align="center"><em>Apercu du dashboard Power BI - Ludovic Ajorque</em></p>

## Contenu

- **foot.pbix** : Dashboard Power BI avec les stats des joueurs
- **donnees_et_indicateurs.ipynb** : Notebook Python pour le nettoyage des donnees et les visualisations
- **data/** : Donnees joueurs et valuations

## Outils

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0D76A8?style=for-the-badge&logo=python&logoColor=white)

- **Python / Pandas** : manipulation et nettoyage des donnees
- **Matplotlib / Seaborn** : visualisations et heatmaps
- **Power BI** : creation du dashboard interactif

## Donnees

Les donnees proviennent du dataset [Player Scores](https://www.kaggle.com/datasets/davidcariboo/player-scores) sur Kaggle, issu de Transfermarkt. Il contient les informations sur les joueurs, leurs stats et l'historique de leur valeur marchande.

Fichiers inclus dans le repo :
- [data/players.csv](data/players.csv) : informations joueurs
- [data/player_valuations.csv](data/player_valuations.csv) : historique des valuations

## Visualisations

En plus du dashboard Power BI, le notebook contient des analyses sur les tirs (corners, coups francs) avec des heatmaps pour visualiser les zones de frappe.

<p align="center">
  <img src="images/heatmap.jpg" width="75%" />
</p>
<p align="center"><em>Heatmap des corners et coups francs des joueurs du SB29</em></p>

<p align="center">
  <img src="images/lees_melou.png" width="90%" />
</p>
<p align="center"><em>Apercu du dashboard - Pierre Lees-Melou</em></p>
