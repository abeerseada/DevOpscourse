kubectl create ns python-app-namespace
kubectl apply -n python-app-namespace -f Kubernetes/Minikube\ /k8s-python-app 
minikube service -n python-app-namespace python-app-service --url
