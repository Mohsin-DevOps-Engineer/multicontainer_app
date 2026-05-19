# Multi-Container Application Deployment

## Overview

This project demonstrates a production-style multi-container application deployment using:

- Node.js
- Docker
- Docker Compose
- Nginx Reverse Proxy
- Redis

The application tracks page visits using Redis and serves traffic through an Nginx reverse proxy.

---

## Architecture

User → Nginx → Node.js App → Redis

---

## Tech Stack

- Docker
- Docker Compose
- Node.js
- Redis
- Nginx
- Linux

---

## Features

- Multi-container deployment
- Redis-based visit counter
- Nginx reverse proxy
- Docker networking
- Service communication
- Container orchestration using Docker Compose

---

## Project Structure

```bash
multi-container-app/
│
├── app/
│   ├── package.json
│   └── server.js
│
├── nginx/
│   └── default.conf
│
├── screenshots/
│
├── architecture/
│
├── Dockerfile
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

## Deployment

Clone repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Go to project directory:

```bash
cd multi-container-app
```

Run containers:

```bash
docker-compose up --build -d
```

Verify running containers:

```bash
docker ps
```

---

## Application Output

Open browser:

```bash
http://YOUR_VM_IP
```

The application displays a dynamic visit counter powered by Redis.

---

## Containers

This project runs the following containers:

- Node.js Application
- Redis Server
- Nginx Reverse Proxy

---

## Screenshots

### Running Containers

Add:
- docker-ps.png

### Browser Output

Add:
- browser-output.png

### Counter Increment

Add:
- counter-increment.png

---

## Future Improvements

- Kubernetes deployment
- CI/CD pipeline integration
- HTTPS support
- Monitoring with Prometheus & Grafana

---

## Author

Mohsin Qureshi
DevOps Engineer
