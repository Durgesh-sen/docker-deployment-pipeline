# Docker Deployment Pipeline

A simple Flask application containerized using Docker and managed with Docker Compose. This project demonstrates the basics of containerization and serves as a foundation for a complete DevOps CI/CD pipeline.

---

## 🚀 Features

- Dockerized Flask Application
- Docker Compose Support
- Custom Dockerfile
- Deployment Script
- Ready for GitHub Actions
- Ready for AWS EC2 Deployment

---

## 📁 Project Structure

```
.
├── Dockerfile
├── README.md
├── app
│   ├── app.py
│   └── requirements.txt
├── docker-compose.yml
└── scripts
    └── deploy.sh
```

---

## 🛠️ Tech Stack

- Python
- Flask
- Docker
- Docker Compose
- Git
- GitHub

---

## ▶️ Run Locally

### Build the Docker Image

```bash
docker build -t flask-app .
```

### Run the Container

```bash
docker run -d -p 5000:5000 flask-app
```

### Using Docker Compose

```bash
docker-compose up --build
```

---

## 🌐 Access the Application

Open your browser and visit:

```
http://localhost:5000
```

---

## 📌 Future Improvements

- GitHub Actions CI Pipeline
- Docker Hub Integration
- AWS EC2 Deployment
- Automatic Docker Image Build
- Nginx Reverse Proxy

---

## 👨‍💻 Author

**Durgesh Sen**

Learning DevOps through hands-on projects.
