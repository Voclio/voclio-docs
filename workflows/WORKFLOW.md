This document defines how the Voclio team collaborates across mobile, web, backend, AI, and design.
It ensures consistency, quality, and smooth delivery.

1. Branching Strategy

main → Always production-ready. Deployed version.

develop → Staging & integration branch. All features merged here first.

Feature branches → For new work.

Format: feature/<repo>/<short-name>

Examples:

feature/mobile/login-ui

feature/web/dashboard-tasks

feature/backend/api-auth

feature/ai/tts-service

Fix branches → For bug fixes.

Example: fix/backend/db-connection

Hotfix branches → Urgent production bugs.

Example: hotfix/web-crash-on-load

Release branches → Pre-production QA & versioning.

Example: release/v1.0.0

2. Roles & Responsibilities

Mobile Team (3 Flutter) → Build voclio-mobile.

Web Dev (1) → Build voclio-web.

Backend Team (2) → APIs in voclio-backend, DB, auth, integration.

AI/ML Team (2) → AI models in voclio-ai.

Shared → Everyone uses voclio-docs for workflows + voclio-design for assets.

3. Commit Guidelines

We follow conventional commits.
