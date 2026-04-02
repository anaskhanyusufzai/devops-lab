# DevOps Lab - Containerized API with Kubernetes

A hands-on DevOps project demonstrating containerization and Kubernetes deployment of a backend API.

## 🚀 Features
- REST API built with FastAPI
- Docker containerization
- Kubernetes deployment (Minikube)
- Multi-replica scaling
- PostgreSQL integration

## 🧱 Tech Stack
- Python (FastAPI)
- Docker
- Kubernetes
- PostgreSQL

## ⚙️ DevOps Highlights
- Built Docker images for backend services
- Deployed applications using Kubernetes deployments
- Managed pods and services
- Scaled applications using replicas
- Debugged CrashLoopBackOff and database connection issues

## ▶️ Run
```bash
docker build -t devops-lab .
docker run -p 8000:8000 devops-lab
