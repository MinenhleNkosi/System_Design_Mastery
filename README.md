# System Design Mastery Guide 🏗️

> A comprehensive, dual-level reference for software engineers — from first-principles fundamentals to production-grade architecture patterns.

---

## Overview

This repository contains a structured guide to system design that serves both **beginners** and **experienced engineers**. It walks through the entire journey of building scalable, reliable, and secure systems: starting from a single-server setup and progressing through databases, scaling strategies, APIs, protocols, authentication, and security.

Whether you're preparing for system design interviews, planning an MVP, or architecting enterprise platforms, this guide provides the conceptual knowledge and practical patterns needed to make sound architectural decisions.

---

## What's Inside

### 🏠 Foundations
- **Single Server Setup** — Understanding the baseline architecture, its components, bottlenecks, and when to move beyond it
- **Vertical vs. Horizontal Scaling** — Tradeoffs, decision frameworks, and migration strategies for growing systems
- **Load Balancing** — Algorithms (Round Robin, Least Connections, IP Hash), Layer 4 vs. Layer 7, SSL termination, and redundancy

### 🗄️ Data
- **Databases: SQL, NoSQL, Graph** — When to use each, ACID vs. BASE tradeoffs, partitioning/sharding strategies, and side-by-side comparisons
- **Caching** — In-memory caches (Redis/Memcached), eviction policies, cache invalidation strategies

### 🔌 APIs & Protocols
- **API Design** — REST principles, versioning, pagination, rate limiting, and standardized error formats
- **RESTful APIs** — Idempotency, ETags, content negotiation, and API gateway patterns
- **GraphQL** — Schema design, N+1 mitigation with DataLoader, federation, and cost-based query validation
- **API Protocols** — REST, GraphQL, gRPC, and WebSocket compared with expert-level usage guidance
- **Transport Layer** — TCP vs. UDP deep dive including flow/congestion control, QUIC, and protocol selection

### 🔒 Security & Identity
- **Authentication** — Sessions, JWTs, OAuth 2.0 flows (Authorization Code + PKCE, Client Credentials), OpenID Connect, MFA, and passkeys
- **Authorization** — RBAC, ABAC, PBAC (OPA/Rego), OAuth scopes, and fine-grained resource-level permissions
- **Security** — HTTPS/TLS, input validation, OWASP Top 10, secrets management, security headers, DDoS protection, and Zero Trust principles

### 🛡️ Reliability
- **Health Checks** — Active vs. passive checks, readiness vs. liveness probes, and circuit breaker patterns
- **Single Points of Failure (SPOF)** — Dependency mapping, Active-Active vs. Active-Passive redundancy, RTO/RPO, and multi-region strategies

---

## Who This Is For

| Audience | What they'll find |
|---|---|
| **Beginners** | Plain-language explanations, step-by-step reasoning, and clear use cases for every concept |
| **Experts** | Deep dives into performance tuning, consistency models, tradeoffs, production patterns, and tooling |

---

## Key Features

- **Dual-level explanations** for every topic — beginner and expert perspectives side by side
- **Code examples** in JavaScript/Node.js, GraphQL, Rego (OPA), and Nginx config
- **Architecture diagrams** illustrating key concepts visually
- **Comparison tables** for quick decision-making (SQL vs. NoSQL vs. Graph, TCP vs. UDP, etc.)
- **Real-world examples** grounded in common production systems (e-commerce, social networks, streaming services)

---

## Suggested Learning Path

1. Start with **Single Server Setup** to understand the baseline
2. Move to **Databases** and learn how to choose the right data store
3. Study **Scaling** and **Load Balancing** to handle growth
4. Explore **API Design**, **RESTful APIs**, and **GraphQL** for service communication
5. Dive into **Transport Protocols** for networking fundamentals
6. Finish with **Authentication**, **Authorization**, and **Security** to harden your systems

---

## Practice Projects

Apply what you've learned by building:

- **URL Shortener** — rate limiting, caching, relational database
- **Social Feed** — NoSQL, denormalization, fan-out patterns
- **Chat Service** — WebSocket, presence management, horizontal scaling
- **E-commerce API** — REST with pagination, idempotency, and authentication

---

## Recommended Resources

- *Designing Data-Intensive Applications* — Martin Kleppmann
- The System Design Primer (open-source)
- OWASP Cheat Sheets
- AWS Well-Architected Framework & Google SRE Book

---

## License

See [LICENSE](./LICENSE) for details.
