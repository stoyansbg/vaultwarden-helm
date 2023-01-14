# vaultwarden
Helm chart for deploying [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) in Kubernetes.


## Installing the Chart

```console
$ helm repo add vaultwarden https://stoyansbg.github.io/vaultwarden-helm/
$ helm upgrade -i vaultwarden vaultwarden/vaultwarden \
    -n vaultwarden \
    -f values.yaml \
    --create-namespace
```

OR

```console
$ git clone https://github.com/stoyansbg/vaultwarden-helm
$ cd vaultwarden-helm
$ helm upgrade -i vaultwarden ./chart/vaultwarden \
    -n vaultwarden \
    --create-namespace

```

## Uninstalling the Chart

```console
$ helm delete vaultwarden -n vaultwarden
```



