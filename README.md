[![Run on Push](https://github.com/annushramrg03-byte/my-first-repo/actions/workflows/push.yml/badge.svg)](https://github.com/annushramrg03-byte/my-first-repo/actions)
# my-first-repo

My first GitHub repository
I am learning:

* Git
* GitHub
* LINUX
* PYTHON
* SHELL SCRIPTING
* \## Feature Branch Update
  Merged changes from Branch A and Branch B

issue resolved

# 🗳️ Cloud-Native Voting App on AWS EKS

## 🚀 Overview
A full-stack cloud-native voting application deployed on **AWS EKS (Kubernetes)**.  
Users can vote for programming languages, with results stored in a **MongoDB Replica Set**.

---

## 🧱 Architecture

Frontend (React)
↓
Backend API (Go)
↓
MongoDB Replica Set (StatefulSet)

---

## 🛠️ Tech Stack

- Kubernetes (AWS EKS)
- Docker
- React (Frontend)
- Go (Backend API)
- MongoDB (Replica Set)
- AWS (EC2, IAM, EKS)

---

## ⚙️ Features

- Vote for programming languages
- Scalable microservices architecture
- MongoDB high availability (Replica Set)
- Kubernetes StatefulSets & Deployments
- LoadBalancer services for public access

---

## 📦 Kubernetes Components

- Namespace (cloudchamp)
- Deployments (Frontend & API)
- Services (LoadBalancer)
- StatefulSet (MongoDB)
- Persistent Volumes (EBS)
- Secrets (DB credentials)

---

## 🚀 Deployment (Quick Steps)

```bash
# Connect to EKS
aws eks update-kubeconfig --name mycluster --region ap-south-1

# Deploy application
kubectl apply -f .

