# NGINX - Helm Charts

This repository contains packaged Helm charts provided by NGINX:

- [NGINX Ingress Controller](#nginx-ingress-controller)
- [NGINX Service Mesh](#nginx-service-mesh)
- [NGINX App Protect DoS Arbitrator](#nginx-app-protect-dos-arbitrator)
- [NGINX Management Suite](#nginx-management-suite)
- [NGINX ACM Developer Portal](#nginx-acm-developer-portal)


## Add Repository

```sh
$ helm repo add nginx-stable https://helm.nginx.com/stable
$ helm repo update
```

## Install Packages

### NGINX Ingress Controller

```sh
$ helm install my-release nginx-stable/nginx-ingress [--version 0.17.1]
```

#### Documentation

https://docs.nginx.com/nginx-ingress-controller/installation/installation-with-helm/

### NGINX Service Mesh

```sh
$ helm install my-release nginx-stable/nginx-service-mesh --namespace nginx-mesh --create-namespace
```

#### Documentation

https://docs.nginx.com/nginx-service-mesh/get-started/install-with-helm/

### NGINX App Protect DoS Arbitrator

```sh
$ helm install my-release nginx-stable/nginx-appprotect-dos-arbitrator [--version 0.1.0]
```

#### Documentation

https://github.com/nginxinc/nap-dos-arbitrator-helm-chart

### NGINX Management Suite

```sh
$ helm install nms nginx-stable/nms [--version 1.1.1]
```

#### Documentation

https://docs.nginx.com/nginx-management-suite/admin-guides/installation/kubernetes/nms-helm/

### NGINX ACM Developer Portal

```sh
$ helm install nms nginx-stable/nginx-devportal [--version 1.4.0]
```

#### Documentation

https://docs.nginx.com/nginx-management-suite/admin-guides/installation/kubernetes/devportal-helm-chart/
