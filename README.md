# charts
helm charts

## Crypto Watchdog
```
$ helm repo add hhaluk https://huseyinnurbaki.github.io/charts/
$ helm install crypto-watchdog hhaluk/crypto-watchdog
```
## Mocktail
```
$ helm repo add hhaluk https://huseyinnurbaki.github.io/charts/
$ helm install crypto-watchdog hhaluk/mocktail
```



## Howto:
### Lint

```
$ helm lint hhaluk/*
```
### Package

```
$ helm package hhaluk/*
```
### Merge Index

```
$ helm repo index --url https://huseyinnurbaki.github.io/charts/ --merge index.yaml .
```

> source: https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417