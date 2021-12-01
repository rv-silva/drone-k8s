# Ghost Kubernetes

This directory contains objects to create Ghost Kubernetes Application and its dependencies including Deployment, Service, HPA, Configmap & Ingress.

- K8s Deployment to release new versions of the application multiple times per day without downtime.
- K8s HPA so the number of Pods can be incresead to handle of up to 4 times the typical load.
- To prevent from security exposure, GKE cluster runs in Private configuration. Therefore, Ghost K8s exposes the App with external LoadBalancer managed with the K8s Ingress.
