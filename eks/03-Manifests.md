## Run the following command to apply the YAML file and create the deployment:

   kubectl apply -f k8s/manifests/deployment.yaml 
## To deploy service: 

   kubectl apply -f k8s/manifests/service.yaml 

##  For ingress: 

   kubectl apply -f k8s/manifests/ingress.yaml 

##  Important Command 

kubectl get nodes -o wide

kubectl get svc

## Delete 
kubectl delete deployment go-web-app


## Helm crete command 2 times 

helm create go-web-app-chart

then 

cd helm helm create go-web-app-chart

## create from helm using command line 

   helm install go-web-app ./go-web-app-chart

 ## Helm unistall   

 helm uninstall go-web-app
 