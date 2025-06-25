# 📦 Analyse des commandes DataShop (janv. 2024 – mars 2025)  
Projet réalisé dans le cadre de ma formation en Data Analyse.

---

## 🧾 Présentation du projet

Ce projet s'inscrit dans une démarche d'apprentissage appliquée à un **cas concret d'analyse de données e-commerce**. L'étude repose sur un jeu de données fourni par **DataShop**, une entreprise fictive spécialisée dans la vente en ligne de **produits électroniques**, **articles de mode** et **équipements pour la maison**.

L'objectif était de simuler une mission réelle confiée à un data analyst, dans laquelle il faut exploiter les données transactionnelles pour aider à la prise de décision stratégique.

Le fichier de données contient des informations détaillées sur les commandes passées par les clients sur une période de **15 mois**, de **janvier 2024 à mars 2025**, avec pour chaque commande :

- Le produit acheté et sa catégorie
- Le montant payé et la quantité achetée
- La localisation de livraison (ville, région)
- La date de commande et la date de livraison
- Un indicateur de clic publicitaire juste avant l’achat (`a_clique_pub`)

---

### Objectifs de l’analyse

L’étude vise à répondre à **trois grandes problématiques** stratégiques :

1. **Performances commerciales**  
   Évaluer le chiffre d'affaires global, le panier moyen, les produits les plus vendus, les régions qui achètent le plus, etc. L’objectif est de fournir une vision claire de la santé commerciale de l’entreprise.

2. **Logistique**  
   Étudier les délais de livraison réels (entre la date de commande et la date de réception) par région. Identifier les zones où les performances sont faibles et où il serait nécessaire d’agir pour améliorer la satisfaction client.

3. **Impact des campagnes publicitaires**  
   Mesurer l’efficacité des publicités en comparant les comportements d’achat des clients exposés à des campagnes publicitaires (clics) et ceux qui ne le sont pas. Cela permet d’estimer le retour sur investissement des campagnes et de mieux cibler les efforts marketing.

---

### Approche utilisée

L’analyse a été réalisée avec **Python** dans un environnement **Jupyter Notebook**.  
Les principales bibliothèques utilisées sont :
- **Pandas** pour la manipulation de données
- **NumPy** pour les calculs
- **Matplotlib** et **Seaborn** pour les visualisations

Le notebook `DataShop.ipynb` contient l'ensemble du code d'exploration, de nettoyage, de visualisation et d’interprétation.  
Des **graphes et indicateurs clés** ont été extraits pour illustrer les tendances, comparaisons et écarts observés dans les données.

Le dépôt est organisé pour faciliter la navigation
