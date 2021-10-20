# ReactApp
[![npm version](https://badge.fury.io/js/react-native.svg)](https://badge.fury.io/js/react-native)
![kubernetes](https://img.shields.io/badge/Kubernetes-deploy-green)
![code](https://img.shields.io/badge/code-success-green)
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This is a webapp which shows posts and comments on the wall and deployed automatically with kubernetes. 

## Technologies
Project is created with:
* Backend: Express and Node
* Frontend: React
* Deployment: Kubernetes

## Setup
To run this project, first install skaffold, npm and kubernetes on local machine:

```
$ git clone https://github.com/vamsivenkat987/ReactApp.git
$ Change your Docker repo name in every Dockerfile and update same repo in kubernetes yaml file.
windows
$ Install docker desktop for windows and run kubernetes init
$ choco install -y skaffold
$ cd infra/k8s 
$ kubectl apply -f *
$ cd ../..
$ skaffold dev
```
