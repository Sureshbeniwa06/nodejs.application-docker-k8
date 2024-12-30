# nodejs.application-docker-k8
............................................................................................................


# Project Prerequisites


     Docker installed
     
     Kubernetes cluster
     
     Node.js environment
     
     Basic understanding of containerization
     
# steps to follow nodejs.application  & create a cluster 

     Key Deployment Stages:

    1.Create Node.js Application
      Create a simple Express.js application

    2.Create Dockerfile Configuration

    3.Create deployment.yaml

    4.Create service.yaml

# Commands to follow:

  
# Build Docker image
docker build -t your-dockerhub-username/nodejs-app .

# Push to Docker Hub
docker push your-dockerhub-username/nodejs-app

# Deploy to Kubernetes
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

# check deployments
kubectl get deployments

# to check pods 
kubectl get pods

# get services
kubectl get services

# to run service on localhost:
minikube service <service name>


--------------------------------------------------------------------------------------------------------------------------

# Installing Dependencies with package.json
  Steps to Install Dependencies
   Initialize Project
   Run the following command to create a package.json file

### 
     npm init -y

# To check dependencies and install it: 

    npm install
 

