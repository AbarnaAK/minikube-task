*Step 1: Install Prerequisites
  1)Docker
  2)kubectl
  3)Minikube
*Step 2: Start Minikube Cluster
*Step 3: Verify Minikube Status
**Step 4: Explore Namespaces
*Pod file created
*View Resources in a Namespace
Pod.yaml
apiVersion: v1
kind: Pod
metadata:
  name: nginx-pod
  labels:
    app: nginx
    tier: dev
spec:
  containers:
  - name: nginx-container
    image: nginx
    

