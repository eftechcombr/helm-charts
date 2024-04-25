## Usage
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/eftechcombr-wireguard)](https://artifacthub.io/packages/search?repo=eftechcombr-wireguard)

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.



Once Helm has been set up correctly, add the repo as follows:

  helm repo add eftechcombr https://eftechcombr.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
eftechcombr` to see the charts.

To install the wireguard chart:

    helm install wireguard eftechcombr/wireguard

To uninstall the chart:

    helm delete wireguard

