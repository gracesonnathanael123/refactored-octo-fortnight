# Flask Docker Application

A simple Flask web application containerized with Docker.

## Student Details
- **Student ID:** URK22CS1105
- **Exercise:** 3 - Flask App Containerization and Docker Hub Deployment
- **Course:** DevOps Laboratory (24CS2019)

## Features
- Flask web application
- Dockerized for easy deployment
- Published on Docker Hub
- Version controlled with Git

## Local Setup

### Run without Docker
```bash
pip install -r requirements.txt
python app.py
```

### Run with Docker
```bash
docker build -t flask-docker-app .
docker run -p 5000:5000 flask-docker-app
```

Visit: http://localhost:5000

## Docker Hub
Pull the image:
```bash
docker pull <your-dockerhub-username>/flask-docker-app:latest
docker run -p 5000:5000 <your-dockerhub-username>/flask-docker-app:latest
```

## Technologies Used
- Python 3.9
- Flask 2.2.5
- Docker
- Git & GitHub