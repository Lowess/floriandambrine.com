---
title: "Logstash - Centralisation d'évènements"
date: 2014-06-12T12:14:34+06:00
image: "images/portfolio/logstash.png"
client: "GumGum"
project_url : "https://www.elastic.co/logstash"
categories: ["internship", "development"]
description: "This is meta description."
draft: false
---

#### Le Projet

J’ai eu l’occasion d’évaluer des outils de gestion de logs et d’événements afin de trouver une solution de remplacement à l’outils Splunk>Storm qui devenait trop honnereux. J’ai donc exploré et évalué les capacités d’une nouvelle technologie nommée Logstash.

L’architecture que j’ai élaborée permet d’acheminer les évenements depuis les serveurs de production jusqu’en base de données. Cette chaine met en jeu un cluster Elasticsearch, un serveur Redis et un groupe de serveurs Logstash analysant ces événements. L’ensemble des données est utilisé par le serveur Kibana mettant à disposition les logs d’une douzaine de services différents.

Un ensemble de scripts a également été developpé afin de déclencher des alertes par email lors de détection d’erreurs.

