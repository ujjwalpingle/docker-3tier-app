# Simple Three-Tier Docker App

A basic web application with React, Flask, and PostgreSQL.

## Setup Steps

1. Clone the repo
2. Copy `.env.example` to `.env`
3. Update `.env` with real credentials
4. Run `docker-compose up --build`

## Access Points

- Website: http://localhost:3000
- API: http://localhost:5000
- Database: localhost:5432

## Useful Commands

```bash
# Start the app
docker-compose up --build

# Stop the app
docker-compose down

# View logs
docker-compose logs
```

## Project Structure
```
my-app/
├── frontend/  (React)
├── backend/   (Flask)
└── docker-compose.yml
```

