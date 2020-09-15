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

Fluentd is an OpenSource data collector for unified logging layer. It allows you to unify data collection and consumption for a better use and understanding of data.

The project I lead at GumGum was meant for building a reliable and real-time process able to ship events from a source (front-end servers emitting events) to a destination where there are stored (in that case AWS S3).

Today's production architecture is a network topology connecting clients to servers. Clients (forwarders) ship their events using TCP sockets to servers named aggregators. They aggregate all theses events coming from multiple clients in order to upload them by batch on AWS S3
.
Clients are also configured with a fail-over mechanism. If all aggregator servers are not responding, the client itself will take care of the upload to S3.

