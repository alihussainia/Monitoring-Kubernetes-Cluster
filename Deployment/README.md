# Creating Deployments

Step#1: Analyze YAML manifest:

`cat deployment.yml`

Step#2: Deploy the manifest:

`kubectl apply -f deployment.yml`

Step#3: Check deployment:

`kubectl get deploy`

Step#4: Check pods:

`kubectl get pods`

Step#5: Create service:

`kubectl apply -f service.yml`

Step#6: Check service:

`kubectl get svc`

