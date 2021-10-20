# ReactApp
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
To run this project, install it locally using skaffold and kubernetes:

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
