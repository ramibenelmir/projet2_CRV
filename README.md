# Projet AutoScaling et IaC :

Ce projet a pour objectif de créer une infrastructure comprenant plusieurs services déployés sur un cluster Kubernetes. Les services comprennent un déploiement Redis, un serveur Node.js avec Redis en tant que base de données, ainsi que Prometheus pour la surveillance et la collecte de métriques. L'ensemble du processus de déploiement sera documenté ci-dessous.


## Contenu du Dépôt : 
- la base de donnée redis : \n
  un déploiment (un seul replica)
  un service exposant le déploiment
- le serveur node redis
  un déploiment (plusieurs replicas possible)
  un service exposant le déploiment
-le front end
  un déploiment
  un service exposant le déploiment
