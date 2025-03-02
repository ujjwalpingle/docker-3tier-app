# Simple Three-Tier Docker App

A basic web application with React, Flask, and PostgreSQL.

## Quick Start

1. **Install Requirements**
   - Docker
   - Docker Compose

2. **Run the App**

```bash
# Start the app
docker-compose up --build

# Stop the app
docker-compose down
```

3. **Access the App**
   - Website: http://localhost:3000
   - API: http://localhost:5000

## Useful Commands

```bash
# View logs
docker-compose logs

# Check running containers
docker ps
```

## Project Structure

```
my-app/
├── frontend/ (React)
├── backend/ (Flask)
└── docker-compose.yml
```

