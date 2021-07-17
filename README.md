# Wordpress com EKS Minikube (Kubernetes)
## How to

Este projeto ajuda você a executar o Wordpress no Kubernetes

### Pré Reque

 - Você deve executar o cluster kubernetes e ter acesso à linha de comando kubectl

##### Run Wordpress on Cluster
- > git clone git clone https://github.com/abraaojs/wordpress-k8s
- > kubectl apply -f wordpress-k8s/

##### remove Wordpress from Cluster
- > kubectl delete -f wordpress-k8s/
