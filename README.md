# DevOps Build Project

## Project Overview
This project demonstrates a complete DevOps workflow for deploying a React application using Docker, Docker Hub, Jenkins, AWS EC2, Prometheus, and Grafana.

## Technologies Used
- AWS EC2 (Ubuntu 24.04)
- Docker
- Docker Hub
- Jenkins
- Git & GitHub
- Prometheus
- Grafana
- Nginx

## Project Architecture

GitHub Repository
        |
        v
     Jenkins
        |
        v
 Docker Build
        |
        v
 Docker Hub
        |
        v
 Docker Container on EC2
        |
        v
 Prometheus + Node Exporter
        |
        v
 Grafana Dashboard

## Features
- Dockerized React application
- Custom Dockerfile
- Docker Compose support
- Jenkins CI/CD Pipeline
- Docker Hub integration
- Automated image build and push
- Monitoring with Prometheus
- Visualization with Grafana

## Docker Commands

Build Image

```bash
docker build -t vinay2704/dev:v1 .
