# TP Automatisation - Flask App with Docker and CI/CD

## Overview
This project is a simple **Flask web application** that lists training courses.  
It is containerized using **Docker** and includes a **CI/CD pipeline** with **GitHub Actions** that automatically builds and tests the app whenever code is pushed to the `main` branch.

---

## Features
- Flask web app serving a homepage (`index.html`)
- Dockerized for easy deployment
- CI/CD pipeline with GitHub Actions
- Health check to ensure the app runs correctly

---

## Project Structure
TP_Automatisation/
├─ app.py
├─ Dockerfile
├─ requirements.txt
├─ templates/
│ └─ index.html
└─ .github/
└─ workflows/
└─ ci.yml



---

## Prerequisites
- Python 3.11+  
- Docker  
- Git

---

## Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/SanaeBouazzah/ProjectAutomation.git
cd tp_automatisation

