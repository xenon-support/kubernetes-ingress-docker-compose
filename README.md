# part 1
checkout branch part1

This belongs to this article: https://medium.com/@wuestkamp/replicate-kubernetes-ingress-locally-with-docker-compose-2872e650af6b

This project shows on a simple example how to simulate a Kubernetes Ingress using Docker Compose for local development.


## setup kubernetes infrastructure
`kubectl apply -f k8s`

### create ingress resource in cluster
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.24.1/deploy/mandatory.yaml
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.24.1/deploy/provider/cloud-generic.yaml
kubectl get svc --namespace=ingress-nginx
```

# part 2
checkout branch part2

coming up: implement https in Kubernetes and Docker Compose

