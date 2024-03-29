# Helm Charts
Helm charts created by me

## Adding Repository
```
$ helm repo add marxlnfcs https://marxlnfcs.github.io/charts/
$ helm repo update

$ helm search repo marxlnfcs
$ helm install my-release marxlnfcs/<chart>
```

## Charts
| Chart                                                                       | Description                                                      | Url                                           |
|-----------------------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------|
| [Wildduck](https://github.com/marxlnfcs/wildduck-helm)                      | Helm chart for running wildduck in Kubernetes                    | https://github.com/marxlnfcs/wildduck-helm    |
| [7DTD](https://github.com/marxlnfcs/7dtd-helm)                              | Helm chart for running 7dtd in Kubernetes                        | https://github.com/marxlnfcs/7dtd-helm        |
| [PalWorld](https://github.com/marxlnfcs/palworld-helm)                      | Helm chart for running a PalWorld Dedicated Server in Kubernetes | https://github.com/marxlnfcs/palworld-helm    |
| [ByteSafe Community Edition](https://github.com/marxlnfcs/bytesafe-ce-helm) | Helm chart for running bytesafe-ce in Kubernetes                 | https://github.com/marxlnfcs/bytesafe-ce-helm |