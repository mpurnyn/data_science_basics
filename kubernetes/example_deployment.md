# check docker
'''sudo systemctl start docker
docker ps'''

# start kubernetes
'''minikube start'''

# check if any pods are running
kubectl get pods

using the yaml file
# start with 
    kubectl apply -f deployment.yaml

# check with 
    kubectl get pod
    
# get really detailed info with 
    kubectl describe pod