# kube-kustomize

### start
```kubectl apply -f argocd-kustomize-dev.yaml```

```kubectl -n kustomize -k overlay/dev```

### switch to prod
```kubectl apply -f argocd-kustomize-prod.yaml```

or manually change repo path
