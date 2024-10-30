This is a kubernetes cluster Powered by TrueCharts ClusterTool

## Flux List Repositories

```
flux get sources git -A
```

## Flux Force Refresh Repository

```
flux reconcile source git cluster -n flux-system
```

## Describe HelmRelease

```
kubectl describe helmrelease clusterissuer -n clusterissuer
```