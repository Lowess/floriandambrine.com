---
title: "Ansible - Continuous Integration"
date: 2016-03-12T12:14:34+06:00
image: "images/portfolio/docker.png"
client: "GumGum"
project_url : "https://themefisher.com/"
categories: ["devops", "automation", "ci/cd"]
description: "This is meta description."
draft: false
---

#### Le Projet

Afin d'assurer le bon fonctionnement des automatisations, les tests sont indispensables! Cependant, contrairement aux tests unitaires, les tests d'intégration continue sont souvent plus compliqués à concevoir, d'autant plus avec un code décrivant l'infrastructure…

Ce projet a pour but d'offrir un processus simple, rapide et peu coûteux pour tester toute une batterie d'automatisations (~100) afin d'assurer son bon fonctionnement en production.

C'est ici que Docker prend tout son sens. Au lieu de démarrer un serveur Amazon pour tester une automatisation, Ansible va se charger de démarrer des conteneurs afin de les automatiser tout comme il le ferait sur un serveur de production. Ansible est capable d'intéragir avec des conteneurs grâce à ses plugins de connexion (http://docs.ansible.com/ansible/developing_plugins.html#connection-type-plugins).

Jenkins s'occupe de tester l'ensemble des automatisations à tour de role, y compris celles necessitant la création de clusters.
