TASK #1


Create automation mechanism to deploy Magento in kubernetes cluster 

Used Minikube Cluster To Deploy Magento. Two Pods will be created for both Mysql and Magento separately.   

Scripts Used:

minikube start --cpus 4 --memory 10240


minikube addons enable ingress


minikube dashboard 


kubectl apply -f secret.yaml


kubectl apply -f magento-deployment.yaml


kubectl apply -f mysql-deployment.yaml


kubectl get all 


kubectl get svc


minikube service magento (service name) will run the magento application


TASK #2

Write a GitLab ci pipeline yaml to deploy scripts/template/deployment files on
an on-prem k8s cluster.



Included the .gitlab-ci.yml to Buid And Deploy on GKE.
