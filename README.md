# Automatic-k8s-gcp

Sample configuration YAML files for automatic provisioning GKE cluster and deployment of applications.

Google's Deployment Manager is used to provision resources and deploy Weaveworks' Flux Operator. This Operator, in turn, will pick up all YAML files stored under `apps` subdirectory, and apply them to Kubernetes cluster.
