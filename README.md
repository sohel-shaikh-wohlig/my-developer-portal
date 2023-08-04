# [Backstage](https://backstage.io)

Internal Development Platform

To start the app, run:

```sh
source environment.sh
yarn install
yarn dev
```

### Start Kubernetes API Server
kubectl proxy --port=8433

### Start ArgoCD 
kubectl port-forward svc/argocd-server -n argocd 8080:443
