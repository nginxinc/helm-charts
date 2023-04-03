# NGINX - Helm Charts

This repository contains packaged Helm charts provided by NGINX:

- NGINX Ingress Controller
- NGINX Service Mesh
- NGINX App Protect DoS Arbitrator
- NGINX Management Suite


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
$ helm install my-release nginx-stable/nginx-service-mesh --namespace nginx-mesh --create-namespace
```

## NGINX App Protect DoS Arbitrator

### Documentation

https://docs.nginx.com/nginx-ingress-controller/installation/installation-with-helm/

### Add repository
```sh
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

### Install packages
```sh
$ helm install my-release nginx-stable/nginx-appprotect-dos-arbitrator [--version 0.1.0]
```

## NGINX Management Suite

### Documentation

https://docs.nginx.com/nginx-management-suite/admin-guides/installation/kubernetes/nms-helm/

### Add repository
```sh
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

### Install packages
```sh
$ helm install nms nginx-stable/nms [--version 1.1.1]
```

## NGINX ACM Developer Portal

### Documentation

https://docs.nginx.com/nginx-management-suite/admin-guides/installation/kubernetes/devportal-helm-chart/

### Add repository
```sh
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

### Install packages
```sh
$ helm install nms nginx-stable/nginx-devportal [--version 1.4.0]
```
