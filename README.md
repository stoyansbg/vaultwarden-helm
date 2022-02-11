# vaultwarden
Helm chart for deploying [dani-garcia/bitwarden_rs](https://github.com/dani-garcia/vaultwarden) in Kubernetes.

## TL;DR;

```console
$ helm repo add bitwarden https://constin.github.io/vaultwarden-helm/
$ helm install bitwarden bitwarden/vaultwarden-helm
```

OR

```console
$ git clone https://github.com/constin/vaultwarden-helm
$ cd vaultwarden
$ helm install bitwarden ./chart/vaultwarden-helm
```


## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install my-release bitwarden/vaultwarden-helm
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
$ helm delete my-release
```



