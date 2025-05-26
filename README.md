# 👩‍💼 OC - Projet 7 : Automatisation d’un diagnostic égalité femmes-hommes avec KNIME

Ce projet a pour but d’automatiser l’analyse de l’égalité professionnelle femmes-hommes à partir des données issues du Système d’Information RH (SIRH) d’un cabinet de conseil en pleine croissance. L’analyse s’appuie sur les recommandations du **Ministère du Travail**.

---

## 🎯 Objectif de la mission

> Fournir un **workflow automatisé** pour générer des indicateurs clés liés à l’égalité femmes-hommes, ainsi qu’un fichier .csv prêt à être intégré dans **Tableau Software** pour la datavisualisation.

Les livrables attendus sont :

- Un **workflow KNIME** permettant de :
  - Nettoyer et anonymiser les données RH
  - Calculer au moins **5 indicateurs d’égalité professionnelle**
  - Générer automatiquement des graphiques pour un reporting
- Un fichier `.csv` exporté automatiquement pour usage dans **Tableau**

---

## 📁 Arborescence du projet

```
├── P7_KNIME.knwf              → Workflow KNIME du diagnostic
├── data/                      → Données RH (non incluses pour confidentialité)
├── export/diagnostic.csv      → Fichier généré prêt à l’usage pour Tableau
├── README.md                  → Présentation du projet
└── ressources/                → Documentation et références officielles
```

---

## 📊 Indicateurs analysés

Parmi les indicateurs recommandés par le Ministère du Travail, le workflow extrait et traite notamment :

- Écart de rémunération femmes-hommes
- Écart de taux d’augmentation
- Écart de taux de promotion
- Présence de femmes parmi les 10 plus hautes rémunérations
- Taux de retour de congé maternité avec augmentation salariale

---

## 🔐 Traitement RGPD

Toutes les **informations personnelles identifiables** (noms, emails, ID RH) sont supprimées ou pseudonymisées afin de garantir la conformité RGPD.

---

## 🛠️ Outils utilisés

- **KNIME Analytics Platform** : préparation, transformation et analyse des données
- **Tableau Software** : visualisation finale des indicateurs
- `CSV` : pour les exports standardisés

---

## 📈 Visualisations générées

- Graphiques en barres par sexe
- Histogrammes des écarts de rémunération
- Diagrammes circulaires de répartition
- Export automatisé des résultats en `.csv`

---

## 🧠 Auteur

Projet réalisé par **AnthonyJVID** dans le cadre du parcours *Data Analyst* chez OpenClassrooms.

---

## 📄 Licence

Projet destiné à un usage pédagogique et démonstratif, sans diffusion des données RH originales.
