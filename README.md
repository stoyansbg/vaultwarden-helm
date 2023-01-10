# vaultwarden
Helm chart for deploying [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) in Kubernetes.


## Installing the Chart
<!-- 
```console
$ helm repo add vaultwarden https://stoyansbg.github.io/vaultwarden-helm/
$ helm install vaultwarden vaultwarden/vaultwarden \
    -n vaultwarden \
    --create-namespace
```

OR -->

```console
$ git clone https://github.com/stoyansbg/vaultwarden-helm
$ cd vaultwarden-helm
$ helm install vaultwarden ./chart/vaultwarden \
    -n vaultwarden \
    --create-namespace

```

## Uninstalling the Chart

```console
$ helm delete vaultwarden -n vaultwarden
```



