# olist-customer-segmentation
Segmentation client basée sur clustering K-Means et indicateurs RFM sur des données transactionnelles d’Olist. Analyse métier approfondie et validation de la stabilité temporelle des segments.


## Projet 4 : `olist-customer-segmentation`

```markdown
# Segmentation Client E-commerce - Olist

J’ai réalisé une segmentation des clients d’Olist, une entreprise de e-commerce brésilienne, à partir de données transactionnelles incluant commandes, fréquence d’achat et satisfaction. J’ai construit des indicateurs comportementaux (RFM, taux de satisfaction), appliqué des algorithmes de clustering (K-Means), et validé la stabilité des segments dans le temps pour assurer leur pertinence métier.

## Fonctionnalités

- Agrégation des données clients via requêtes SQL
- Construction de scores RFM et autres indicateurs clés
- Normalisation, encodage et préparation des données pour clustering
- Application et optimisation du clustering K-Means
- Analyse métier des segments clients
- Étude de la stabilité temporelle des clusters (ARI)

## Technologies utilisées

- SQL (MySQL / DBeaver)
- Python (pandas, NumPy, scikit-learn, Seaborn, Matplotlib)

## Installation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/tonPseudo/olist-customer-segmentation.git
