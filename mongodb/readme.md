#How to run
```
kubectl apply -f mongodb-pv.yaml
kubectl apply -f mongodb-pvc.yaml
kubectl apply -f mongodb-secrets.yaml
kubectl apply -f mongodb-deployment.yaml
kubectl apply -f mongodb-nodeport-svc.yaml
kubectl apply -f mongodb-statefulset.yaml
kubectl apply -f mongodb-ingress.yaml
```