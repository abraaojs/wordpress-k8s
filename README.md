Wordpress com EKS Minikube (Kubernetes)
How to:
Este projeto ajuda você a executar o Wordpress no Kubernetes

Pré Reque:
Você deve executar o cluster kubernetes e ter acesso à linha de comando kubectl
Configuração
Execute o Wordpress no cluster
git clone https://github.com/abraaojs/wordpress-k8s

kubectl apply -f wordpress-with-k8s /

remove Wordpress do cluster
kubectl delete -f wordpress-with-k8s /