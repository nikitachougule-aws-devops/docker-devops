## 🔹 Docker

Docker is an open-source platform that allows developers to build, package, and run applications inside containers.

Containers include:

- Application code  
- Dependencies  
- Libraries  
- Runtime  

👉 This ensures the application runs the same in every environment.

---

## 🔹 Container?

It is a lightweight, standalone package that includes everything needed to run an application.

---

## 🔹Docker Image

It is a blueprint of a container.

It contains:

- Application code  
- Dependencies  
- Instructions to run  

👉 Containers are created from images.

---

## 🔹 Docker Architecture

Docker uses a client-server architecture.

### Components:

- **Docker Client**  
  Where you run commands (e.g., `docker run`)

- **Docker Daemon**  
  Runs in the background and manages containers and images  

- **Docker Registry**  
  Stores Docker images  
  Example: Docker Hub  

---

## 🔹 Docker Workflow

Basic flow:

1. Write a Dockerfile  
2. Build an image  
3. Run a container  

👉 Flow:

Dockerfile → Image → Container


---


---

## 🔹 Real-World Example

**Without Docker:**

- App works on developer machine  
- Fails on server 😓  

**With Docker:**

- Same container runs everywhere ✅  

---

## 🔹 Summary

- Docker simplifies application deployment  
- Containers are lightweight alternatives to VMs  
- Images are used to create containers  
- Helps in DevOps, CI/CD, and cloud deployments  
