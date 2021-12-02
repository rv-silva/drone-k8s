# Drone Kubernetes

This repository consists of Kubernets manifests deployed to run Drone Shuttles Ltd Applications.

## List of Contents:

- `poc-k8s-ghost`: used to deploy Kubernetes objects which runs Ghost Application.
- `poc-k8s-nfs`: NFS is used as a persistency layer for Ghost Application.

## How to Deploy Ghost

```
kubectl apply -f poc-k8s-nfs/namespace.yml
kubectl apply -f poc-k8s-nfs/
kubectl apply -f poc-k8s-ghost/
```
