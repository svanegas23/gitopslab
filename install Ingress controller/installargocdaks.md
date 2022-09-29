Install ArgoCD on an AKS cluster with NGINX

In this post, I’ll walk through the essentials of configuring an AKS cluster to use Argo CD with an NGINX Ingress Controller.

Pre-Requisites

You’ll need:

An AKS cluster. Here’s a Gist I use to create a simple cluster.

Helm 3

Azure CLI

A Custom DNS/Access to the provider (I will be using Azure DNS)
