# Kubernetes with GKE

You will learn how to:

* Provision a complete Kubernetes using [Google Container Engine](https://cloud.google.com/container-engine)
* Deploy and manage Docker containers using kubectl

Kubernetes Version: 1.2.2

## Setup GCE and Enable Cloud Shell 

## Provision Kubernetes using GKE

## Managing Applications with Kubernetes

[App](https://github.com/kelseyhightower/app) is hosted on GitHub and provides an example 12 Facter application. We will be working with the following Docker images:

* [kelseyhightower/monolith](https://hub.docker.com/r/kelseyhightower/monolith) - Monolith includes auth and hello services.
* [kelseyhightower/auth](https://hub.docker.com/r/kelseyhightower/auth) - Auth microservice. Generates JWT tokens for authenticated users.
* [kelseyhightower/hello](https://hub.docker.com/r/kelseyhightower/hello) - Hello microservice. Greets authenticated users.
* [ngnix](https://hub.docker.com/_/nginx) - Frontend to the auth and hello services.


## Credit
* [googleCode](https://github.com/googlecodelabs/orchestrate-with-kubernetes.git) - Get complete codes
