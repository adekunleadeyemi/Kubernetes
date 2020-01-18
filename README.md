# Kubernetes
Basic understanding and code deployment of kubernetes and deploying this to AWS using terraform.

# BASIC Requirement

- Ensure docker is installed on the environment and running
- Ensure you have minikube installed and running (for MacOS and linuxOS)
- Ensure you have kubectx and kubens installed
- Ensure you have enabled registry credentials in minikube. this is to talk to your aws account.
- Ensure that you have right access to AWS account.

# Hello World Application

- Once the requirement has been met do the following
  - kubectl apply -f deployment.yml
  - kubectl apply -f service.yml
