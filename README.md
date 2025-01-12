# Projet SIEM

## Description
Ce projet est conçu pour déployer un environnement SIEM (Security Information and Event Management) simple à l'aide de Docker. Il inclut plusieurs services comme Elasticsearch, Kibana, Filebeat, et Suricata pour la collecte, le traitement et la visualisation des données de logs.

Ce projet est une base qui pourra être intégrée à d'autres projets futurs nécessitant des fonctionnalités de surveillance ou d'analyse de sécurité.

---

## Fonctionnalités principales
- **Elasticsearch** : Pour le stockage et la recherche des données.
- **Kibana** : Pour la visualisation et l'analyse des données.
- **Filebeat** : Pour la collecte des logs générés par Suricata.
- **Suricata** : Pour l'analyse des paquets réseau et la détection d'intrusions.

Ce projet inclut des configurations et volumes spécifiques pour chaque service, comme indiqué dans le fichier `docker-compose.yml`. 

---

## Utilisation
Pour lancer l'environnement, exécutez les commandes Docker Compose standard :

docker-compose up -d

Accédez à Kibana sur `http://localhost:5601` pour consulter les tableaux de bord.
