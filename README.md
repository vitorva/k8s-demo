# k8s-demo

This project is a simple web application connected to a NoSQL MongoDB database, and it utilizes Kubernetes for container orchestration. It was created as part of my learning journey to gain a basic understanding of Kubernetes.

## Prerequisites

Before you can run this project, make sure you have the following installed:

- Docker: for containerization of the application
- Kubernetes: for container orchestration
- Minikube: for running Kubernetes locally on your machine

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Start Minikube on your local machine using the following command: minikube start.
4. Deploy the application to Kubernetes using the following command: kubectl apply -f <file_name>.
5. Verify that the application pods are running using the following command: kubectl get pods. You should see the pods in a "Running" state.

**Note:** If you're running on Windows you have to run `minikube service webapp-service` which will create a tunnel to the service via ports published by minikube container and redirect the browser to tunneled port.

## Technologies Used

- Kubernetes: for container orchestration
- Docker: for containerization
- MongoDB: for the NoSQL database
- Minikube: for running Kubernetes locally

## Acknowledgements

I would like to express my gratitude to [this online tutorial](https://www.youtube.com/watch?v=s_o8dwzRlu4) that provided the guidance and knowledge needed to complete this project. The tutorial was invaluable in helping me learn the basics of Kubernetes and how to deploy a web application using Docker containers and Kubernetes.
