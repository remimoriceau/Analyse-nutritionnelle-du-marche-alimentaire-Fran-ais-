# Analyse nutritionnelle du marché alimentaire français

Analyse de la qualité nutritionnelle de 473 487 produits vendus en France,
à partir de la base Open Food Facts.

## Contexte

Le marché alimentaire français compte des centaines de milliers de produits.
Ce projet évalue leur qualité nutritionnelle à travers deux systèmes :
le Nutri-Score (qualité nutritionnelle de A à E) et le groupe NOVA
(niveau de transformation industrielle de 1 à 4).

## Résultats clés

- 28,24% des produits ont un Nutri-Score E (pire note)
- Seulement 24,65% atteignent un Nutri-Score A ou B
- Les aliments ultra-transformés (NOVA 4) sont les plus représentés avec 153 000 produits

## Stack technique

 Outil et Usage 
 Python / pandas => Nettoyage, chunking, visualisations 
 SQL / SQLite => Base de données, 5 requêtes analytiques 
 Power BI => Dashboard interactif, mesures DAX 

## Fichiers

- `analyse_nutritionnelle.ipynb` : nettoyage des données et visualisations Python
- `SQL.ipynb` : 5 requêtes analytiques sur la base SQLite

## Source des données

Open Food Facts — base collaborative publique
https://world.openfoodfacts.org/
