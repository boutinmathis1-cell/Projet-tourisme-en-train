# 🚅 Projet Latitude : Tourisme en train
Faciliter et encourager le voyage bas carbone en France.

🌍 Contexte
Aujourd'hui, 69 % de l'empreinte carbone du tourisme provient du transport. Pourtant, le train émet en moyenne 10 fois moins de CO2 que la voiture.

Le Projet Latitude propose une solution technique pour lever les freins au tourisme ferroviaire en croisant les données de transport et les points d'intérêt (POI) touristiques sur l'ensemble du territoire français.

🚀 Fonctionnalités clés
🗺️ Carte Interactive : Visualisation croisée des gares SNCF et des sites touristiques labellisés.

📊 Indice IATR : Un score exclusif d'Accessibilité Touristique par département (basé sur la densité, le trafic et la proximité).

⏱️ Temps de trajet réels : Intégration de l'API SNCF pour calculer les durées de voyage (et non une simple distance à vol d'oiseau).

🌱 Calculateur CO2 : Estimation de l'économie carbone réalisée par rapport à un trajet en voiture.

🚲 Le Dernier Kilomètre : Identification des modes de transport doux (navettes, vélos, marche) à l'arrivée en gare.

📈 L'Indice IATR (Indice d'Accessibilité Touristique)
Nous avons créé un indicateur pondéré (normalisé sur 100) pour évaluer le potentiel touristique ferroviaire d'une zone :

Densité de gares locales.

Trafic voyageurs annuel (flux).

Proximité des POI dans un rayon de 10 km autour des gares.

🛠️ Stack Technique
Visualisation de données : Microsoft Power BI (Dashboard interactif).

Développement Web : Astro & Observable Plot (pour la version web en cours de déploiement).

Traitement de données : Power Query / Python.

API : API SNCF (Navitia) pour les calculs d'itinéraires en temps réel.

📂 Sources de données (Open Data)
Ce projet repose sur l'exploitation de plusieurs jeux de données publics :

SNCF Open Data : Référentiel des gares de voyageurs (gares-de-voyageurs.csv).

DATAtourisme : Inventaire des Points d'Intérêt et établissements "Qualité Tourisme" (datatourisme-tour.csv).

API SNCF : Flux de départs et calculateur d'itinéraires.

👥 L'Équipe
Projet réalisé par :

Maxendre B.

Mathis B.

Mohsine E.

Auxence T.
