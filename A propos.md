# 🍷 Analyse Stock & Ventes – Mission Business Intelligence chez Bottleneck

## 🎯 Objectif du projet

En tant que Business Analyst chez Bottleneck, enseigne spécialisée dans la vente de vin, j’ai été chargé de consolider, nettoyer et analyser les données issues de plusieurs systèmes afin d’identifier les produits stratégiques, les anomalies de stock, et formuler des recommandations concrètes pour le comité de direction.

---

## 🏢 Contexte

La direction souhaitait disposer d’indicateurs fiables avant d’intégrer un nouvel ERP et de déployer un tableau de bord décisionnel.  
Les données provenaient de 3 sources hétérogènes : ERP interne, site e-commerce, table de liaison.

---

## 🧩 Étapes et méthodologie

### 🔹 Phase 1 – Fusion et nettoyage

- Consolidation des fichiers via `product_id`, `sku`, `id_web`
- Suppression de 85 lignes invalides, nettoyage des doublons
- Création de variables : marge, rotation, mois de stock, prix HT

### 🔹 Phase 2 – Analyses et indicateurs

- Analyse univariée des prix (Boxplot, Z-score, IQR)
- Classements par CA, marges, stocks dormants
- Étude de corrélation (prix/ventes, stock/rotation)
- Identification des produits déficitaires ou non rentables

---

## 🔍 Indicateurs & résultats clés

- 📈 **Top 20 produits = 10 % du CA**
- 💰 **61 % des références génèrent 80 % du chiffre d’affaires**
- 🧊 **Immobilisation de stock : jusqu’à 25 ans**
- ❌ **Taux de marge négatif pour certains produits (jusqu’à -86 %)**
- ✅ **Marge minimale recommandée : 30 %**

---

## 📁 Livrables

- 🧪 [Notebook d’analyse (Jupyter)](./Vatin_Antoine_1_Notebook_022025.ipynb)
- 🎤 [Présentation synthétique à destination du CODIR (PDF)](./Vatin_Antoine_2_presentation_022025.pdf)

> Tous les fichiers sont disponibles dans le dépôt.

---

## 🧠 Compétences mobilisées

### 🔧 Hard Skills

- 🔗 Fusion de datasets multi-sources (ERP, Web, Liaison)
- 🧹 Nettoyage avancé avec **Pandas** (Python)
- 📊 Analyse exploratoire & statistiques descriptives
- 📈 Recommandations métier orientées **marge, rotation et CA**

### 🤝 Soft Skills

- Esprit d’analyse et détection d’anomalies
- Structuration des insights pour des décideurs
- Communication claire et visuelle (CODIR)
- Vision business orientée rentabilité

---

## ✅ Recommandations formulées

- 🔄 Mettre en place un plan d’écoulement des stocks dormants
- 💸 Réviser les prix des produits déficitaires
- 📦 Optimiser les seuils de réapprovisionnement
- ⚙️ Automatiser les contrôles de qualité et alertes
