# learn-kubernetes
### We can run each compenent separately using docker. It means run each services with its own dependencies in separate containers. Containers are completely isolate environments. Containers are running instance of images.
### Whole process of automatically deploying and manage containers known as container orchestration.
### Kubernetes is a container orchestration technology that manages and deploys thousands od containers in a cluster.
### A node is a worker machine and that is where containers will be launched. 
### A cluster is a set of grouped works together.
### The master watches over the nodes in the cluster and is responsible for the actual orcherstration of containers on the worker node. 
### The containers are encapsulated into a kubernetes object known as pods. It is the smallest object in kubernetes. Pods have a one to one relationship with containers. But a single pod can have multiple containers. They are usually not multiple containers of same kind.
### The replication controller can help by automatically bringing up new pod when the existing one fails. The replication controller ensures that the specify number of pods are running at all time. And also we need replication controllers to create multiple pods to share the load across them.
### The role of the replicaset is to monitor the pods and any of them were to fail, deploy new ones.
### The deployment provides us with the capability to upgrade the underlying instances seamlessly using rolling updates, undo changes, and pause, and resume changes as required.
