# checkpointDataBases


### Diapositive 1 : Introduction

Titre : Qu’est-ce qu’une base de données ?

Contenu :

    . Définition générale d'une base de données.

    . Types principaux : SQL (relationnelle) vs NoSQL (non relationnelle).

    . Objectif de la présentation : comparer MongoDB (NoSQL) et une base SQL comme MySQL ou      PostgreSQL.



### Diapositive 2 : Présentation de SQL (ex. MySQL/PostgreSQL)

Titre : Bases de données relationnelles (SQL)

Contenu :

    . Données organisées en tables avec colonnes.

    . Utilisation du langage SQL pour interroger les données.

    . Schéma fixe (structure prédéfinie).

    . Exemples : MySQL, PostgreSQL, SQLite.

    . Avantages : intégrité des données, relations puissantes (jointures).



### Diapositive 3 : Présentation de MongoDB (NoSQL)

Titre : MongoDB – Base de données NoSQL

Contenu :

    . Données stockées sous forme de documents JSON (flexibles).

    . Pas de schéma fixe, structure dynamique.

    . Très bon pour les données non structurées ou semi-structurées.

    . Scalable horizontalement (ajout de serveurs).

    . Utilisé pour des applications modernes (temps réel, big data...).


### Diapositive 4 : Comparaison SQL vs MongoDB

Titre : Comparaison des deux approches

Tableau comparatif :

|------------------------------|---------------------------|---------------------------------|
|                              |                           |                                 |
|   Critère                    |    SQL (MySQL)	           |             MongoDB(NoSQL)      |
|------------------------------|---------------------------|---------------------------------|
|   Structure	               |     Tables & colonnes	   |          Documents JSON         |
|------------------------------|---------------------------|---------------------------------|
|    Schéma	                   |      Fixe	               |            Flexible             |
|------------------------------|---------------------------|---------------------------------|
|    Langage de requête	             SQL	                           Requêtes BSON/JSON    |
|------------------------------|---------------------------|---------------------------------|
|    Relations	                     Forte (jointures)	               Faible (imbriqué)     |
|------------------------------|---------------------------|---------------------------------|
|    Scalabilité	                 Verticale	                       Horizontale           |
|------------------------------|---------------------------|---------------------------------|
|    Cas d’usage typique	         ERP, banques	                   IoT, réseaux sociaux  |
|------------------------------|---------------------------|---------------------------------|


#### Diapositive 5 : Conclusion

Titre : Quand utiliser SQL ou MongoDB ?

Contenu :

    . SQL : idéal pour les applications structurées, critiques, avec des relations fortes.

    . MongoDB : parfait pour les données flexibles, gros volumes, applications modernes.

    . Résumé : il n’y a pas de meilleur choix absolu, cela dépend du besoin du projet.