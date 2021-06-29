# NGINX - Helm Charts

This repository contains packaged Helm charts provided by NGINX.
## NGINX Ingress Controller

### Documentation

https://docs.nginx.com/nginx-ingress-controller/installation/installation-with-helm/

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

### Documentation

https://docs.nginx.com/nginx-service-mesh/get-started/install-with-helm/

### Add repository
```sh
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

### Install packages
```sh
$ helm install my-release nginx-stable/nginx-service-mesh --namespace nginx-mesh --create-namespace [--version 0.1.0]
```
