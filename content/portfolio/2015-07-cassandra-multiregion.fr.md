---
title: "Cassandra - Interconnexion de clusters en multi-régions"
date: 2015-07-12T12:14:34+06:00
image: "images/portfolio/cassandra.png"
client: "Snecma"
project_url : "https://themefisher.com/"
categories: ["devops", "automation"]
description: "This is meta description."
draft: false
---

#### Le Projet

Suite à l'ouverture de nouveaux datacenters en Irlande et en Californie, l'équipe d'ingénieurs GumGum a dû faire face à d'importants changements d'architecture afin d'optimiser les temps de réponse des applications utilisant la base de données Cassandra.

Lors de ce projet j'ai travaillé autour d'une problèmatique complexe qui était la suivante:

Comment migrer notre simple cluster Cassandra version 2.0.8 (EC2 Classic) vers un Cluster 2.1.5 multi régions en VPC (Virtual Private Cloud), multi AZ (Availability Zone), multi datacenters (un en Irlande et deux autres aux USA)?

L'ensemble de la migration s'est faite sans interrompre les 20K requêtes de lecture par seconde. Le projet s'est déroulé sur 3 mois incluant une phase de planification, de tests et de migration du système pour sa mise en production.

Pour plus de détails sur le sujet vous pouvez vous référer à cette présentation de Mario Lazaro, Ingénieur BigData chez GumGum, rédigée à l'occasion du #CassandraSummit2015:

* http://slides.com/mario2/cassandra-summit-2015-gumgum#/
