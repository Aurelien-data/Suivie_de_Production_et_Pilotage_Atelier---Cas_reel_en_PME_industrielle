# 🏭 Suivi de Production et Pilotage Atelier – Cas réel en PME industrielle

## 🎯 Objectif du projet
Ce dashboard Power BI a été développé pour une PME industrielle spécialisée dans la fabrication de gaines de ventilation. L’objectif : fournir un outil de suivi opérationnel précis et évolutif, capable de refléter en temps réel l’état d’avancement des lots de production, leur historique et les éventuels blocages.

## 🧠 Contexte métier
Dans cette entreprise en pleine transition digitale, aucun indicateur centralisé ne permettait jusqu’alors de suivre les performances de l’atelier de manière fine. Les données issues de l’ERP étaient difficilement exploitables en l’état.
Ce projet s’est donc inscrit dans une démarche de structuration de la donnée, de fiabilisation des informations et de création d’un outil d’aide à la décision pour les responsables de production.

## 📊 Fonctionnalités du dashboard
Suivi quotidien de l’avancement des lots (GAINE, PLENUM, etc.)

Calcul du taux d’avancement réel basé sur les étapes effectivement réalisées

Identification des lots bloqués ou en stagnation

Visualisation des retards et alertes (via dates de livraison et fabrication)

Historisation automatique via snapshots journaliers

Calcul du nombre de jours ouvrés de stockage et catégorisation des statuts de stockage

Suivi de la charge de travail et des capacités disponibles par groupe (Gaine, Plenum)

## ⚙️ Outils & Technologies utilisés
Power BI

Power Query (nettoyage, transformation)

DAX (mesures avancées, logique de surcharge)

DAX Studio (export snapshots)

Python (scripts d’automatisation des snapshots)

.bat (workflow automatisé local)

## 🧩 Structure technique
Modèle en étoile avec table de faits centralisée (FACT_PLANNING)

Intégration de données ERP via ODBC + fichiers Excel exportés

Gestion des prix composants avec historisation temporelle

Calculs DAX complexes pour la surcharge atelier, les alertes, la traçabilité des lots

🚀 Résultats & impact
💡 Mise à disposition d’un outil 100 % automatisé, consultable à tout moment

📈 Gain de visibilité sur les goulots d’étranglement

⏱️ Gain de temps dans l’analyse quotidienne de la production

🤝 Adoption forte par les équipes grâce à un design métier simple et clair

🧠 Réelle aide au pilotage pour anticiper les saturations et arbitrer les priorités

## 📁 Confidentialité
Les données sources et fichiers Power BI ne peuvent être publiés pour des raisons de confidentialité (RGPD & propriété de l’entreprise).
👉 Ce projet est néanmoins valorisable comme démonstration de cas concret d’intégration BI en entreprise, avec une forte implication métier et technique.

## ✅ En résumé
Un projet complet mêlant :

Compréhension des besoins métiers

Structuration et fiabilisation des données

Modélisation DAX et automatisation

Intégration dans le quotidien des équipes

Ce travail illustre parfaitement ma capacité à traduire des enjeux opérationnels en solutions BI concrètes et efficaces.
