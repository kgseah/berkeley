# berkeley

To run this project

# build local image
docker build . -t localhost:5000/berkeley

# Using Build and deploy using docker-compose
docker-compose up -d

# Tear down docker-compose service
docker-compose down

# Deploy in Kuberenetes in local
kubectl create -f service.yaml,deployment.yaml,redis-deployment.yaml,redis-service.yaml

# Tear down deployment and service in k8s
kubectl delete -f service.yaml,deployment.yaml,redis-deployment.yaml,redis-service.yaml

# View result in local
At browser type http://localhost
