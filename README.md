# data_refirment
Projet de nettoyage et de raffinement de données sur un dataset de ventes de café
# ☕ Projet : Raffinement du Dataset Cafe Sales

Ce projet consiste en un processus complet de **nettoyage, transformation et analyse** d'un jeu de données brut contenant 10 000 transactions d'un café. [cite_start]L'objectif est de transformer une donnée "sale" en un dataset exploitable pour la Business Intelligence. [cite: 30, 31]

## 📂 Structure du Projet

L'organisation des fichiers suit les standards de la Data Science pour assurer la reproductibilité :

- **DATA/** : 
    - [cite_start]`RAW/` : Contient le dataset original (`dirty_cafe_sales.csv`). [cite: 33]
    - [cite_start]`PROCESSED/` : Contient le dataset final nettoyé (`cleaned_cafe_sales.csv`). [cite: 48]
- **NOTEBOOKS/** : Fichiers Jupyter contenant le code de diagnostic et de nettoyage.
- **REPORTS/** : Rapport final détaillé au format PDF.

## 🛠️ Actions de Nettoyage (Data Quality)

Le diagnostic initial a révélé des manques importants (ex: 2579 paiements et 3265 localisations manquantes). [cite_start]Voici les actions entreprises : [cite: 33]

* [cite_start]**Correction des types** : Conversion des prix et quantités en format numérique. [cite: 34, 41]
* [cite_start]**Traitement des nuls** : Suppression des lignes sans produit (`Item`) et imputation par "Unknown" pour le reste. [cite: 37, 38]
* [cite_start]**Standardisation** : Correction des fautes de frappe et uniformisation de la casse des noms de produits. [cite: 39]

## 📊 Résultats Clés

L'analyse après raffinement montre que :
* [cite_start]**Top 10 Produits** : Les salades et sandwichs génèrent le chiffre d'affaires le plus élevé. [cite: 42, 44]
* [cite_start]**Validation** : La corrélation parfaite entre quantité et prix confirme la fiabilité de la donnée finale. [cite: 46]
* [cite_start]**Temporalité** : 100% des transactions enregistrées se situent durant la période du soir. [cite: 45]

## 🚀 Installation et Utilisation

1. Cloner le dépôt :
   ```bash
   git clone [https://github.com/votre-compte/data_refirment.git](https://github.com/votre-compte/data_refirment.git)


   pip install -r requirements.txt