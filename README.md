# architecture-sprint-6
kubectl apply -f Exc2/test-app.yaml
kubectl apply -f Exc2/test-app-service.yaml
kubectl apply -f Exc2/test-app-hpa.yaml

minikube service test-app-service --url

