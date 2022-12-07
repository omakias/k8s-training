kubectl create deployment nginx-pod-osher --image=nginx:alpine --port 80

kubectl create deployment messaging --image=redis:alpine --port 80 -l tier=msg
