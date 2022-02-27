# squest-k8s-deployment
This repo used for to assist in installing a self service catalog tool - Squest - on Kubernetes. Project information for Squest can be found here - https://github.com/HewlettPackard/squest

# Kubernetes Requirements
* K8S Cluster with version 1.21 and up
* A Storage Class provider for persistent volumes

# Usage
git clone https://github.com/slarimore02/squest-k8s-deployment.git
kubectl apply -f squest-k8s-deployment/
