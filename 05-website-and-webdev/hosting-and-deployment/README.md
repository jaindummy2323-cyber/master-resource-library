# Hosting, Deployment & DevOps Tools

> The best open-source self-hosting platforms, deployment tools, and infrastructure management for web applications.

---

## Self-Hosted PaaS (Heroku/Vercel Alternatives)

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Coolify](https://github.com/coollabsio/coolify) | 36k+ | Open-source, self-hostable Heroku/Netlify alternative. | One-click deploys. Docker + Buildpacks. SSL, databases, monitoring. |
| [Dokku](https://github.com/dokku/dokku) | 29k+ | Docker-powered mini-Heroku. Smallest PaaS implementation. | Git push to deploy. Heroku buildpacks. Simple and proven. |
| [CapRover](https://github.com/caprover/caprover) | 13k+ | Easy-to-use app/database deployment and web server manager. | One-click apps. Let's Encrypt SSL. Web dashboard. Docker-based. |
| [Dokploy](https://github.com/Dokploy/dokploy) | 10k+ | Open-source Vercel/Netlify/Heroku alternative. | Modern UI. Docker + Docker Compose. Multi-server support. |
| [Kamal](https://github.com/basecamp/kamal) | 12k+ | Deploy web apps anywhere with Docker. By Basecamp. | Zero-downtime deploys. Works on any cloud or VPS. Simple YAML config. |
| [Sst](https://github.com/sst/sst) | 22k+ | Build full-stack apps on your own infrastructure. | AWS-native. Infrastructure as code. Live Lambda development. |

## Container Orchestration

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Kubernetes (K8s)](https://github.com/kubernetes/kubernetes) | 112k+ | Production-grade container orchestration. | Industry standard. Auto-scaling, self-healing, rolling updates. |
| [K3s](https://github.com/k3s-io/k3s) | 28k+ | Lightweight Kubernetes distribution. | Half the memory of K8s. Perfect for edge, IoT, and VPS. |
| [Portainer](https://github.com/portainer/portainer) | 31k+ | Lightweight management UI for Docker and Kubernetes. | Best Docker GUI. Manage containers, images, networks visually. |
| [Traefik](https://github.com/traefik/traefik) | 52k+ | Modern HTTP reverse proxy and load balancer. | Auto-discovers services. Let's Encrypt. Docker/K8s native. |
| [Caddy](https://github.com/caddyserver/caddy) | 60k+ | Fast, multi-platform web server with automatic HTTPS. | Auto-HTTPS. Zero-config TLS. Simpler than Nginx for most use cases. |
| [Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager) | 23k+ | Nginx management with a nice web UI. | Easy reverse proxy. SSL management GUI. Docker-based. |

## CI/CD & Build Tools

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Gitea](https://github.com/go-gitea/gitea) | 46k+ | Painless self-hosted Git service. Lightweight GitHub alternative. | Self-hosted GitHub. CI/CD built in (Gitea Actions). Single binary. |
| [Forgejo](https://github.com/forgejo/forgejo) | 5k+ | Community-driven Gitea fork. | Community-governed. Enhanced privacy. Same Gitea features. |
| [Drone](https://github.com/harness/drone) | 32k+ | Container-native CI/CD platform. | Docker-first CI/CD. Simple YAML pipelines. Self-hosted. |
| [Woodpecker CI](https://github.com/woodpecker-ci/woodpecker) | 4k+ | Simple yet powerful CI/CD engine (Drone fork). | Community fork of Drone. Multi-platform. Plugin ecosystem. |
| [Act](https://github.com/nektos/act) | 56k+ | Run GitHub Actions locally. | Test GitHub Actions on your machine. Fast iteration. |

## Monitoring & Observability

| Repo | Stars | Description | Why It's Top-Tier |
|------|-------|-------------|-------------------|
| [Uptime Kuma](https://github.com/louislam/uptime-kuma) | 60k+ | Self-hosted monitoring tool. | Beautiful UI. HTTP, TCP, DNS, Docker monitoring. 90+ notification types. |
| [Grafana](https://github.com/grafana/grafana) | 65k+ | Open-source analytics and monitoring platform. | Industry standard dashboards. Works with Prometheus, Loki, etc. |
| [Prometheus](https://github.com/prometheus/prometheus) | 56k+ | Monitoring and alerting toolkit. | CNCF graduated. Time-series DB. Pull-based metrics. |

---

## Selection Criteria Applied
- Every repo above has 4,000+ GitHub stars (most have 20k+)
- All are actively maintained (commits within 2025-2026)
- Self-hostable with Docker or single binary
- Clear documentation and deployment guides
- Permissive or open-source licenses

## How to Choose
- **Simple self-hosting (Heroku-like)?** -> Coolify (modern, feature-rich) or Dokku (battle-tested)
- **Deploy to any VPS?** -> Kamal (Docker, zero-downtime) or Dokploy (modern UI)
- **AWS infrastructure as code?** -> SST (full-stack AWS framework)
- **Container management GUI?** -> Portainer (Docker + K8s dashboard)
- **Reverse proxy?** -> Caddy (auto-HTTPS, simple) or Traefik (auto-discovery)
- **Self-hosted GitHub?** -> Gitea (full-featured) or Forgejo (community fork)
- **CI/CD (self-hosted)?** -> Drone (container-native) or Woodpecker CI
- **Uptime monitoring?** -> Uptime Kuma (beautiful, 60k+ stars)
- **Dashboards?** -> Grafana (industry standard)
