# NGINX - Helm Charts

This repository contains packaged Helm charts provided by NGINX.

## Add Repository (stable)

```console
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

## Add Repository (experimental)

```console
$ helm repo add nginx-edge https://helm.nginx.com/edge
$ helm repo update
```

## Install Packages (stable)

```console
$ helm install nginx-stable/nginx-ingress
```

## Install Packages (experimental)

```console
$ helm install nginx-edge/nginx-ingress
```

## Install Packages (specific version)

```console
$ helm install nginx-stable/nginx-ingress --version <chart_version>
```