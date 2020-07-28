# helm_charts

## Add helm private repo
```
helm repo add local localhost:5000
```

## Push chart to repo
* [Helm registries](https://helm.sh/docs/topics/registries/)
* [k3s registries](https://rancher.com/docs/k3s/latest/en/installation/private-registry/)
* [Docker registry image](https://docs.docker.com/registry/deploying/)
```
helm chart push localhost:5000/local/mychart:2.7.0
```

## Install chart
```
helm install dfsfdfsfdfsdf TODO:
```

## Uninstall chart
```
helm sdfdfdfsd TODO:
```
