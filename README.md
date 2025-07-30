# ONDC Services

This repository contains microservices and APIs for ONDC implementation.

## Services Include:
- Authentication Service
- Registry Service  
- Gateway Service
- Logging Service
- Monitoring Service

## Getting Started

### Prerequisites
- Docker and Docker Compose
- Node.js 18+ / Python 3.8+ / Java 11+ (depending on service)
- MongoDB / PostgreSQL (for data persistence)

### Installation
```bash
# Clone the repository
git clone https://github.com/nmonga26/Services.git
cd Services

# Start all services using Docker Compose
docker-compose up -d
```

## Service Architecture

Each service follows a microservices architecture pattern with:
- RESTful APIs
- Event-driven communication
- Containerized deployment
- Independent scaling

## Related Repositories
- [ONDC-Specifications](https://github.com/nmonga26/ONDC-Specifications)
- [Workbench](https://github.com/nmonga26/Workbench)
- [SDKs-and-Utilities](https://github.com/nmonga26/SDKs-and-Utilities)
