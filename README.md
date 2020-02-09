# berkeley

To run this project

# Using Build and deploy using docker-compose
docker-comppose up -d

# To build and Deploy in Kuberenetes in local
docker build . -t localhost:5000/berkeley
kubectl create -f service.yaml,deployment.yaml,redis-deployment.yaml,redis-service.yaml

# View result in local
At browser type http://localhost
