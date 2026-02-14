# Projet_Chlordecone_Theo_Roussel
Vous trouverez ici la réalisation d’un projet de première année à l’ENSAR portant sur l’analyse de la contamination au chlordécone en Martinique.

Objectif :
Ce projet analyse la contamination des sols au chlordécone en Martinique afin d’identifier les zones les plus touchées et d’aider à la prise de décision publique.
Les données couvrent :
-	3 610 parcelles
-	36 communes
-	Environ 31 000 mesures
-	Période : 2005 – 2019

Organisation du dossier :
• 📁 data/ - données
    •	📁 source/ - données brutes
    •	📁 dataclean/ - données nettoyées
• 📁 outputs/ - tables agrégées prêtes pour Power BI
• 📓 Chlordecone_Theo_Roussel.ipynb - notebook (nettoyage, analyse, clustering)
• 📊 Power BI Théo.pbix – Tableau de bord
• 📄 Aide à la décision Chlordécone.pdf - synthèse & recommandations

Fonctionnement du projet :

Les données brutes sont placées dans data/source/.
Le notebook Python permet de réaliser plusieurs traitements sur les données et de fournir une première analyse des résultats.
Des tables agrégées sont générées dans outputs/.
Le Power BI s’appuie sur ces tables pour créer des visualisations et un tableau de bord interactif.
Enfin, le PDF d’aide à la décision présente les résultats de façon simple et concise et indique des recommandations.

Contenu du notebook :

Le notebook python permet de :
Nettoyer les données
Analyse descriptive
Création des tables agrégées
Visualiser les premiers résultats
ACP et clustering
Effectuer des tests statistiques
Exporter les tables finales

Pour refaire l’analyse :

Ouvrir Chlordecone_Theo_Roussel.ipynb
Exécuter les cellules dans l’ordre
Vérifier que les fichiers sont générés dans outputs/
Ouvrir le fichier Power BI et actualiser les données

