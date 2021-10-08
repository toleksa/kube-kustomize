# kube-kustomize

### start
```kubectl -n kustomize -k overlay/dev```

### ArgoCD start dev

```kubectl apply -f argocd-kustomize-dev.yaml```

### ArgoCD switch to prod
```kubectl apply -f argocd-kustomize-prod.yaml```

or manually change repo path from wui
