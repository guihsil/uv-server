# 🚀 FastAPI + UV + Docker Starter Kit

> A modern, minimal boilerplate for Python web services, pre-configured with uv and Docker for rapid development.

---

## 📌 Table of Contents
* [About the Project](#-about-the-project)
* [Tech Stack](#-tech-stack)
* [Project Structure](#-project-structure)
* [Getting Started](#-getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
* [Usage](#-usage)

---

## 💻 About the Project
This repository serves as a clean skeleton for building Python APIs. Instead of spending time configuring environments every time, I created this starter kit to provide a solid foundation using the latest industry standards.

The focus here is on developer experience: fast dependency resolution with uv and consistent environments with Docker.

### 🛠️ Tech Stack
This project was developed using the following technologies:

| Category | Technology |
|-----------|------------|
| Language | Python |
| Framework | FastAPI |
| Tools | uv |
| Containerization | Docker & Docker Compose |
| Database | PostgreSQL (Ready-to-connect) |

## ✨ Features
- [ ] **Minimal Setup:** A clean "Hello World" FastAPI structure ready to be expanded.
- [ ] **Modern Tooling:** Uses uv for lightning-fast installs (much faster than pip).
- [ ] **Docker Ready:** Includes a Dockerfile and docker-compose.yml for instant deployment.
- [ ] **Environment Isolation:** Pre-configured to work inside containers or local virtualenv



## 🚀 Getting Started

### Prerequisites
* Docker
* Python 3.14+
* uv (if running locally without Docker)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/guihsil/uv-server
2. **Navigate to the project directory:**
    ```bash
    cd uv-server

## 🛠️ Usage 
    docker compose --env-file "env/.env" up
Open http://localhost:8000/
