# helm_charts

## Add helm private repo
```
helm repo add local localhost:5000
```

## Push chart to repo
(https://helm.sh/docs/topics/registries/)
(https://rancher.com/docs/k3s/latest/en/installation/private-registry/)
(https://docs.docker.com/registry/deploying/)
```
helm chart push localhost:5000/local/mychart:2.7.0
```
