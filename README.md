# project_circulation_routiere
Étude et analyse des accidents corporels de la circulation routière

La description du projet permet de fournir tout un ensemble d'information par rapport au contexte et au secteur cible. Certaines informations essentielles, comme les contraintes du projet ou encore les objectifs à atteindre, y sont définies.

Une compagnie d'assurance propose à ses clients des contrats d'assurance automobile avec un système bonus malus. Afin de pouvoir personnaliser au mieux le contrat d'assurance et proposer une prime adaptée à chaque client, la compagnie souhaite utiliser des données récoltées sur les différents accidents survenus dans la localisation où réside le client. En effet, la prime doit être en mesure de refléter le caractère accidentogène de la région où réside le client.

Pour cela, la compagnie fait appel à tes services dans le but de développer un Dashboard permettant d'obtenir des statistiques détaillées sur les accidents corporels de la circulation routière. Ce Dashboard interactif permettra alors aux équipes de tarification de pouvoir ajuster au mieux leur modèle de tarification dans le but de refléter au plus possible la réalité.

**Contraintes**
Afin de répondre aux besoins des équipes métiers, il est demandé de produire un Dashboard interactif en deux parties, et en utilisant Streamlit dans le but de pouvoir ensuite déployer en interne.

**Statistiques**
Afin de pouvoir disposer de métriques quantitatives, les équipes métiers souhaitent avoir sur une page l'ensemble des graphiques suivants.

- Le nombre d'accidents par mois.
- Le nombre d'accidents par jour.
- Le nombre d'usagers par gravité d'accident.
- Les catégories de véhicules impliqués.
- La répartition des accidents par type de trajet.
- La répartition des usagers par sexe.
- Le nombre d'accidents par condition atmosphérique.
- La répartition des obstacles mobiles heurtés (véhicule, piéton, animal, etc).
En plus de ces graphiques, on souhaiterait également avec les statistiques descriptives suivantes.

- Le nombre d'accidents.
- Le nombre de véhicules impliqués.
- Le nombre d'usagers impliqués.
- Le nombre de décès.
- Le taux de létalité.
  
**Carte interactive**
Les équipes métiers souhaitent également disposer d'une carte interactive, leur permettant d'analyser l'ensemble des accidents survenus à une localisation précise, et également de pouvoir filtrer selon plusieurs caractéristiques. En particulier, les équipes souhaitent disposer de la possibilité de filtrer sur les paramètres suivants.

- Le département.
- Les conditions atmosphériques.
- Les conditions d'éclairage.
- La localisation (en ou hors agglomération).
- La catégorie de route.
- Le type de collision.
Sur la base de ces filtres, les équipes souhaitent avoir par ailleurs, en plus de la carte interactive, les informations suivantes.

- Le nombre d'accidents.
- Le nombre de véhicules impliqués.
- Le nombre d'usagers impliqués.
- Le nombre de décès.
- Le taux de létalité.

**Description des données**
La compagnie met à disposition plusieurs fichiers contenant différentes informations.

- Le fichier usagers.csv contient des informations sur les usagers (conducteurs, passagers, piétions cyclistes) impliqués dans les accidents, qu'ils soient responsables ou non.
- Le fichier vehicules.csv contient des informations sur les véhicules impliqués dans les accidents.
- Le fichier lieux.csv contient des informations sur les lieux où se sont produits les accidents.
- Le fichier caracteristiques.csv contient diverses informations comme la date, les conditions météos ou la luminosité.
- La description détaillée des données est fournie dans l'onglet Données.
