### Zhassulan Kainazarov

Backend Developer / DevOps at KOZ AI, Almaty. I write Python (FastAPI) and Go services and own the infrastructure they run on: Ansible, Docker and rootless Podman, GitLab CI and GitHub Actions, PostgreSQL. At work that means the team's golden paths (a GitLab CI component library, Ansible provisioning and hardening playbooks) and incident response for the services I own. M.Sc. Computer Science at KBTU, where I also lecture the undergraduate Databases course.

**Selected work**

- [rides-service](https://github.com/companion-ride/rides-service) and [pathfinder](https://github.com/companion-ride/pathfinder): the core services of a carpooling platform. PostGIS ride matching, a Kafka driver-offer waterfall, 2GIS routing with key rotation. The architecture, almost all of the code and the per-service CD on self-hosted runners are mine.
- [instant](https://github.com/Zhassulan1/instant): Go microservices behind a Consul-based API gateway, an idempotent Kafka consumer with retries and a dead-letter topic, Kafka on RKE2. Gateway, consumer and all infrastructure are mine (team of 4).
- [Secure-Container](https://github.com/Zhassulan1/Secure-Container): a hardened container image. Static non-root build, all capabilities dropped, seccomp, no-new-privileges; Trivy, Semgrep and SonarCloud in CI.

[LinkedIn](https://www.linkedin.com/in/zhkainazarov)
