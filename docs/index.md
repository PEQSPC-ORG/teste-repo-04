# teste-repo-04

Welcome to the documentation for **teste-repo-04**.

## Overview

| Property | Value |
|----------|-------|
| **Tech Stack** | NODEJS |
| **Branching** | trunk |
| **Repository** | [PEQSPC-ORG/teste-repo-04](https://github.com/PEQSPC-ORG/teste-repo-04) |

## Getting Started

```bash
npm install
npm run dev
```

## CI/CD

This project uses GitHub Actions for continuous integration and delivery.
See [`.github/workflows/ci-cd.yaml`](https://github.com/PEQSPC-ORG/teste-repo-04/blob/main/.github/workflows/ci-cd.yaml).

## Health Check

The service exposes a health endpoint at `/health`.
```json
GET /health
{
  "status": "ok",
  "service": "teste-repo-04"
}
```
