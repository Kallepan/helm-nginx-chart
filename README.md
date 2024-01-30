# Helm Nginx Chart

A simple Helm chart to deploy a Nginx web server. This chart is based on the [stable/nginx-stable](https://github.com/nginxinc/helm-charts) chart.

## Prerequisites

- Kubernetes 1.12+
- Helm 3.0.0+


## Installing the Chart
```bash
helm install nginx-release nginx

kubectl port-forward svc/nginx-svc 8080:80
```