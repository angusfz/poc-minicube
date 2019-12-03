# poc-minicube

## Install tools (MAC)

```shell
$ brew update && brew install minikube
```

## Start k8s cluster with virutalbox

```shell
# Start a cluster using the virtualbox driver
$ minikube start --vm-driver=virtualbox

# To make virtualbox the default driver
$ minikube config set vm-driver virtualbox

```
