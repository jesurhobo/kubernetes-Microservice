# Microservices Demo with Kubernetes

This project provides Kubernetes manifest files for deploying the  [Google Microservices Demo](https://github.com/GoogleCloudPlatform/microservices-demo) in a Kubernetes cluster. The Google Microservices Demo is a cloud-native application simulating an e-commerce platform composed of various microservices. The Kubernetes manifest files enable efficient deployment and management of these microservices in a Kubernetes environment..

## Introduction

The Google Microservices Demo is a cloud-native application that simulates a web-based e-commerce platform, consisting of several microservices. Each microserviice has its separate deployment and service configuration files with best practices such as livenessProbe and Resource management implemented.


## Prerequisites

Before you begin, ensure you have the following installed:

- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- A running Kubernetes cluster
- Docker (if you plan to build and push custom Docker images)