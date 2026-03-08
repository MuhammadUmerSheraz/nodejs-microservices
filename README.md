# nodejs-microservices

Production-ready Node.js Microservices built with Clean Architecture and SOLID principles.

## Architecture

- **Clean Architecture** - Separation of concerns across domain, data, and presentation layers
- **Modular Structure** - Independently deployable and testable modules
- **SOLID Principles** - Maintainable, extensible codebase

## Tech Stack

Node.js, NestJS, TypeORM, Redis, RabbitMQ

## Setup

```bash
npm install
cp .env.example .env
npm run start:dev
```

## Testing

```bash
npm test
```

## Docker

```bash
docker-compose up -d
```

## Documentation

- [Architecture](docs/architecture.md)
- [System Design](docs/system-design.md)
- [Deployment](docs/deployment.md)
