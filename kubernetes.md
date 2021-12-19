# Kubernetes Tutorial

# Create Cluster on Google Cloud
cloud.google.com -> create account -> kubernetes engine -> create cluster

# Open Cloud Shell on Google Cloud
cloud shell icon -> run the following commands

# Kubernetes Controller
kubeclt

# Deploying Docker image to Cluster
kubectl create deployment imageName --image=dockerHubUsername/imageName:versionOrTag

# Exposing the deployment
kubectl expose deployment deploymentName --type=LoadBalancer --port=8080