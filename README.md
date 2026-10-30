# Dao Khai Minh

Full-Stack Software Engineer | Java, Spring Boot & Angular | Distributed Systems & Cloud Native

I build Java APIs and Angular interfaces, with a focus on clear contracts, relational data and reliable failure handling. My portfolio centers on FlowDesk, where I document architecture decisions and verify behavior across the browser, API and database.

## Core stack

- **Backend:** Java 21, Spring Boot, REST APIs and API contract testing.
- **Frontend:** Angular 20, TypeScript, standalone components, lazy routing and RxJS.
- **Database:** PostgreSQL, SQL constraints, Flyway migrations and Testcontainers integration tests.
- **Infrastructure & delivery:** Docker Compose for local development, GitHub Actions, frontend lint/build checks and Playwright E2E tests.

## Flagship: [FlowDesk](https://github.com/khaiminh0401/flowdesk)

An enterprise workspace and workflow management application **in development**. The current increment establishes the engineering foundation and live dashboard/API connectivity.

**Stack:** Java 21 / Spring Boot 3.5 · Angular 20 / TypeScript · PostgreSQL 17 / Flyway.

**Architecture:** Modular Monolith — one Spring Boot API, one Angular SPA and one database. Feature packages provide the starting structure; business modules are planned. The [architecture decision](https://github.com/khaiminh0401/flowdesk/blob/main/docs/adr/0001-modular-monolith.md) explains the choice and its scaling trade-offs.

### Implemented

- API info and health endpoints, plus a standalone Angular shell with a lazy dashboard.
- A read-only connection card with loading, response validation, bounded errors and retry.
- Flyway V1 schema groundwork, tested against real PostgreSQL with Testcontainers.
- API and Angular unit tests, Playwright connectivity/failure/mobile tests, and GitHub Actions quality gates.

### Planned

Authentication and sessions, workspace RBAC and management, project/task CRUD, Kanban, approvals and audit history. The user table is schema groundwork; no user API or JPA entity exists yet. Production deployment and observability are future milestones.

**Evidence:** [CI run on `69ad007`](https://github.com/khaiminh0401/flowdesk/actions/runs/40338793703) passed on October 26, 2026: 2 API unit tests, 7 PostgreSQL integration tests, 18 Angular unit tests and 4 Playwright tests. These tests cover the implemented foundation and connectivity.

Explore the [test strategy](https://github.com/khaiminh0401/flowdesk/blob/main/docs/engineering/TEST-STRATEGY.md), [source at the verified commit](https://github.com/khaiminh0401/flowdesk/tree/69ad007b0e6cb52ccd7950d473b11ffb8c8f4ec2) and [roadmap](https://github.com/khaiminh0401/flowdesk/blob/main/docs/engineering/PRODUCT-ROADMAP.md).

## Selected projects

- **[Java6_ASM_BE](https://github.com/khaiminh0401/Java6_ASM_BE)** — Java/Spring Boot e-commerce coursework with product pagination/filtering, cart and order APIs. An earlier backend project.
- **[micro-gateway](https://github.com/khaiminh0401/micro-gateway)** — Java 21 / Spring Cloud Gateway experiment with reactive routes and path rewriting configured in YAML.
- **[mcp-demo-spring](https://github.com/khaiminh0401/mcp-demo-spring)** — Java 21 / Spring AI travel-booking proof of concept: a Gemini-backed REST agent and three MCP servers for synthetic flight, hotel and cab bookings, with H2 persistence.

## Engineering focus

I value readable code, reproducible tests and explicit trade-offs. My current work focuses on:

- Tracing failures across UI, HTTP contracts and database boundaries.
- Testing schema constraints against a real database and handling loading/error/retry states explicitly.
- Choosing architecture that fits the current scope and documenting when to revisit it.

I am deepening my understanding of distributed systems and cloud-native engineering, especially transaction consistency, idempotency, messaging reliability and observability.

## Contact

[khaiminh0401@gmail.com](mailto:khaiminh0401@gmail.com) · [GitHub](https://github.com/khaiminh0401)
