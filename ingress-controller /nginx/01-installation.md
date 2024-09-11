## Install Nginx Ingress Controller on AWS
Step 1: Deploy the below manifest

```bash

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.11.1/deploy/static/provider/aws/deploy.yaml

```bash

## Documentation 
   https://kubernetes.github.io/ingress-nginx/deploy/

   https://github.com/kubernetes/ingress-nginx?tab=readme-ov-file

# How works 

```bash

Ingress controller will look ingress service and create the lB

ingress resourecs (File) <-----Ingress Controller->LB

```bash

## Command 

```bash

kubectl get pods -n ingress-nginx
kubectl get ing


```bash