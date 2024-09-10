1. Install EKS
Please follow the prerequisites doc before this.


eksctl create cluster --name demo-cluster --region us-east-1 
eksctl create cluster --name demo-cluster --version 1.30 --node-type t3.micro --nodes 2

2. Delete the cluster
eksctl delete cluster --name demo-cluster --region us-east-1