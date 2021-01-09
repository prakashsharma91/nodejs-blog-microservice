# Error starting minikube
sudo chmod 776 /var/run/docker.sock

# ErrImagePull
## Run following command before docker build. Rerun on closing the terminal
eval $(minikube docker-env)

# Enabled ingress
minikube addons enable ingress

# skaffold
skaffold dev