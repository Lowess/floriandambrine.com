---
title: "Logstash - Centralisation d'évènements"
date: 2014-06-12T12:14:34+06:00
image: "images/portfolio/logstash.png"
client: "Snecma"
project_url : "https://themefisher.com/"
categories: ["internship", "development"]
description: "This is meta description."
draft: false
---

#### The Project

I have had a chance to compare several centralized logging solutions in order to replace the current Splunk>Storm architecture. I decided to dig into Logstash which is a tool for managing events and logs. You can use it to collect logs, parse them, and store them for later use (like, for searching). Logstash is well integrated with Elasticsearch and Kibana, this stack is commonly named ELK.

The architecture involves, Logstash forwarders (deployed over more than 150 servers), a Redis queue that helps to buffer events coming from the forwarders, a group of Logstash servers acting as parsers that inserts processed logs into Elasticsearch. Kibana is the final bundle of this architecture which displays dashboards and graphs exploiting Elasticsearch data.

I developed a couple of scripts in order to trigger email alerts when a threshold is reached or optimize monitor or maintain the Elasticsearch backend.

