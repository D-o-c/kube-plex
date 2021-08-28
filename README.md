## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```code
  helm repo add kube-plex https://munnerz.github.io/kube-plex-helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.  You can then run `helm search repo kube-plex` to see the charts.

To install the kube-plex chart:

```code
    helm install kube-plex kube-plex/kube-plex
```

To uninstall the chart:

```code
    helm delete kube-plex
```
