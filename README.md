# Kubernetes with GKE

## Tutorial

1. [From a monolithic app to micro services on GCP Kubernetes](https://bogotobogo.com/DevOps/Docker/Docker-from-Monolithic-to-Micro-services-GCP-Kubernetes.php) 

* Provision a complete Kubernetes using [Google Container Engine](https://cloud.google.com/container-engine)
* Deploy and manage Docker containers using kubectl
* Ports - NodePort, Port, TargetPort
* Service types - NodePort and LoadBalancer
* Managing Applications with Kubernetes

2. [Docker : Deployments to GKE (Rolling update, Canary and Blue-green deployments)](https://bogotobogo.com/DevOps/Docker/Docker-Rolling-Update-Canary-Blue-Green-Deployments-to-GKE-Kubernetes.php) 

* Provision a complete Kubernetes using [Google Container Engine](https://cloud.google.com/container-engine)
* Deploy and manage Docker containers using kubectl
* Managing Deployments with Kubernetes (Rolling update, Canary and Blue-green deployments. Also, roll-back)




[App](https://github.com/kelseyhightower/app) is hosted on GitHub and provides an example 12 Facter application. We will be working with the following Docker images:

* [kelseyhightower/monolith](https://hub.docker.com/r/kelseyhightower/monolith) - Monolith includes auth and hello services.
* [kelseyhightower/auth](https://hub.docker.com/r/kelseyhightower/auth) - Auth microservice. Generates JWT tokens for authenticated users.
* [kelseyhightower/hello](https://hub.docker.com/r/kelseyhightower/hello) - Hello microservice. Greets authenticated users.
* [ngnix](https://hub.docker.com/_/nginx) - Frontend to the auth and hello services.


## Credit
* [googleCode](https://github.com/googlecodelabs/orchestrate-with-kubernetes.git) - Get complete codes
