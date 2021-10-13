# RocketChat helm chart
## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```
helm repo add rocketchat https://josesolis2201.github.io/helm-charts/
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.

To install the rocketchat chart:
```
helm install my-rocketchat josesolis2201/rocketchat
```

To uninstall the chart:
```
helm delete my-rocketchat
```