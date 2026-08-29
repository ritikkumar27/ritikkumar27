# Hey, I'm Ritik Kumar 👋

### Backend Developer • DevOps Enthusiast • Homelab Builder

I’m a Computer Science student who likes learning by **actually building things and then figuring out why they break**.

My main focus is backend development with **TypeScript, Node.js and NestJS**, while also learning how those applications are built, deployed, monitored and operated in real environments.

A lot of my learning happens in my homelab — an old PC running Linux that I use to host applications, experiment with infrastructure, break deployments, troubleshoot networking issues and learn how systems behave outside of localhost.

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00F7FF&center=true&vCenter=true&width=650&lines=Building+backend+systems;Learning+distributed+systems;Running+my+own+infrastructure;Docker+%7C+Linux+%7C+CI%2FCD;Learning+by+building+and+breaking" />
</p>

---

## What I Work With

### Backend

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square\&logo=node.js\&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square\&logo=nestjs\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square\&logo=prisma\&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square\&logo=typeorm\&logoColor=white)

**Things I work on:** REST APIs · PostgreSQL · Redis · caching · background jobs · queues · workers · asynchronous processing

### Infrastructure & DevOps

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square\&logo=ubuntu\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=github-actions\&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square\&logo=caddy\&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square\&logo=cloudflare\&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square\&logo=amazon-aws\&logoColor=white)

**Things I work on:** Docker · Docker Compose · CI/CD · Linux servers · reverse proxies · DNS · HTTPS · Cloudflare Tunnel · self-hosted runners · container networking

<!-- 
### Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square\&logo=prometheus\&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square\&logo=grafana\&logoColor=white)

**Things I explore:** metrics · dashboards · container monitoring · resource usage · system observability -->

### Development

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square\&logo=gnubash\&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square\&logo=turborepo\&logoColor=white)

---

## 🚀 Things I've Built

### 🎬 MediaForce

An asynchronous media processing platform built around background jobs rather than keeping long-running work inside API requests.

* NestJS + TypeScript backend
* PostgreSQL + TypeORM
* Redis + BullMQ workers
* Turborepo monorepo
* Multi-stage Docker builds
* GitHub Actions → GHCR → self-hosted deployment
* Caddy + Cloudflare Tunnel
* Running on my own Linux server

**Currently one of my main projects for learning backend architecture and distributed systems.**

---

### 🏠 HomeLab

My homelab is where most of my infrastructure learning happens.

I run an Ubuntu Server machine and use it to host applications and services while experimenting with:

* Docker & Docker Compose
* Caddy reverse proxy
* Cloudflare Tunnel
* Tailscale
* GitHub Actions self-hosted runner
* Persistent storage and Docker networking
* Linux administration and troubleshooting

The goal isn't just to keep services running — it's to understand **what happens underneath them**.

---

### 🔗 URL Shortener

A backend project I use to explore system design beyond a basic CRUD application.

**NestJS · PostgreSQL · Prisma · Redis · Docker**

Used it to experiment with caching, database indexing, redirects, rate limiting, analytics and how background processing could be introduced as the system grows.

---

### 🎮 Modded Minecraft Server

A heavily modded Fabric server that became another practical infrastructure project.

* 146-mod Fabric 1.21.1 server
* Docker deployment
* Persistent world storage
* JVM memory management
* Lithium + FerriteCore optimization
* Automated Bash + cron backups
* RCON-based world saves
* SSH + tmux administration

It taught me a surprising amount about **stateful services, resource constraints, backups and keeping a server running reliably**.

---

## 🏗️ How I Learn

I don't learn infrastructure by memorizing commands.

I usually follow this cycle:

```text
Build
  ↓
Deploy
  ↓
Break something
  ↓
Read logs (Ask LLM)
  ↓
Figure out why
  ↓
Fix it
  ↓
Document it
  ↓
Repeat
```

That's also why I keep a homelab — it gives me somewhere to experiment with things that are difficult to understand from tutorials alone.

---

## 📚 Currently Learning

* System Design
* Distributed Systems
* Backend Architecture
* Redis & asynchronous processing
* BullMQ, workers & queues
* Linux internals
* Docker & container networking
* CI/CD
* Monitoring & observability
* Infrastructure and reliability

---

## 🖥️ My Homelab

```text
                    Internet
                       │
                       ▼
               ┌───────────────┐
               │ Cloudflare    │
               │ Tunnel        │
               └───────┬───────┘
                       │
                       ▼
               ┌───────────────┐
               │ Caddy         │
               │ Reverse Proxy │
               └───────┬───────┘
                       │
                       ▼
              ┌─────────────────┐
              │   Ubuntu Server │
              │                 │
              │     Docker      │
              │   ┌──────────┐  │
              │   │ Services │  │
              │   └──────────┘  │
              │                 │
              └─────────────────┘
```

**Current hardware:** Intel i5 3rd gen · 8GB DDR4 RAM · SSD 256GB + HDD 500GB

<p align="center">
  <i>Building things. Breaking things. Learning why they broke.</i>
</p>
