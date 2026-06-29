# 🚀 Node.js Todo App with Docker & Jenkins CI/CD

A simple **Todo List** application built with **Node.js** and **Express**, containerized using **Docker**, and deployed through a **Jenkins CI/CD pipeline**.

## ✨ Features

* ✅ Create, edit, and delete todos
* 🐳 Dockerized application
* 📦 Docker Compose deployment
* 🔄 Automated CI/CD using Jenkins
* ☁️ Docker Hub image publishing

## 🛠️ Tech Stack

* Node.js
* Express.js
* Docker
* Docker Compose
* Jenkins

## 📁 Project Structure

```text
.
├── app.js
├── Dockerfile
├── docker-compose.yaml
├── Jenkinsfile
├── package.json
└── views/
```

## ▶️ Getting Started

### Build Docker Image

```bash
docker build -t node-app .
```

### Run Container

```bash
docker run -d -p 8000:8000 node-app
```

### Or Run with Docker Compose

```bash
docker compose up -d
```

🌐 Open your browser and visit:

```text
http://localhost:8000/todo
```

## ⚙️ Jenkins CI/CD Pipeline

The pipeline automates the following tasks:

* 📥 Clone the repository
* 🔨 Build the Docker image
* 📤 Push the image to Docker Hub
* 🚀 Deploy the application using Docker Compose

## 📸 Application

After deployment, the Todo application is available at:

```text
http://localhost:8000/todo
```

## 👨‍💻 Author

**Shashank Kanade**
