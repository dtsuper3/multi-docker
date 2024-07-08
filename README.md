 kind create cluster --config kind.yml --name local

kubectl apply -f deployment.yml

kubectl get deployment
kubectl get rs
kubectl get pods

kubectl delete deployment {name}


kubectl get services
kubectl delete services {name}


