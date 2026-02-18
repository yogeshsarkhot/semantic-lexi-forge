# SemanticLexiForge

**SemanticLexiForge** is an enterprise-grade, 3-tier web application designed to capture, govern, and version **data dictionaries** and **rule dictionaries** in a way that makes them natively understandable and usable by AI coding agents (Gemini, Claude, custom LLMs, etc.).

It combines:
- **Structured entity-attribute modeling** (data dictionary)
- **Rich, contextual business rule definition** with intelligent @entity.attribute autocompletion
- **Full versioning & audit history**
- **Approval-based workflow** (editor → reviewer → approved/published)
- **Role-based access** (editor, reviewer, admin)

… all built with modern, production-ready tools: React + Vite (frontend), Spring Boot 3 + PostgreSQL (backend), Docker + Kubernetes-ready deployment, Terraform (AWS/Azure multi-cloud), and observability/logging foundations.

The goal: turn messy, human-only requirements artifacts into clean, **semantic-rich lexicons** that AI agents can reliably read, reason over, and act upon — accelerating enterprise software delivery while maintaining governance and traceability.

**Status:** MVP foundation in progress → full enterprise hardening underway.

Tech highlights:
- React 18 + TypeScript + Tailwind + TanStack Query
- Spring Boot 3.3+ (Java 21) + JPA/Hibernate Envers + Flyway
- PostgreSQL 16 (multi-AZ planned)
- Terraform IaC (AWS + Azure + Kubernetes)
- Mock roles & security for demo (real auth later)
- Correlation-ID tracing, structured logging, actuator metrics

Perfect for teams that want requirements documentation to become **AI-native assets** instead of static Word/Confluence pages.
