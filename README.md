# 🐳 Docker Projects Repository

This repository contains my end-to-end Docker-based projects developed while learning and practicing containerization, DevOps workflows, and microservice-style deployments.

Each project focuses on containerizing applications, connecting services, and exploring CI/CD & reverse proxy setups with Docker.

---

## 🚀 Projects Included
### 1️⃣ **Flask + PostgreSQL CRUD REST API**

A simple backend API built using **Flask** and **PostgreSQL**, containerized with Docker.  
This project demonstrates how to build, run, and manage a REST API without Docker Compose — using manual linking of containers.

**🔧 Features:**
- CRUD operations using Flask REST API  
- PostgreSQL as backend database  
- Database connection via environment variables  
- Dockerfile for Flask app containerization  
- Manual linking between Flask and PostgreSQL containers  

**🧰 Tech Stack:**  
`Python` · `Flask` · `PostgreSQL` · `Docker`

**🧠 Learning Focus:**
- Build Flask image using Dockerfile  
- Connect Flask container to PostgreSQL container  
- Persist data using Docker volumes

---

### 2️⃣ **Full Stack App — Flask + PostgreSQL + NGINX + Frontend**

A complete multi-container setup demonstrating how a real-world web application runs in Docker.
It includes a frontend, backend (Flask), PostgreSQL database, and NGINX reverse proxy.

**🔧 Features:**
- Flask backend connected to PostgreSQL
- Frontend (HTML/CSS/JS) served via NGINX
- Reverse proxy configuration for routing traffic

**🧰 Tech Stack:** 
`NGINX` · `Flask` · `PostgreSQL` · `HTML/CSS/JS`

**🧠 Learning Focus:**
- Setting up reverse proxy using NGINX
- Exposing ports and networking between containers
- Managing environment variables securely











