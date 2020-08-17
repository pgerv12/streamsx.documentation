---
layout: docs
title: Introduction to Streams development for edge analytics
navtitle: Introduction
description: IBM® Streams can be used to develop and build applications for edge analyics using IBM Edge Analytics Beta on Cloud Pak for Data.
weight: 45
published: true
tag: edge
next:
  file: edgeanalytics/kafka-options
  title: Apache Kafka options for edge applications
---

IBM® Streams can be used to develop and build applications for edge analytics using IBM Edge Analytics Beta on Cloud Pak for Data.


For more information about Edge Analytics, see the [IBM Edge Analytics Beta on Cloud Pak for Data](https:// https://www.ibm.com/support/knowledgecenter/SSQNUZ_3.0.1/svc-welcome/edge.html) documentation.

***

To get started creating a Streams application for edge analytics, view one or more Streams edge samples:

* Python Notebooks
  1. [sample.edge-rolling-average](https://github.com/IBMStreams/sample.edge-rolling-average) - Level: Beginner - Rolling average of stock prices
  1. [sample.edge-mnist-notebook](https://github.com/IBMStreams/sample.edge-mnist-notebook) - Level: Advanced - Handwritten digit image recognition application
  1. [sample.edge-batch-return](https://github.com/IBMStreams/sample.edge-batch-return) - Level: Intermediate, fault-tolerance handling - A Streams application showcasing network disconnects from edge system to central Cloud Pak for Data control plane.
  1. [sample.edge-app-control](https://github.com/IBMStreams/sample.edge-app-control) - Level: Intermediate, required submission-time parameter handling - A Streams application that showcases using submission-time parameters.

* Streams Flows
  1. [sample.edge-mnist](https://github.com/IBMStreams/sample.edge-mnist) - Level: Advanced - Handwritten digit image recognition application

* Streams Processing Language (SPL)
  1. [sample.netflow](https://github.com/IBMStreams/sample.netflow) - Level: Advanced, multi-application submission, coordination - Collects network statistics and presents them centrally in a web display.

For more information about develop and building edge applications using IBM Streams, see [Moving analytics to the edge with Edge Analytics](https://www.ibm.com/support/knowledgecenter/SSQNUZ_3.0.1/svc-edge/usage.html).

***

One way to communicate data from edge applications to a central cloud platform, service, or application is through a data feed or messaging system like Apache Kafka. See [Apache Kafka options for edge applications](kafka-options) for a list of a few possible Kafka installation options and how to interface with those options in your edge applications using Streams toolkits.
