#  Analyse des ventes d’un supermarché avec SQL

## À propos du projet 
Dans ce projet, j’ai analysé des données de ventes d’un supermarché afin de mieux comprendre les tendances commerciales et le comportement des clients.

L’objectif était de mettre en pratique mes compétences en SQL pour extraire des informations utiles à partir de données réelles.

##  Objectifs de l’analyse
- Identifier les produits les plus vendus  
- Déterminer les catégories les plus rentables  
- Analyser les ventes par ville  
- Étudier l’évolution des ventes dans le temps  
- Comprendre les préférences de paiement des clients
- pour chaque achat d'un produit donnez le nom du client
- la moyenne des ventes pour chaque client
- la vente minimale et maximale


## 🗂️ Données utilisées
Le dataset principal 'facture.cvs' contient :
- facture_ID  
- ville 
- Catégorie 
- nom_produit 
- prix_unitaire
- Quantite
- Date  
- méthode payement
  

### 2️⃣ Dataset clients
'clients.csv' contient   
- Client_ID  
- facture_ID
- Nom 
- Genre
- Age  
- ville 


## 🛠️ Outils
- SQL  

## 📊 Ce que j’ai appris
Grâce à ce projet, j’ai appris à :
- Manipuler des données avec SQL  
- Utiliser GROUP BY, SUM, ORDER BY, LIMIT, INNER JOIN, AVG, COUNT,MIN, MAX...
- Analyser des données pour en tirer des conclusions  

## 📁 Structure du projet 
sql-supermarket-sales-analysis
│
├── README.md
├── questions.md
├── analysis.sql
├── dataset.csv
