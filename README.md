# tp_python_vde 1.2.0

# Application Pratique: Gestion des Ventes Quotidiennes d'un Magasin

Un magasin enregistre ses ventes quotidiennes sous forme de liste de dictionnaires. Chaque dictionnaire contient les informations suivantes :

- **Date** : La date de la vente (au format "AAAA-MM-JJ").
- **Produit** : Le nom du produit vendu.
- **Quantité** : Le nombre d'unités vendues.
- **Prix Unitaire** : Le prix par unité du produit.
- **Total Vente** : Le total de la vente, calculé comme `Quantité * Prix Unitaire`.
- **Vendeur** : Le nom de la personne ayant effectué la vente.

### Exemple de données
Voici un exemple de ce à quoi pourrait ressembler une entrée de la liste de dictionnaires :

```python
ventes = [
    {
        "Date": "2025-01-21",
        "Produit": "T-shirt",
        "Quantité": 3,
        "Prix Unitaire": 15.99,
        "Total Vente": 47.97,
        "Vendeur": "Alice"
    },
    {
        "Date": "2025-01-21",
        "Produit": "Jean",
        "Quantité": 1,
        "Prix Unitaire": 49.99,
        "Total Vente": 49.99,
        "Vendeur": "Bob"
    }
]
