# Projet AutoScaling et IaC :

Ce projet a pour objectif de créer une infrastructure comprenant plusieurs services déployés sur un cluster Kubernetes. Les services comprennent un déploiement Redis, un serveur Node.js avec Redis en tant que base de données, ainsi que Prometheus pour la surveillance et la collecte de métriques. L'ensemble du processus de déploiement sera documenté ci-dessous.


## Contenu du Dépôt : 
- la base de donnée redis : <br/>
  un déploiment (un seul replica) <br/>
  un service exposant le déploiment<br/>
- le serveur node redis<br/>
  un déploiment (plusieurs replicas possible)<br/>

  un service exposant le déploiment<br/>
-le front end: <br/>

  un déploiment<br/>

  un service exposant le déploiment<br/>
- Prometheus:<br/>
un dépoilement<br/>

un service exposant le déploiment<br/>

un ficher de configuration <br/>
  

