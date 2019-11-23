# cloud-native-guide

Cloud Native
---


Kubernetes
---
Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation.  

### Concepts


**Master:** The machine that controls Kubernetes nodes. This is where all task assignments originate. 

**Node:** These machines perform the requested, assigned tasks. The Kubernetes master controls them.

**Pod:** A group of one or more containers deployed to a single node. All containers in a pod share an IP address, IPC, hostname, and other resources. Pods abstract network and storage away from the underlying container. This lets you move containers around the cluster more easily.

**Container:** A lightweight and portable executable image that contains software and all of its dependencies.
Containers decouple applications from underlying host infrastructure to make deployment easier in different cloud or OS environments, and for easier scaling.

**Control Plane:** The container orchestration layer that exposes the API and interfaces to define, deploy, and manage the lifecycle of containers.
**Data Plane:** The layer that provides capacity such as CPU, memory, network, and storage so that the containers can run and connect to a network. 


**Cluster:** A set of machines, called nodes, that run containerized applications managed by Kubernetes. A cluster has at least one worker node and at least one master node. The worker node(s) host the pods that are the components of the application. The master node(s) manages the worker nodes and the pods in the cluster. Multiple master nodes are used to provide a cluster with failover and high availability. 

**Replication controller:**  This controls how many identical copies of a pod should be running somewhere on the cluster.

**Service:** This decouples work definitions from the pods. Kubernetes service proxies automatically get service requests to the right pod—no matter where it moves to in the cluster or even if it’s been replaced.

**Kubelet:** This service runs on nodes and reads the container manifests and ensures the defined containers are started and running.

**kube-proxy:** kube-proxy is a network proxy that runs on each node in your cluster, implementing part of the Kubernetes Service concept. kube-proxy maintains network rules on nodes. These network rules allow network communication to your Pods from network sessions inside or outside of your cluster. 

**kubectl:** This is the command line configuration tool for Kubernetes.

### Local Deployment

### Deployment Strategies





## Openshift

### Concepts

### Local Deployment

### Deployment Strategies

## AWS

### Concepts





## References
* https://kubernetes.io/docs/home/
