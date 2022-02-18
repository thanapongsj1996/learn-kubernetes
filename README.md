kubectl apply -f mongo-deployment.yaml
kubectl apply -f mongo-service.yaml 
kubectl apply -f mongo-express-deployment.yaml 
kubectl apply -f mongo-express-service.yaml 

kubectl get pods
kubectl get pods -o wide
kubectl get services

http://localhost:8081/
