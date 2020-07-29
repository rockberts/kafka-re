# kafka-re


from: https://www.magalix.com/blog/kafka-on-kubernetes-and-deploying-best-practice

kubectl apply -f kafka-deployment-re.yaml
kubectl apply -f zoo_deployment_re.yaml
kubectl apply -f zoo_service_re.yaml
kubectl apply -f kafka-service-re.yaml
