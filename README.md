### imperative steps:

`ytt -f base/argocd.yaml -f overlays | kubectl apply -n argocd -f -`