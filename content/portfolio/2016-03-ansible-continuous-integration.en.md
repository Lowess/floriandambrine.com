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

#### The Project

In order to ensure the accuracy of automations, testing is essential! Although, unlike unit testing, continuous integration testing are often more complex to design, especially when you are working with infrastructure as code….

This project aimed to offer a simple process, quick and low-priced that will test a whole set of automations (~100) in order to make sure they will run properly in production.

This where Docker C'est ici que Docker prend tout son sens. Au lieu de démarrer un serveur Amazon pour tester une automatisation, Ansible va se charger de démarrer des conteneurs afin de les automatiser tout comme il le ferait sur un serveur de production. Ansible est capable d'intéragir avec des conteneurs grâce à ses plugins de connexion (http://docs.ansible.com/ansible/developing_plugins.html#connection-type-plugins).

Jenkins s'occupe de tester l'ensemble des automatisations à tour de role, y compris celles necessitant la création de clusters.

