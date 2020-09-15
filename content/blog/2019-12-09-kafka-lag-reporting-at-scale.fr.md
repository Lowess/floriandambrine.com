---
title: "Karrot Lag Reporting At Scale"
date: 2019-12-09T12:14:34+06:00
image: "images/blog/karrot-lag-reporting.png"
description: "This is meta description."
tags: ["medium"]
draft: false
---

# Karrot Lag reporting

Karrot is a simple Python Flask Webapp that ingests Burrow events sent by Burrow Notifiers which responds to consumer group status evaluations and makes HTTP calls to an outside server, Karrot.
The core feature of Karrot is simple, Take an incoming JSON event sent by Burrow and forward this metrics to multiple services (CloudWatch, Prometheus, and more if needed…).

* https://medium.com/gumgum-tech/karrot-kafka-lag-reporting-at-scale-b32061dcc604
