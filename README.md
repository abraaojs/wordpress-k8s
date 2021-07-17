# Wordpress com EKS Minikube etc.. (Kubernetes)
## How to

Este projeto ajuda você a executar o Wordpress no Kubernetes

### Pré Reque

 - You should run kubernetes cluster and have kubectl commandline access
### Configuration

##### Run Wordpress on Cluster
- > git clone git clone https://github.com/abraaojs/wordpress-k8s
- > kubectl apply -f wordpress-k8s/

##### remove Wordpress from Cluster
- > kubectl delete -f wordpress-k8s/
