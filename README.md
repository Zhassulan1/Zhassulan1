# Zhassulan Kainazarov

Backend Developer / DevOps at KOZ AI, Almaty. Python (FastAPI) and Go backends, plus the infrastructure
they run on: Ansible, Docker / rootless Podman, GitLab CI and GitHub Actions, PostgreSQL.
M.Sc. Computer Science at KBTU, where I lecture the undergraduate Databases course (PostgreSQL internals).

At work: the team's golden paths (a reusable GitLab CI component library, Ansible provisioning and hardening
playbooks, a JWT/RBAC auth library), incident response and monitoring for the services I own, PostgreSQL
query tuning, and client SLAs validated with Locust before delivery.

## Where to look

| Repo | What it is | My part |
|---|---|---|
| [rides-service](https://github.com/companion-ride/rides-service) | Ride matching for a carpooling platform: Go, PostgreSQL/PostGIS, Kafka driver-offer waterfall | architecture, almost all of the code, CD on self-hosted runners |
| [pathfinder](https://github.com/companion-ride/pathfinder) | Routing service: 2GIS API with key rotation, Redis cache, S2 projection | architecture, almost all of the code, CD on self-hosted runners |
| [instant](https://github.com/Zhassulan1/instant) | Go microservices: Consul-based API gateway, idempotent Kafka consumer (retries, DLQ), Kafka on RKE2 | gateway, consumer, all infrastructure (team of 4) |
| [Secure-Container](https://github.com/Zhassulan1/Secure-Container) | Hardened container example: static non-root build, cap_drop ALL, seccomp, Trivy / Semgrep / SonarCloud in CI | solo |

zhkainazarov@gmail.com | [LinkedIn](https://www.linkedin.com/in/zhkainazarov)
