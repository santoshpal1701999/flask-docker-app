# Flask Docker Application

This project demonstrates how to dockerize a Python Flask application using Docker Desktop.

## Prerequisites
- Docker Desktop
- Python (optional for local testing)

## Build Docker Image
```bash
docker build -t flask-docker-app .

Run Docker Container

docker run -p 5000:5000 flask-docker-app

ccess Application

Open browser and visit:

http://localhost:5000

Output

Hello! Flask Application is running inside Docker 🚀