# AI Model Evaluation & Deployment Platform

A production-minded platform for registering AI models, managing evaluation
datasets, running asynchronous model evaluations, tracking evaluation jobs,
storing metrics, and comparing model performance.

## Why This Project?

This project demonstrates production software engineering skills required
for AI/ML infrastructure and backend engineering roles, including:

- REST API design
- Authentication and authorization
- Database architecture
- Background job processing
- AI evaluation pipelines
- Distributed systems
- Automated testing
- Docker containerization
- CI/CD
- Observability
- Error handling
- Production-oriented architecture

## Architecture

React + TypeScript
        |
        v
     FastAPI
        |
   +----+----+
   |         |
PostgreSQL  Redis
              |
              v
           Celery
              |
              v
     Evaluation Engine
              |
              v
        Evaluation Results

## Technology Stack

### Backend
- Python
- FastAPI
- Pydantic
- SQLAlchemy
- PostgreSQL
- Redis
- Celery

### Frontend
- React
- TypeScript
- Vite

### DevOps
- Docker
- Docker Compose
- GitHub Actions

### Testing
- Pytest
- Unit tests
- Integration tests
