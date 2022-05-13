# Kubernetes

## what
A useful tool for scaling systems, microservice architectures, and decoupling of applications
starts containers and manages state

# prereqs
linus cmd line, yaml, docker, and containerization

# K8 Cluster

# Cluster
A Cluster is
Made of Nodes which are
made of Pods
Pods are the smallest working unit.

# Master Node
A special Master Node is the sole interface and controlls the the Nodes the Scheduler

# Scheduler
Assign pods to nodes according to available resources in a logical structure

# API Server
To change the nodes you send an object to the Master Nodes API Server (Rest API)
the object is a representation of the desired state (called "spec") of the nodes.
Master Nodes Controller monitors the state and brings the cluster from the state to the spec.

the spec can denote
which pods are running and which nodes
how much compute resources are available
other things

# Worker Nodes 
nodes minimum processes
- kubelet - main brain that checks the health state of containers and updates them to spec and
- container runtime (usually docker)
- kube-proxy - controlls network and 

## Pods
have at least one container
does the work
