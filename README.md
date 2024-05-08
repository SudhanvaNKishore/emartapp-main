# EMart Microservice Application

This project demonstrates the deployment of a microservice application called EMart using Docker and Docker Compose.

## Introduction

EMart is an e-commerce application built using microservice architecture. It consists of multiple components, including frontend, backend APIs, and databases, all deployed as containers.

## Components

### Frontend
- Angular-based client app
- Accessible through NGINX API Gateway
- Endpoints: /, /api, /webapi

### Backend APIs
- Mart API: NodeJS application serving the /api endpoint
  - Requires MongoDB database
- Books API: Java application serving the /webapi endpoint
  - Requires MySQL database

## Deployment

### Prerequisites
- Docker
- Docker Compose
  
### Setup
1. Build and run the application:
docker-compose up -d
2. Access the application at http://localhost:80.

## Technologies Used
- Docker
- Docker Compose
- NGINX
- Angular
- NodeJS
- Java
- MongoDB
- MySQL
