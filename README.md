# restinthemiddle Helm chart repository

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/restinthemiddle)](https://artifacthub.io/packages/search?repo=restinthemiddle)
![GitHub tag (with filter)](https://img.shields.io/github/v/tag/restinthemiddle/helm)

## Add Helm repository

```shell
helm repo add https://restinthemiddle.github.io/helm
helm repo update
```

## Deploy restinthemiddle

```shell
helm install restinthemiddle-example restinthemiddle/restinthemiddle --set='config.targetHostDsn=https://www.example.com'
```
