# Dashboard foot SB29

Dashboard Power BI et visualisations de donnees pour le Stade Brestois 29.

L'objectif : creer un reporting visuel propre et rapide a partir des donnees Transfermarkt, sans y passer trop de temps.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6603b7d2-ab7d-4b45-a00f-2e42c712cadd" width="90%" />
</p>

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

<p align="center">
  <img src="https://github.com/user-attachments/assets/baa89661-769b-4eeb-88ec-9872924fff87" width="100%" />
</p>
<p align="center"><em>Schema des donnees</em></p>

## Autres visualisations

Heatmaps des corners et coups francs (non integrees au dashboard) :

<p align="center">
  <img src="https://github.com/user-attachments/assets/fbc24557-3067-4dc3-bbaf-5e5a96a2a2d0" width="75%" />
</p>
