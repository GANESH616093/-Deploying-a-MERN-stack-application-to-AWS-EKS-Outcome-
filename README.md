# -Deploying-a-MERN-stack-application-to-AWS-EKS-Outcome-
Deploying a MERN stack application to AWS EKS involves containerizing the application and running it on a managed Kubernetes cluster for scalable and resilient deployment. This project provides hands-on experience with Kubernetes concepts, container orchestration, and AWS cloud infrastructure management.


##  Project Overview

This project demonstrates how to deploy a full-stack **MERN (MongoDB, Express, React, Node.js)** application on **AWS Elastic Kubernetes Service (EKS)**. It focuses on containerization, orchestration, and cloud deployment using Kubernetes.

---

##  Objective

To gain an in-depth understanding of:

* Kubernetes architecture and components
* Containerization using Docker
* Deployment and scaling using AWS EKS
* Managing cloud-native applications

---

##  Tech Stack

* **Frontend:** React.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Containerization:** Docker
* **Orchestration:** Kubernetes
* **Cloud Platform:** AWS EKS

---

##  Features

* Full-stack MERN application deployment
* Dockerized frontend and backend services
* Kubernetes deployments and services
* Load balancing and scaling support
* Cloud-based infrastructure using AWS

---

##  Architecture

1. React frontend served via Kubernetes service
2. Node.js backend APIs deployed in pods
3. MongoDB database (local or cloud-hosted)
4. Docker containers for each service
5. Kubernetes manages deployment, scaling, and networking
6. AWS EKS hosts the Kubernetes cluster

---

##  Deployment Steps (High-Level)

1. Build Docker images for frontend and backend
2. Push images to a container registry (e.g., Docker Hub)
3. Create an EKS cluster on AWS
4. Configure `kubectl` to connect to the cluster
5. Deploy application using Kubernetes YAML files
6. Expose services using LoadBalancer

---

##  Project Structure

```
project-root/
│── frontend/        # React application
│── backend/         # Node.js + Express APIs
│── k8s/             # Kubernetes YAML files
│── Dockerfile       # Container configurations
│── README.md
```

---

##  Learning Outcomes

* Practical knowledge of Kubernetes deployment
* Hands-on experience with AWS EKS
* Understanding microservices architecture
* Experience with container-based development
* Cloud infrastructure and scaling concepts

---

##  Conclusion

This project provides real-world experience in deploying scalable applications using Kubernetes on AWS. It bridges the gap between development and cloud deployment, preparing you for roles in **DevOps and Cloud Engineering**.

---

## Author
Ganesh J


