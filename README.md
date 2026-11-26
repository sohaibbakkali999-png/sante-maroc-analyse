# Répartition et Équité Territoriale des Établissements de Santé au Maroc

Analyse de données sur la répartition des établissements publics de santé au Maroc entre les régions, les délégations et les milieux urbain/rural.

## Problématique

> La répartition des établissements de santé au Maroc est-elle équitable entre les différentes régions, délégations et communes, et existe-t-il des disparités dans l'accès aux infrastructures de santé selon les territoires ?

## Objectifs

- Dresser un état des lieux de l'offre publique de santé (3 394 établissements).
- Comparer la dotation entre les 12 régions administratives.
- Identifier les délégations les plus et les moins dotées (82 délégations).
- Évaluer l'équilibre entre milieu rural et milieu urbain.
- Comparer le réseau des soins de santé primaires et le réseau hospitalier.

## Source des données

Données officielles du **Ministère de la Santé et de la Protection Sociale du Royaume du Maroc** (carte sanitaire nationale).

- Fichier : `data/etablissements_sante_maroc.csv`
- 3 394 observations et 8 variables
- Soins de santé primaires (2024) et réseau hospitalier public (2022)

| Colonne | Description |
| :--- | :--- |
| `Région` | Région administrative (12 régions) |
| `Délégation` | Délégation provinciale ou préfectorale (82) |
| `Commune` | Commune d'implantation |
| `Nom_établissement` | Nom officiel de la structure |
| `Catégorie` | Code abrégé (CSR-1, CSU-1, DR, HP, etc.) |
| `Libellé_catégorie` | Description complète de la catégorie |
| `Type_établissement` | Soins primaires ou Hôpital |
| `Année_source` | Année du recensement (2022 ou 2024) |

## Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, SciPy, Jupyter Notebook

## Structure du projet

```
├── analyse.ipynb
├── data/
│   └── etablissements_sante_maroc.csv
├── requirements.txt
└── README.md
```

## Lancer le projet

```bash
git clone https://github.com/TON_USERNAME/sante-maroc-analyse.git
cd sante-maroc-analyse
pip install -r requirements.txt
jupyter notebook analyse.ipynb
```

## Auteur

**Sohaib** — ISTA NTIC Tanger
