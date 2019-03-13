# NGINX - Helm Charts

This repository contains packaged Helm charts provided by NGINX.

## Add Repo

```console
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

## Install Packages

```console
$ helm install nginx-stable/nginx-ingress
```

## Install Packages (specific version)

```console
$ helm install nginx-stable/nginx-ingress --version 1.4.3
```