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

#### The Project

After having opened new datacenters in Ireland and in California, GumGum's engineering team had to work on important architecture changes in order to optimize the response time of applications using the NoSql database Cassandra.

The complex problematic of the project was the following:

How to migrate a simple Cassandra cluster version 2.0.8 (running in EC2 Classic) to a Multi-region Cluster version 2.1.5 running in VPC (Virtual Private Cloud) using multi AZ (Availability Zone), multi datacenters (one in Ireland and two others in USA)?

The migration process was completed without interrupting the 20K read requests per second. The project last about 3 month including a planning phase, tests and benchmarks in order to put it in production.

For more details on the subject, you can refer to this presentation written for the #CassandraSummit2015 from Mario Lazaro, Big Data Engineer at GumGum:

http://slides.com/mario2/cassandra-summit-2015-gumgum#/
