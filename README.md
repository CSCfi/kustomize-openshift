# Kustomize demo

Simple kustomize example for OpenShift.

## Install

```sh
kustomize build overlays/production | kubectl apply -f -
```

# Uninstall

```sh
kustomize build overlays/production | kubectl delete -f -
```

