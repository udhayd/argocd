# Argo CD Chart

A Helm chart for ArgoCD, a declarative, GitOps continuous delivery tool for Kubernetes.

Source code can be found [here](https://argoproj.github.io/argo-cd/)


## Prerequisites

- Kubernetes 1.7+
- Helm v3.0.0+

## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ cd chart/

$ helm dep update

$ helm install --name my-release . -n argocd

```
