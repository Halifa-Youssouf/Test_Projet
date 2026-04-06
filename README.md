# Analyse de Performance Financière Globale (Power BI)

# Contexte du projet
Ce projet consiste en la création d'un tableau de bord décisionnel interactif permettant de piloter la performance commerciale d'une entreprise internationale. À partir d'un jeu de données financières complexes, j'ai transformé des lignes brutes en insights visuels exploitables pour la direction générale.

# Objectifs 
Le projet s'articule autour de **quatre axes majeurs** :  

1. **Analyse de la Structure des Revenus :**  
   Visualiser la répartition des ventes par segment et par pays pour identifier immédiatement les marchés piliers (ex : domination du secteur Government).  

2. **Performance Produit (Deep-Dive) :**  
   Identifier les produits leaders au sein de chaque segment et zone géographique afin d'optimiser le catalogue et la gestion des stocks.

   
4. **Intelligence Temporelle :**  
   Suivre l’évolution des ventes dans le temps pour détecter les saisonnalités, les pics de croissance et les cycles de vente.  

5. **Aide à la Décision (Self-Service BI) :**  
   Fournir un outil interactif et intuitif permettant aux décideurs d'explorer les données en toute autonomie pour une prise de décision rapide et basée sur les faits.

# Stack Technique & Méthodologie
 
- **Outil :** Microsoft Power BI Desktop  
- **ETL (Power Query) :** nettoyage des données, gestion des types (monnaies, dates), création de colonnes calculées et des mesures 
- **Modélisation :** mise en place d'un schéma en étoile pour optimiser les performances des filtres  
- **DAX (Data Analysis Expressions) :** création de mesures personnalisées pour le calcul des variations et des parts de marché.

# Analyse du Dashboard (Key Visuals)

## 1. Indicateur de Performance Flash (KPI)
- **Ventes Totales :** 118,73M€  
  Un chiffre imposant qui donne immédiatement l'échelle de l'entreprise analysée.

## 2. Répartition Stratégique (Donut Chart)
- Le segment **Government** domine avec **44,22%** du chiffre d'affaires.  
- Le segment **Enterprise** suit avec **35,74%**.  
- **Insight Analyst :** L'entreprise est fortement dépendante des contrats publics, ce qui demande une gestion de compte spécifique.

## 3. Arbre de Décomposition (Decomposition Tree) – La pièce maîtresse
- Ce visuel permet d'explorer la donnée de manière dynamique :  
  **Segment → Pays → Produit**  
- Exemple : dans le segment **Government** en France, le produit **Amarilla** génère plus de **2,68M€**.  
- C'est cet outil qui permet de faire du "**Deep Dive**" (analyse profonde).

## 4. Analyse Temporelle (Trend Line)
- Le graphique montre une forte volatilité des ventes avec des **pics de croissance marqués**.  
- Permet d'identifier des **effets de saisonnalité** ou l'impact de **campagnes marketing spécifiques**.

---
## Résultats et Recommandations
Grâce à ce dashboard, un décideur peut :  

- **Cibler les efforts marketing :** Prioriser les produits comme **Amarilla** ou **Paseo** qui performent bien sur les segments clés.  
- **Optimiser les stocks :** Ajuster la production en fonction des volumes de ventes par pays (**USA** et **Canada** en tête).  
- **Sécuriser les revenus :** Diversifier les segments pour réduire la dépendance au **secteur gouvernemental**.
  
