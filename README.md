# Kubernetes Operations (Creating Deployment, Service and Ingress)

## Step-01: Create Kubernetes Manifest Files
- Created Deployment manifest file refer to nginx-deployment.yaml
- Created Service manifest file refer to nginx-service.yaml
- Created ingress manifest file refer to ingress.yaml


### Kubernetes CLI commands to apply the above manifests (Deployed in local desktop cluster using Docker Desktop)
    - kubectl apply -f nginx-deployment.yaml
    - kubectl apply -f nginx-service.yaml
    - kubectl apply -f ingress.yaml
    - Alternatively kubectl apply -f . can be used to apply all at once.

### Check the desired kubernetes objects created by above manifests
    - kubectl get deployments (to list the deployment created)
    - kubectl get replicasets (to list the replica sets created)
    - kubectl get services (to list the services created)
    - kubectl get ingress (to list the ingress resources)






