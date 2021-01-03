# PREQUISITES FOR RUNNING KUBERNETES (Linux Perspective) :desktop_computer:

- Docker 
- kubectl 
- minikube

# HOW TO RUN :running_man:

- ```minikube start ```
- ```minikube status ``` `To check if working`
- ```kubectl create secret generic pgpassword --from-literal PGPASSWORD=anythinghere```
- ```kubectl apply -f ./k8s ```
- ```minikube ip``` `Copy IP`
-  `Hit the IP from browser`

# ABOUT :metal:

> It's a Fibonacci Calculator

**Client- Reactjs**
**Server- Nodejs**
**DB- Postgres**
**Redis used for caching**



