# NGINX - Helm Charts

This repository contains packaged Helm charts provided by NGINX.

## Add Repository (stable)

```sh
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

## Add Repository (experimental)

```sh
$ helm repo add nginx-edge https://helm.nginx.com/edge
$ helm repo update
```

## Install Packages (stable)

```sh
# Helm 2.x client
$ helm install --name my-release nginx-stable/nginx-ingress [--version 0.4.1]

# Helm 3.x client
$ helm install my-release nginx-stable/nginx-ingress [--version 0.4.1]
```

## Install Packages (experimental)

```sh
# Helm 2.x client
$ helm install --name my-release nginx-edge/nginx-ingress --devel

# Helm 3.x client
$ helm install my-release nginx-edge/nginx-ingress --devel
```