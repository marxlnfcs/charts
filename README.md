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
| Chart                                                                       | Description                                      | Url                                           |
|-----------------------------------------------------------------------------|--------------------------------------------------|-----------------------------------------------|
| [Wildduck](https://github.com/marxlnfcs/wildduck-helm)                      | Helm chart for running wildduck in kubernetes    | https://github.com/marxlnfcs/wildduck-helm    |
| [7DTD](https://github.com/marxlnfcs/7dtd-helm)                              | Helm chart for running 7dtd in kubernetes        | https://github.com/marxlnfcs/7dtd-helm        |
| [ByteSafe Community Edition](https://github.com/marxlnfcs/bytesafe-ce-helm) | Helm chart for running bytesafe-ce in kubernetes | https://github.com/marxlnfcs/bytesafe-ce-helm |