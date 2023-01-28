# restinthemiddle Helm chart repository

## Add Helm repository

```shell
helm repo add https://restinthemiddle.github.io/helm
helm repo update
```

## Deploy restinthemiddle

```shell
helm install restinthemiddle-example restinthemiddle/restinthemiddle --set='config.targetHostDsn=https://www.example.com'
```

