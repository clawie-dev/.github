# Clawie

> The open-source autonomous software agency framework.

Clawie runs teams of AI agents — from brief to launched product. Research, spec, code, review, deploy, market — all in isolated containers, every config version-controlled, every decision auditable.

## Where to start

- 📖 **[Specifications](https://github.com/clawie-dev/specs)** — the end-goal architecture and 31 feature specs
- 🤖 **[Framework](https://github.com/clawie-dev/clawie)** — the AdonisJS platform (CLI + Web + API)
- 📚 **[Documentation](https://github.com/clawie-dev/docs)** — user guides
- 🛒 **[Marketplace](https://github.com/clawie-dev/market.clawie.dev)** — design contract for plugins, skills, drivers (lands in v1.x)
- 🌐 **[clawie.dev](https://github.com/clawie-dev/clawie.dev)** — landing + docs site

## Highlights

- **Layered, not monolithic** — surfaces, control plane, policy + credential, runtime, eval — each swappable
- **Default-deny** — Docker isolation + optional Outcall egress rules
- **Git is the source of truth** — every team, agent, skill is its own repo with per-component rollback
- **Continuously benchmarked** — agents are scored on every self-modification merge
- **End-to-end software agency** — the v1.x flagship pipeline (research → spec → code → review → deploy → market) defined in [spec 016](https://github.com/clawie-dev/specs/tree/main/speckit/016-software-agency-pipeline); v1.0 ships the substrate (durable lifecycle, container execution, policy, audit, teams, scheduler) the pipeline runs on

## License

MIT.
