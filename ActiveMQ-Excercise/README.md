# Important thing to note

- You must have a service.yml file
- You must have a deployment.yml file

# Deployment steps

to deploy basic pods without self monitoring, run the following cmds
- kubectl apply -f Service.yml
- kubectl apply -f Pods.yml

To deploy with defining how many replicas you want, run the following cmds
- kubectl apply -f Service.yml
- kubectl apply -f ReplicaSet.yml

To deploy with self monitoring and self healing, run the following cmds
- kubectl apply -f Service.yml
-kiubectl apply -f deployment.yml
