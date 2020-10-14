# Kubernetes configuration for Dice-Game
 
## To install application follow the instructions

### Requirements

* Installed and configured Kubernetes on your OS. In this guide I will only show how to deploy applications in Kubernetes.
* Installed GIT on the same OS when Kubernetes is installed

### 1. Download this git project
``` bash
git clone https://github.com/Bartosz95/zyj-game-kubernetes-configuration.git
```

### 2. Change directory to this project
``` bash
cd dice-game-kubernetes-configuration/
```

## There are several way to install this application

### Install manually
#### 1. Install
##### Pods
``` bash
kubectl create -f dice-game-pods/*
```
##### Services
``` bash
kubectl create -f dice-game-services/*
```
#### 2. Check status
``` bash
kubectl get all
```
#### You should get something like this:
(...)
### Install by deployment:
(...)

