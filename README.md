# helm charts 
This repository contains Helm charts that can be used to deploy various operators and CRDs on Kubernetes.

## Getting Started
To use this Helm chart repository, you'll need to have Helm installed on your local machine or Kubernetes cluster. If you don't have Helm installed, you can follow the official Helm installation guide here: https://helm.sh/docs/intro/install/

Once Helm is installed, you can add this repository to your Helm configuration using the following command:

```
helm repo add sevenport-repo https://sevenport-labs.github.io/helm-charts/
```

## Charts
This repository currently contains the following Helm charts:

- **kudremukh-operator**: A Pod reconciler operator. Charts here can be used to deploy `kudremukh-operator` on Kubernetes.

## Installing Charts
You can install charts from this repository using the helm install command. For example, to install `kudremukh-operator`, you can use the following:

```
helm install kudremukh-operator sevenport-repo/helm-charts -n <namespace>
```
## Contributing
If you'd like to contribute to this Helm chart repository, you can fork the repository, make changes, and submit a pull request. Please make sure to follow the Helm chart development best practices and provide a clear description of your changes in your pull request.

## Issues and Support
If you encounter any issues or have questions about this Helm chart repository, please open an issue in the GitHub repository or contact the maintainer for support.

## License
This Helm chart repository is licensed under the MIT License.