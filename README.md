# NextBuy

Analyse de commandes de courses en ligne et modèles prédictifs, réunis dans un notebook Jupyter.

## Contenu de l'analyse

- **Exploration :** huit questions métier sur les meilleures ventes, les horaires de commande, le bio, le premier article ajouté au panier, les réachats, les profils de clients et l'assortiment
- **Modèle de classification :** prédire si un produit sera commandé de nouveau
- **Modèle de régression :** prédire la taille moyenne du panier des clients qui achètent des produits de boulangerie

## Stack

Python, pandas, NumPy, Matplotlib, seaborn, scikit-learn, XGBoost.

## Lancer le notebook

Les données ne sont pas dans le dépôt. Le notebook attend `orders.csv`, `order_products.csv`, `products.csv`, `aisles.csv` et `departments.csv` dans `NextBuy/datasets/`.

```bash
cd NextBuy
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
