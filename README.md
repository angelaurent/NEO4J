# BASE DE DONNEES NOSQL ORIENTEE GRAPHE : NEO4J

*TACHE EFFECTUE DANS CE PROJET
1.Mis en place d'un cluster neo4j avec docker-compose.
2.Implementation de la tolerance aux pannes, disponibilite.(MA VERSION DE NEO4J N'IMPLEMENTE PAS LE SHARDING MAIS A PARTIR DE LA VERSION 4 LE MODULE NEO4J FABRIC PERMET DE REALISER LE SHARDING)
3.chargement de notre jeu de donnees.
4.Operation CRUD.
5.Faire du requetage sur notre jeu de donnees.

*UN PEU DE CONNAISSANCE
NEO4J est une base de données qui permet representer de maniere lisible(graphe), de stocker dans un grand nombre de donnees coherents 
les informations qui sont connectées les unes aux autres de maniere complexe.
elle Modélise les données sous forme de nœuds ,de relations et de propriétés,adaptée à toutes les données.
Open source.
c'est une Base de données transactionnelles, respectueuse des principes ACID et est disponible via la mise en place d'un cluster .
elle Permet des requêtes rapides et des analyses avancées sur des ensembles de données complexes car elle Utilise APACHE LUCENE pour l'indexation et la recherche de données.

#NEO4J dispose d'un puissant langage de requête,utilisé pour créer et récupérer des relations entre les données sans utiliser les requêtes complexes comme les jointures appele CYPHER
#NEO4J dispose d'une Application Web intégrée qui permet de créer et interroger nos données, d'importer nos données à partir d’un fichier ou site web appele NEO4J BROSWER

#PARTICULARITE DE NEO4J
1.Architecture de clustering causale
2.Tolérance aux pannes (plusieurs stratégies comme clustering autonome, réplica en mode lecture)
3.Sans schéma
4.Haute performance
5.Evolutivité et fiabilité
6.Flexibilité
7.Sécurité
8.Cohérence causale
9.Système de requêtage plus plaisant (absence de jointures)

#USE CASE
1.Logistique 
2.Réseau social
3.Recommandation de produit
3.Gestion des droits d’accès 
4.Biologie, interactions moléculaires
5.Les services financiers


