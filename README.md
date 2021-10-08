# kube-kustomize
kubectl apply -f argocd-kustomize.yaml

kubectl -n kustomize -k overlay/dev
