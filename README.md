### Senior Full-Stack / Product Engineer — production infrastructure · automation · applied AI

I build the application **and** run the production infrastructure it lives on. Kuala Lumpur, Malaysia · remote (GMT+8).

10+ years delivering production web applications and business systems for SME, NGO and e-commerce
clients — then deploying, securing, monitoring and supporting them on a three-host self-managed Docker
platform. Most full-stack engineers stop at the application layer; running the platform underneath it is
what keeps that layer honest.

---

#### Selected work

| Project | What it is |
|---|---|
| **Three-host production platform** | 162 containers across 78+ compose stacks on Synology DSM, Unraid and an Ubuntu VPS, serving live public services. Traefik reverse-proxy fleet with automated ACME TLS, Prometheus/Grafana monitoring on every host, authentik SSO, MySQL master/replica replication, CI/CD, and automated backup and restore. |
| **[traefik-botfilter](https://github.com/hoelee/traefik-botfilter)** | Dependency-free Traefik middleware in Go — rejects scanner and malformed-HTTP traffic using configurable request validation, heuristic scoring and temporary in-memory IP bans. |
| **[hoelee-webdav-server](https://github.com/hoelee/hoelee-webdav-server)** | Hardened WebDAV server (Apache httpd) in Docker — pinned base image, modern TLS, healthcheck, CI/CD. |
| **[email-sync-oauth2](https://github.com/hoelee/email-sync-oauth2)** | Dockerised multi-account IMAP sync with OAuth2 for Office 365, Outlook.com and Gmail — built for the Microsoft Basic-Auth retirement. |
| **[digikedai-bot](https://github.com/hoelee/digikedai-bot)** | Production Telegram AI customer-support bot: Dockerised, LLM-backed, tunnel-only ingress (no inbound ports). TypeScript + LiteLLM, running in production since Aug 2026. |
| **[springboot-hoelee-demo](https://github.com/hoelee/springboot-hoelee-demo)** | Modern Spring Boot showcase — Thymeleaf UI, JPA, Security, caching and tests. Live at [spring.hoelee.com](https://spring.hoelee.com). |
| **[universal-video-transcode](https://github.com/hoelee/universal-video-transcode)** | Any video in, one MP4 out that plays on both iPad and Android. Source-file-driven recipe selection (lossless copy where possible) and a header-only gate that catches the frame-timing defect no fps test can see. |
| **[hoelee-blog](https://github.com/hoelee/hoelee-blog)** | Technical writing on real debugging, migrations and platform design. Astro 5 + Markdown, English-first with Chinese under `/posts/zh/`, deployed by self-hosted CI/CD. |

#### What I work with

```
Languages    PHP · Java · Python · JavaScript · TypeScript · SQL
Frameworks   Spring Boot · CodeIgniter · WordPress · Node.js · REST APIs
Data         PostgreSQL · MySQL/MariaDB (incl. replication) · Redis · SQLite · Elasticsearch
Platform     Docker · Linux · Traefik · Nginx · Cloudflare · CI/CD (GitHub Actions, Gitea Actions)
Infra        Self-hosted mail (Postfix/Dovecot/Rspamd) · Prometheus/Grafana · authentik SSO · restic backup
AI           OpenAI API · LLM integration · OCR · n8n automation · local LLM inference (llama.cpp)
```

Beyond application work I take automation end-to-end: browser-automation and CDP tooling, marketplace and
fulfilment workflows, and AI features shipped inside commercial products, including a WordPress plugin that
generates furniture product photography with an image model.

---

#### Elsewhere

- **Writing** — [blog.hoelee.com](https://blog.hoelee.com)
- **Portfolio** — [me.hoelee.com](https://me.hoelee.com)
- **LinkedIn** — [linkedin.com/in/hoelee](https://linkedin.com/in/hoelee)
- **Work with me** — [me@hoelee.com](mailto:me@hoelee.com)

<sub>Most of my day-to-day repositories live on a self-hosted Gitea instance; what is public here is what I can show.</sub>
