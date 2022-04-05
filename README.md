# Jade Shooter Game Application for Kubernetes

1. Get a Kubernetes cluster

2. Connect to the cluster using `kubectl`

- For OpenShift
3. `oc create -f https://raw.githubusercontent.com/ksingh7/jade-shooter-app/main/jade-shooter-aio.yaml `
4. `oc expose svc/jade-shooter-service`

- For Kubernetes
  
3. Clone this repo 

`git clone https://github.com/ksingh7/jade-shooter-app.git`

4. Apply the manifests in this repo 
 
    `kubectl apply -f jade-shooter-app/yamls`

5. Get resources 
```
kubectl get all
kubectl get ingress
```

6. Open the ingress route in browser

7. Enjoy the game
