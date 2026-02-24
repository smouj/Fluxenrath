# Fluxenrath

<p align="center">
  <img src="./assets/branding/logo.svg" alt="Fluxenrath logo" width="88" />
</p>

![Language](https://img.shields.io/badge/language-Python%203.11%2B-blue)
![License](https://img.shields.io/github/license/smouj/Fluxenrath)
![Last Commit](https://img.shields.io/github/last-commit/smouj/Fluxenrath)
![CI](https://img.shields.io/github/actions/workflow/status/smouj/Fluxenrath/ci.yml?branch=main)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20this%20project-ff5f5f?logo=ko-fi&logoColor=white)](https://ko-fi.com/smouj013_dev)

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

**Workflow automation forge with resilient execution semantics.**

## Vision
Executes DAG-style workflows with guardrails, retries, and traceable outcomes.

## What problem it solves
Automation flows fail without robust retries and state guarantees.

## Core superpower
- ⚡ **Composable workflow engine with reliability-first orchestration**

## Key use cases
- ✅ Task orchestration
- ✅ Pipeline automation
- ✅ Self-healing retries
- ✅ Local-first ops workflows


## API surface
`GET /`, `POST /run` (planned), `GET /health`

## Technical stack
- **Core stack:** FastAPI + workflow graph runtime
- **Runtime:** local-first, self-hosted friendly
- **Infra:** Docker Compose + Caddy + Redis/Chroma/Ollama compatibility

## Current status (Feb 2026)
- ✅ Public scaffold available
- ✅ Bilingual README (EN default + ES)
- ✅ CI + release baseline configured
- 🚧 Feature hardening in progress

## Quick start
```bash
git clone https://github.com/smouj/Fluxenrath.git
cd Fluxenrath
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m src.fluxenrath.cli --help
```

## Documentation
- [Implementation Guide](./docs/IMPLEMENTATION.md)
- [Architecture](./docs/ARCHITECTURE.md)
- [Runbook](./docs/RUNBOOK.md)
- [Deployment Guide](./docs/DEPLOYMENT.md)
- [Release Process](./docs/RELEASE.md)
- [Changelog](./CHANGELOG.md)

## Contributing
Contributions are welcome. Please read [CONTRIBUTING.md](./CONTRIBUTING.md).

## License
MIT © 2026 smouj

---

### Other skills
Explore the full ecosystem here: **[smouj/smouj](https://github.com/smouj/smouj)**

**Signature:** [@Smouj013](https://x.com/smouj013)
