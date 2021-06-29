# NGINX - Helm Charts

This repository contains packaged Helm charts provided by NGINX.

## Documentation

https://docs.nginx.com/nginx-ingress-controller/installation/installation-with-helm/

## NGINX Ingress Controller
### Add Repository (stable)

```sh
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

### Add Repository (experimental)

```sh
$ helm repo add nginx-edge https://helm.nginx.com/edge
$ helm repo update
```


### Install Packages (stable)

```sh
$ helm install my-release nginx-stable/nginx-ingress [--version 0.4.1]
```

### Install Packages (experimental)

```sh
$ helm install my-release nginx-edge/nginx-ingress --devel

```

## NGINX Service Mesh

### Add repository
```sh
$ helm repo add nginx-service-mesh https://helm.nginx.com/nginx-service-mesh
$ helm repo update
```

### Install packages
```sh
$ helm install my-release nginx-service-mesh/nginx-service-mesh [--version 0.1.0]
```
