# Présentation du projet

Dans ce projet d'utilisation de Microsoft Azure pour la création d'un model de prédiction. J'ai utilisé la problématique des accidents de route déjà traitée par Ilyes Talbi (https://larevueia.fr/xgboost-vs-random-forest-predire-la-gravite-dun-accident-de-la-route/)

Suite à toute la partie préparation de la donnée, j'ai créé 3 modèles prédictifs différents : KNN, DecisionTree et RandomForest.

À la fin, j'ai choisi un de ces 3 modèles pour créer une API qui permet d'utiliser mon modèle via le Cloud.

# Sources des données (cf : Ilyes Talbi )

Les données ont été tirées du site data.gouv.fr. 

carac.csv nous donne des caractéristiques sur les accidents
lieux.csv recense des données sur les lieux des accidents
veh.csv donne des informations sur les véhicules impliqués
vict.csv donne des informations sur les victimes

Concrètement, pour chaque victime, la gravité de l’accident est donnée sur une échelle de 1 à 4 :

1 : Indemne
2 : Tué
3 : Hospitalisé
4 : Blessé léger

# Eléments du repository

Dans ce repository, il sera possible de retrouver dans un premier temps, un notebook avec les commandes de créations du modèle.

Et aussi un autre notebook avec le code pour utiliser le modèle.

# Modèle retenu et ses performances

Le modèle choisi pour à la suite partager le modèle est le KNN.

Pour des raison techniques j'ai pas eu la possibilité de creer les autres modèles car le code est long.

# Lien de l'endpoint du modèle

