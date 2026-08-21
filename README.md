
## Contenu du notebook

1. Distribution d'une variable avec histplot()
2. Distribution d'une variable avec kdeplot()
3. Distribution d'une variable avec boxplot()
4. Distribution d'une variable avec violinplot()
5. Comptage des catégories avec countplot()
6. Relation entre deux variables avec scatterplot()
7. Régression avec regplot()
8. Régression avec lmplot()
9. Corrélations (matrice Pandas + heatmap)
10. Analyse multivariée avec pairplot()
11. Sauvegarde des graphiques dans exports/
12. Bonus : analyse temporelle de la consommation (par heure et par plage horaire, croisée avec le bâtiment)

Chaque partie répond directement, dans le notebook, aux questions d'interprétation posées dans l'énoncé.

## Principaux constats

- Les températures sont concentrées autour de 25°C, avec une distribution globalement symétrique.
- Le bâtiment B004 se distingue nettement des trois autres : valeurs extrêmes de température (-18,5°C et 58,7°C), dispersion la plus forte, et le plus grand nombre de mesures en alerte.
- La seule corrélation notable du jeu de données est celle entre température et consommation (environ 0,32) ; les autres paires de variables sont proches de zéro.
- La consommation varie selon l'heure de la journée et selon le bâtiment, ce qui ouvre une piste concrète d'optimisation énergétique ciblée.

## Utilisation

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook notebooks/atelier_seaborn_iot.ipynb
```

## Livraison

Le dossier est poussé sur un dépôt public GitHub, d'abord vide puis mis à jour au fur et à mesure avec des messages de commit explicites.