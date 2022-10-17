# Deploying Flask application on Kubernetes

This example deploys a Flask application on Kubernetes by using Deployments and services.
The service is exposed by using an Nginx Ingress Controller.


kubectl get pods -n kube-system

kubectl -n kubernetes-dashboard config view --minify

kubectl config view --minify --raw