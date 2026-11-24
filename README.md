# Fixora

Fixora is a maintenance management system.

## Project structure
- `frontend/` – React + Vite application
- `backend/` – Spring Boot REST API
- `database/` – ER diagram and sample data scripts
- `documentation/` – diagrams, UI designs, meeting notes, report and user guide
- `testing/` – manual test cases and QA reports

## Prerequisites
- Java 17+
- Node.js 20+
- Docker Desktop
- Git

## Setup
1. Copy `.env.example` to `.env` and fill in local secret values.
2. Start the database with `docker compose up -d`.
3. Start the backend from `backend/`.
4. Start the frontend from `frontend/`.

Do not commit `.env`, passwords, tokens, uploaded files, `node_modules/`, or `target/`.

## Git workflow
- Create feature branches from `develop`.
- Push your feature branch and open a Pull Request into `develop`.
- Do not push directly to `main` or `develop`.
