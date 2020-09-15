---
title: "Fluentd Traitement de données temps réel"
date: 2015-03-12T12:14:34+06:00
image: "images/portfolio/fluentd.png"
client: "Snecma"
project_url : "https://themefisher.com/"
categories: ["devops", "development"]
description: "This is meta description."
draft: false
---

#### Le Projet


Fluentd est une technologie OpenSource permettant de collecter des données afin d'unifier leur traitement et leur stockage.

Le projet que j'ai mené chez GumGum a pour but d'offrir un processus fiable et temps réel d'acheminement d'événements depuis leur source (serveurs frontaux émettant les logs) jusqu'à leur destination où ils seront stockés (Amazon S3 dans ce cas).

L'architecture mise en place aujourd'hui met en jeu une topologie de réseaux connectant les clients aux serveurs. Les clients (forwarders) relayent les différents événements issus de l'application vers les serveurs (aggregators) permettant d'agréger ces messages afin de les stocker sur AWS S3.

Les clients sont configurés de telle sorte que si l'ensemble des serveurs permettant l'agrégation ne répondent pas, ils se chargent eux-mêmes de l'envoi sur AWS S3.

