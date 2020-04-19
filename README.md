# Kubernetes
Basic understanding and code deployment of kubernetes and deploying this to AWS using terraform.

# BASIC Requirement

- Ensure docker is installed on the environment and running
- Ensure you have minikube installed and running (for MacOS and linuxOS)
- Ensure you have kubectx and kubens installed
- Ensure you have enabled registry credentials in minikube. this is to talk to your aws account.
- Ensure that you have right access to AWS account.

# Introduction

- Once the basic requirement has been met do the following
  - copy the files in the introduction directory to your local environment
  - ensure that your minikube is running by doing "minikube status" and ensure that it is running
  - Run "kubectl apply -f firstPod.yml"
  - Run "kubectl apply -f firstService.yml"
