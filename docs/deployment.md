# Deployment

kubectl apply -f kubernetes/

Verify:

kubectl get pods -n nexoryx-security
kubectl get svc -n nexoryx-security
kubectl get ingress -n nexoryx-security
