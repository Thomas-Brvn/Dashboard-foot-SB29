# Dashboard foot SB29

Dashboard Power BI et visualisations de donnees pour le Stade Brestois 29.

L'objectif : creer un reporting visuel propre et rapide a partir des donnees Transfermarkt, sans y passer trop de temps.

## Contenu

- **foot.pbix** : Dashboard Power BI avec les stats des joueurs (poste, age, taille, matchs, buts, valeur marchande)
- **donnees_et_indicateurs.ipynb** : Notebook Python pour le nettoyage des donnees et quelques visualisations (heatmaps corners/coups francs)
- **data/** : Donnees joueurs et valuations ([source Kaggle](https://www.kaggle.com/datasets/davidcariboo/player-scores))

## Outils

- Python / Pandas pour la manipulation de donnees
- Matplotlib / Seaborn pour les visualisations
- Power BI pour le dashboard

## Donnees

Les donnees proviennent du dataset [Player Scores](https://www.kaggle.com/datasets/davidcariboo/player-scores) sur Kaggle (Transfermarkt).

Fichiers inclus dans le repo :
- [data/players.csv](data/players.csv)
- [data/player_valuations.csv](data/player_valuations.csv)

## Visualisations

Heatmap des corners et coups francs :

<p align="center">
  <img src="images/heatmap.jpg" width="75%" />
</p>
