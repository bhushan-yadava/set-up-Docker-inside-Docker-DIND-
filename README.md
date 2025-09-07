# 🚀 Docker-in-Docker (DIND) Setup

This project demonstrates a **Docker-in-Docker (DIND)** setup using Docker Compose, allowing you to run Docker inside a Docker container.  
This is useful for use cases like CI/CD pipelines, integration testing, and automation where Docker commands need to run in an isolated environment.

---

## ✅ Project Overview

### What is Docker-in-Docker (DIND)?
Docker-in-Docker means running a full Docker daemon inside a container.  
This enables running, building, and managing containers from within another container.

---

## 🎯 Why Use This Setup?

- ✅ Automate container builds and tests in CI/CD pipelines (GitLab CI, Jenkins).
- ✅ Test containerized applications in isolation.
- ✅ Avoid installing Docker directly on your host machine.
  
---

## ⚡ Features

- Uses official `docker:dind` image.
- Easy setup via Docker Compose.
- Exposes Docker daemon over TCP for external connections.
- Simple and reusable for multiple projects.
  
---

