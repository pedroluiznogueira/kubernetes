# Kubernetes Tutorial

# Kubernetes Controller
kubeclt

# Deploying Docker image to Cluster
kubectl create deployment imageName --image=dockerHubUsername/imageName:versionOrTag

# Exposing the deployment
kubectl expose deployment deploymentName --type=LoadBalancer --port=8080