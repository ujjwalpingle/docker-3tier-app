# Simple Three-Tier Docker App  

![Three-Tier Architecture](/assets/Simple%20Three-Tier%20Docker%20App.jpg)  

A basic web application using **React (Frontend)**, **Flask (Backend API)**, and **PostgreSQL (Database)**, containerized with Docker for easy deployment.  

## Prerequisites  

Ensure you have the following installed:  
- [Docker](https://docs.docker.com/get-docker/)  
- [Docker Compose](https://docs.docker.com/compose/install/)  

## Setup & Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-repo/three-tier-app.git
   cd three-tier-app
   ```  
2. **Set up environment variables:**  
   ```bash
   cp .env.example .env
   ```  
   - Update `.env` with your database credentials.  
3. **Start the application:**  
   ```bash
   docker-compose up --build
   ```  

## Access Points  

- **Frontend (React):** [http://localhost:3000](http://localhost:3000)  
- **Backend API (Flask):** [http://localhost:5000](http://localhost:5000)  
- **PostgreSQL Database:** `localhost:5432`  

## Useful Commands  

```bash
# Start the app
docker-compose up --build  

# Stop the app
docker-compose down  

# View logs
docker-compose logs  

# Rebuild containers
docker-compose up --build --force-recreate  
```

## Project Structure  

```
three-tier-app/
├── frontend/    # React application
├── backend/     # Flask API server
├── db/          # Database-related scripts (optional)
└── docker-compose.yml  # Docker configuration
```

---

This project provides a simple yet scalable foundation for a three-tier web application using Docker. 🚀
