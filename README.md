# Book Club Platform

A mobile-first platform for managing book clubs, their members, books, reading schedules, meetings, discussions, and club activity.

The project is being developed incrementally as a production-style software system, with an emphasis on backend engineering, mobile development, software architecture, database design, distributed systems, cloud infrastructure, reliability, and eventually AI integration.

## Vision

The long-term goal is to build a platform that book clubs can use to organize and experience their clubs from one place.

The primary user interfaces will eventually be native mobile applications for:

- Android
- iOS

These applications will communicate with a shared backend API.

The project will be developed incrementally rather than attempting to build the entire product upfront.

## Project Goals

The Book Club Platform serves two purposes:

1. Build a useful product for real book clubs.
2. Serve as a long-term engineering project for exploring the design, development, and operation of a production software system.

## Planned Architecture

The intended high-level architecture is:

```text
Android Application
        │
        │
        ├──────────► Backend API ◄──────────┐
        │                 │                 │
        │                 │                 │
iOS Application           ▼                 │
                    Data & Services         │
```

The exact architecture and technologies will evolve as the project develops.

## Core Domain

The initial domain includes:

- Users
- Book clubs
- Club membership
- Books
- Reading selections
- Reading schedules
- Meetings
- Ratings and reviews
- Discussions
- Club activity and history

Additional functionality will be introduced as the product evolves.

## Initial Product Scope

### Users

Users should eventually be able to:

- Create and manage an account
- Join book clubs
- Participate in multiple clubs
- View their club activity

### Book Clubs

Book clubs should eventually be able to:

- Create and manage a club
- Manage membership
- Assign member roles
- Maintain a history of books and meetings

### Books

Clubs should eventually be able to:

- Add books
- Select books to read
- Track current and previous selections
- Rate and review completed books

### Meetings

Clubs should eventually be able to:

- Schedule meetings
- Record meeting details
- Track attendance
- Associate meetings with book selections

## Potential Future Product Areas

Future functionality may include:

- Book nominations and voting
- Reading progress
- Discussion prompts
- Member contributions
- Club analytics
- Notifications and reminders
- Book recommendations
- AI-assisted discussion features
- Integrations with external book data sources

These features are outside the initial implementation scope and will be evaluated incrementally.

## Engineering Direction

The project is intended to progressively explore several areas of software engineering.

### Backend Engineering

Planned areas include:

- Python
- Django
- Django REST Framework
- API design
- Authentication and authorization
- Domain modelling
- Business logic
- Testing

### Mobile Development

The intended mobile clients are:

**Android**
- Kotlin
- Jetpack Compose

**iOS**
- Swift
- SwiftUI

Mobile development will begin after the initial backend foundation has been established.

### Data & Persistence

Planned areas include:

- PostgreSQL
- Schema design
- Constraints and data integrity
- Query optimization
- Indexing
- Transactions
- Concurrency

### Distributed Systems

As the system grows, it may introduce:

- Redis
- Background jobs
- Celery
- Caching
- Event-driven workflows
- Idempotency
- Asynchronous processing

### Reliability & Operations

The project will eventually explore:

- Logging
- Metrics
- Tracing
- Error handling
- Health checks
- Observability
- Performance monitoring

### Cloud & Infrastructure

Later phases are expected to explore:

- Docker
- AWS
- Kubernetes
- Infrastructure as Code
- Terraform
- CI/CD
- Production deployment

### AI

AI capabilities may eventually be introduced where they provide genuine product value, potentially including:

- Book recommendations
- Discussion-question generation
- Review and discussion summarization
- Semantic search
- Reading insights

## Development Approach

The project is intentionally iterative.

Each phase will introduce new product and engineering capabilities while preserving a functioning system.

The priority is not feature quantity. The goal is to build a system whose architecture, data model, business rules, reliability, and operational characteristics can be understood and explained.

## Current Focus

The first development phase focuses on establishing the core backend and domain model:

- Users and authentication
- Book clubs
- Club membership and roles
- Books
- Core business rules
- REST API foundations
- PostgreSQL persistence
- Automated testing

Subsequent phases will expand the platform into mobile clients, distributed processing, cloud infrastructure, observability, and intelligent features.

## Status

🚧 Active development
