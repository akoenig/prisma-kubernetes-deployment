# Graphcool Prisma – Kubernetes Deployment

Example repository for demonstrating how to deploy a [Prisma](https://www.prismagraphql.com/)-based application to a [Kubernetes](https://kubernetes.io/) cluster.

## Table of Contents

**TBD**

## Motivation

In this tutorial, you will learn how to create a Prisma cluster on Kubernetes and deploy your prisma services to it.

[Kubernetes](https://kubernetes.io/) is a container orchestrator, that helps with deploying and scaling of your containerized applications.

<InfoBox>

The setup in this tutorial assumes that you have a running Kubernetes cluster in place. There are several providers out there that gives you the possibility to establish and maintain a production grade cluster. This tutorial aims to be provider agnostic, because Kubernetes is the abstraction layer. The only part which differs slightly is the mechanism for creating `persistent volumes`. Here, we use the [Kubernetes Engine](https://cloud.google.com/kubernetes-engine) on the [Google Cloud Platform](https://cloud.google.com/).

</InfoBox>

## 1. Prerequisites

  * A running Kubernetes cluster
  * A local version of [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) which is configured to communicate with your Kubernetes cluster

## 2. Creating a separate namespace

Kubernetes comes with the primitive of `namespaces`. A `namespace` helps to group your applications logically. 


## Author

MIT © [André König](https://andrekoenig.de)
