[![GitHub contributors](https://img.shields.io/github/contributors/Nafiros/B-DOP-500-Bernstein-Bootstrap?style=for-the-badge)](https://github.com/Nafiros/B-DOP-500-Bernstein-Bootstrap/graphs/contributors)
[![GitHub forks](https://img.shields.io/github/forks/Nafiros/B-DOP-500-Bernstein-Bootstrap?style=for-the-badge)](https://github.com/Nafiros/B-DOP-500-Bernstein-Bootstrap/network)
[![GitHub stars](https://img.shields.io/github/stars/Nafiros/B-DOP-500-Bernstein-Bootstrap?style=for-the-badge)](https://github.com/Nafiros/B-DOP-500-Bernstein-Bootstrap/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Nafiros/B-DOP-500-Bernstein-Bootstrap?style=for-the-badge)](https://github.com/Nafiros/B-DOP-500-Bernstein-Bootstrap/issues)
[![GitHub license](https://img.shields.io/github/license/Nafiros/B-DOP-500-Bernstein-Bootstrap?style=for-the-badge)](https://github.com/Nafiros/B-DOP-500-Bernstein-Bootstrap)
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="#">
    <img src="https://logos-download.com/wp-content/uploads/2018/09/Kubernetes_Logo-700x356.png" alt="Logo" width="200" height="100">
  </a>

  <h3 align="center">B-DOP-500-Bernstein-Bootstrap</h3>

  <p align="center">
    Bernstein bootstrap - Initiation to Kubernetes
    <br />
    <br />
    <a href="https://github.com/Nafiros/B-DOP-500-Bernstein-Bootstrap/issues">Report Bug</a>
    ·
    <a href="https://github.com/Nafiros/B-DOP-500-Bernstein-Bootstrap/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

Initiation to Kubernetes before Bernstein project
Initiation to Kubernetes for the thrid DevOps project in 3rd year epitech PGE program
Take a look to the .pdf files to try before look at the project solution.


### Built With

* [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
* [minikube](https://minikube.sigs.k8s.io/docs/start/)
* [VirtualBox](https://www.virtualbox.org/) or [VMware](https://www.vmware.com/)
* [Docker-machine](https://docs.docker.com/machine/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

You just need to install kubectl, minikube virtualBox and docker-machine

### Installation

1. Clone the repo
```sh
git clone git@github.com:Nafiros/B-DOP-500-Bernstein-Bootstrap.git
```
2. Start minikube node
```sh
minikube start
```
3. Set context for kubectl to minikube
```sh
kubectl config use-context minikube
```
4. Apply different ressources to minikube 
```sh
kubectl apply -f [filename].yaml
```


<!-- CONTACT -->
## Contact

[![LinkedIn][linkedin-shield]][linkedin-url] 





<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jean-gaillon-954018153/
