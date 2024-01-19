### Containers in the cloud

#### Introduction to containers
Conainers are a userfull resource in the infrastructure as a service (IaaS), but they can be considered as small platform as a service (PaS). They provide independant os level virtualization to package a software. In that way, they offer isolation, configuration and fast deployment. 

#### Kubernetes
Kubernetes is an open-platform for managing containerized worloads and service. Simply, it can be seen as a container orchestrator. It is composed of :
* **pods** : a pod is the smallest unit that can be deployed in Kubernetes ; there is generaly one container per pod ; but several containers with strong dependcies can be managed within a single pod ;
* **deployment** : a deployment is group of replicas of the same pod, it keeps the pods running even when the nodes they run on commes to fail ;
* **service** : a service is what allow the pods within a cluster to be accessed by defininf different sets of policies ; for example, creating a fixed IP adress or setting up a network loadbalancer ; 

#### Google Kubernetes Engine (GKE)
GKE is a google hosted and managed Kubernetes service in the cloud.
