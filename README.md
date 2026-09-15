<div align="center">

# Easy Python Service Starter

**A production-capable Python service foundation for workers, webhooks, scheduled jobs, integrations, automation, and messaging workloads.**

[![Use this template](https://img.shields.io/badge/use%20this%20template-2EA44F?logo=github&logoColor=white)](https://github.com/FonijBuild/easy-python-service-starter/generate)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)
![Status: Foundation](https://img.shields.io/badge/status-foundation-F59E0B)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![uv](https://img.shields.io/badge/uv-DE5FE9) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Service](https://img.shields.io/badge/runtime-service-7C3AED)

[Documentation](https://github.com/FonijBuild/fonij-docs) · [Discussions](https://github.com/orgs/FonijBuild/discussions) · [Issues](https://github.com/FonijBuild/easy-python-service-starter/issues)

</div>

> “What do we build for, if not to lessen each other’s hardship?”

> [!IMPORTANT]
> This repository is currently in the **foundation stage**. Do not treat it as production-ready until the first stable release.

## Best for

- Background workers and scheduled jobs
- Webhook consumers and integration services
- Automation workloads
- Messaging bots built through channel adapters

**Not for:** A full web frontend or a domain-heavy Django application that benefits from the Django API foundation.

## Baseline

- Clear service, domain, integration, job, and worker boundaries
- Environment validation and structured logging
- Testing, typing, linting, CI, and container-ready workflows
- Extension points for queues, schedulers, and channel adapters
- AI-agent rules, specs, and architecture documentation

## Quick start

Preferred:

```bash
fonij create my-product
```

Direct template use:

```bash
gh repo create my-product --template FonijBuild/easy-python-service-starter --private --clone
cd my-product
cp .env.example .env
uv sync
uv run pytest
```

## Project contract

- `.fonij/starter.json` describes this foundation to Fonij.
- `AGENTS.md` defines repository rules for AI coding agents.
- `specs/` contains implementation-ready feature specifications.
- `docs/` contains architecture and repository-specific guidance.
- Keep quality checks green before merging changes.

## Contributing

Read [`CONTRIBUTING.md`](CONTRIBUTING.md) before contributing. Security issues must follow [`SECURITY.md`](SECURITY.md).
