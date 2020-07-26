# helm_charts

## Add helm private repo
```
helm repo add papapumpnz https://papapumpnz.github.io/helm_charts/
```

## Push chart to repo
https://helm.sh/docs/topics/registries/
```
helm chart push localhost:5000/myrepo/mychart:2.7.0
```
