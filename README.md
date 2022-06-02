# Install flow.ci from helm

To install the Helm Chart from our Helm Repository, you can use the following commands:

```bash
helm repo add flow.ci https://flowci.github.io/helm-chart/
helm repo update

kubectl create ns flowci
helm install flow.ci flow.ci/flow.ci -n flowci
```