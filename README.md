# AAA · VentureScout

Projet du cours *Analyse de données et Apprentissage Automatique* (IMT Atlantique).

**Question :** une startup qui vient de faire sa première levée *angel / seed* lèvera-t-elle auprès de fonds de capital-risque (tour Series A/B/C ou *venture*) dans les 24 mois ? Classification binaire sur données tabulaires.

## Notebooks

| Notebook | Contenu | Colab |
|---|---|---|
| `notebooks/01_construction_dataset.ipynb` | Des tables brutes Crunchbase à un tableau « 1 ligne = 1 startup » avec la cible `y` | [Ouvrir](https://colab.research.google.com/github/Baptisteg-92/AAA/blob/main/notebooks/01_construction_dataset.ipynb) |
| `notebooks/02_exploration_donnees.ipynb` | Exploration des données (EDA) et clustering | [Ouvrir](https://colab.research.google.com/github/Baptisteg-92/AAA/blob/main/notebooks/02_exploration_donnees.ipynb) |

Les données sont lues directement depuis ce dépôt GitHub : rien à télécharger ni à installer dans Colab.

## Données

- `data/raw/` : export officiel Crunchbase d'octobre 2013 (`companies`, `rounds`, `investments`, `acquisitions`), licence CC-BY au moment de l'export. Source : https://github.com/datahoarder/crunchbase-october-2013
- `data/processed/venturescout_dataset.csv` : tableau final produit par le notebook 1 (2 503 startups, 19 variables, 25 % de `y = 1`).
