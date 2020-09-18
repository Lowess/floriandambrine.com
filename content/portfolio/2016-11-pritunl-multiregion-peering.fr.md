---
title: " Pritunl VPN - Multiregion peering"
date: 2016-11-12T12:14:34+06:00
image: "images/portfolio/pritunl.png"
client: "GumGum"
project_url : "https://pritunl.com/"
categories: ["devops"]
description: "This is meta description."
draft: false
---

#### Le Projet

Pritunl (https://pritunl.com) est une solution VPN d'entreprise open source distribuée. Cette technologie permet de virtualiser un ensemble de réseaux privés qui peuvent être localisés dans des datacenters ou des régions différentes.

Pritunl permet également d'interconnecter des VPC AWS afin d'offrir une meilleur expérience à ses utilisateurs. En effet, une fois connecté au serveur VPN d'une région, l'accès aux autres régions devient alors transparent.

De plus, Pritunl offre des aspects de sécurité très interessants comme l'authentification à deux facteurs de type OTP et le “single sign-on”.

Lors de ce projet, j'ai procédé à la mise en place complète de l'infrastructure Pritunl (4 serveurs Pritunl + 1 serveur MongoDB). Le tout est intégralement automatisé (Création de modules Ansible pour la gestion d'utilisateurs Pritunl). Les différentes régions AWS utilisées chez GumGum ont étés interconnectées.

