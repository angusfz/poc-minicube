# poc-minicube

## Install tools (MAC)

```bash
$ brew update && brew install minikube
```

## Start k8s cluster with virutalbox

```bash
# Start a cluster using the virtualbox driver
$ minikube start --vm-driver=virtualbox

# To make virtualbox the default driver
$ minikube config set vm-driver virtualbox

```


## Misc

```bash
# Tunnel makes services of type LoadBalancer accessible on localhost
$ minikube tunnel 
```
