# compunube-proyecto2

## Punto 2

kubectl apply -f kubermatic-dl.yaml

kubectl expose deployment kubermatic-dl-deployment  --type=LoadBalancer --port 80 --target-port 5000


## Punto 3

kubectl apply -f azure-vote.yaml
