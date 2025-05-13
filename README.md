# nginx-k8s-deployment
## Preview

This repository provides the Kubernetes configuration files required to deploy an Nginx web server. The configuration files include a custom namespace and deployment manifest to set up the Nginx container within a Kubernetes cluster.
# Nginx Kubernetes Deployment

## Project Structure
- `deployment.yaml` - Defines the Nginx Deployment.
- `namespace.yaml` - Defines a custom Kubernetes namespace for organizing resources.

## How to Use

1. Ensure your Kubernetes cluster is running (e.g., using `minikube`, `kind`, or a cloud provider).
2. Apply the custom namespace:
   ```bash
 kubectl apply -f deployment.yaml

kubectl get pods -n <your-namespace>
git blame k8s/deployment.yaml
git blame k8s/namespace.yaml
