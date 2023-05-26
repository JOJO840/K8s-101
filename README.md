# Installing A Kubernetes Bundle With Monitoring And CI/CD Features

We are 2 students who made a journey with Fabled. On our journey we struggled at the beginning with k8s. 
Thats why we decided to make this k8s 101 file for helping people like us to get to know k8s a little bit better.
We also wanted to give a little info about the components Fabled is currently using.

The increasing popularity of Kubernetes (K8s) attracts a growing number of first-time users seeking proper training. However, these users soon realize that to fully benefit from K8s, they need to incorporate other technologies alongside it. Consequently, the challenge for new users lies not only in studying K8s itself but also in familiarizing themselves with the broader K8s ecosystem, including various open-source software that interacts with it.

While there are numerous online resources covering each software individually, it is uncommon to find tutorials that guide users in setting up a cluster and integrating additional software into it. This repository aims to address this gap by providing instructions and commands for your knowledge.

#K3D
A lightweight and scalable K3d cluster. K3d leverages Docker to create and manage Kubernetes multi-node clusters and is compatible with 'kubectl'.

#Tekton 
A Kubernetes-native CI/CD pipeline solution. The Kubernetes-native approach ensures tight integration with Kubernetes, enabling applications to fully leverage its powerful features, scalability, and resilience. Tekton's fundamental component is called "tasks" and is defined by YAML files.

#Monitoring tools and helm
Grafana, Prometheus, and Loki, which are lightweight, open-source monitoring solutions for real-time cluster monitoring. These monitoring tools are installed using Helm, which is a package manager for Kubernetes. Helm simplifies the deployment process through reusable YAML files known as "Helm charts" that can be pulled from Helm repositories.
