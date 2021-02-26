# Deploy RabbitMQ Cluster on Kubernetes

1. kubectl create ns rabbitmqns
1. kubectl apply -n rabbitmqns -f 1-rbac.yml
1. kubectl apply -n rabbitmqns -f 2-configmap.yml
1. kubectl apply -n rabbitmqns -f 3-secret.yml
1. kubectl apply -n rabbitmqns -f 4-statefulset.yml
1. kubectl apply -n rabbitmqns -f 5-service.yml
