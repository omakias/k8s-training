kubectl run nginx-pod-osher --image=nginx:alpine

kubectl run messaging --image=redis:alpine --labels="tier=msg"

kubectl create namespace apx-x998-osher

kubectl get nodes -ojson 

kubectl create service clusterip messaging-service --tcp=6379:6379 

kubectl label service  messaging-service app2=messaging/"tier=msg"

 
