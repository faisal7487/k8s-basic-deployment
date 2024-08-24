# k8s-basic-deployment
A simple container deplyment in kubernetes

Clone the Repo 

#Run the following commands
cd k8s-basic-deployment
kubectl apply -f mongo-config.yaml

kubectl apply -f mongo-secret.yaml

kubectl apply -f mongo.yaml

kubectl apply -f webbapp.yaml
