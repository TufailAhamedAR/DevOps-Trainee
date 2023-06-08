Set up a Kubernetes cluster:

To set Kubernetes cluster i have installed kubectl in Docker Desktop


Deploy MongoDB to Kubernetes:

Create a Kubernetes deployment and service for MongoDB.

--> mongo-deployment.yaml

--> mongo-services.yaml


Deploy MongoDB using the following commands:

kubectl apply -f mongo-deployment.yaml

kubectl apply -f mongo-service.yaml


Deploy the application to Kubernetes:

Create a deployment and service for the application in Kubernetes.

-->app-deployment.yaml

-->app-service.yaml


Deploy the application using the following commands:

kubectl apply -f app-deployment.yaml

kubectl apply -f app-service.yaml


Verify the deployment:

Check the status of your deployments and services using the following commands:

kubectl get deployments

kubectl get services

The application is now deployed in Kubernetes with MongoDB, and you can access it from within the cluster using the appropriate service name and port.


