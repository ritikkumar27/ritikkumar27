<!--
  Ritik Kumar · GitHub Profile README
  username: ritikkumar27  ·  change `ritikkumar27` in any image URL to switch accounts
  dynamic widgets: github-readme-stats + streak-stats, wired to the public PAT-less endpoints.
  If one lags, it degrades to an empty table cell, not a broken gap.
-->

<table border="0" cellspacing="0" cellpadding="0" width="100%">
<tr>
<!-- ==================== LEFT: IDENTITY ==================== -->
<td width="52%" valign="top" style="padding-right: 18px;">


**Ritik Kumar** · CS undergrad

**Backend Developer** &nbsp;•&nbsp; **DevOps Enthusiast** &nbsp;•&nbsp; **Homelab Builder**

&nbsp;

> *"learning by actually building things and then figuring out why they break"*

&nbsp;

I build backends and the infrastructure they run on — not just the code that serves an API, but the **queues, caches, proxies, DNS and CI/CD pipelines** that keep it alive at 3am.

&nbsp;

<p align="left">
  <a href="https://github.com/ritikkumar27"><img src="https://img.shields.io/badge/Profile-0D1117?style=flat-square&logo=github&logoColor=00F7FF" alt="GitHub profile"></a>
  <a href="mailto:hello@ritikkumar.dev"><img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=00F7FF" alt="Email me"></a>
  <a href="https://github.com/ritikkumar27?tab=repositories&sort=stargazers"><img src="https://img.shields.io/badge/Repositories-0D1117?style=flat-square&logo=github&logoColor=00F7FF" alt="GitHub repositories"></a>
</p>

</td>
<!-- ==================== RIGHT: TYPING ==================== -->
<!-- <td width="48%" valign="top">

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&pause=1500&color=00F7FF&center=true&vCenter=true&repeat=true&width=440&height=110&lines=Building+backend+systems...;Learning+distributed+systems...;Running+my+own+infrastructure...;Docker+%7C+Linux+%7C+CI%2FCD;Learning+by+building+and+breaking" alt="Typing animation: Building backend systems; Learning distributed systems; Running my own infrastructure; Docker | Linux | CI/CD; Learning by building and breaking" />
</p>

</td> -->
</tr>
</table>

---

<h3 align="center">⚡ Stack</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=typescript,nodejs,nestjs,postgres,redis,prisma&theme=dark&perline=6" alt="Core backend stack: TypeScript, Node.js, NestJS, PostgreSQL, Redis, Prisma" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,docker,githubactions,cloudflare,aws&theme=dark&perline=6" alt="Infrastructure stack: Linux, Ubuntu, Docker, GitHub Actions, Cloudflare, AWS" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,bash&theme=dark&perline=6" />
  &nbsp;&nbsp;
  <img src="https://img.shields.io/badge/TypeORM-FE0803?style=flat-square&logo=typeorm&logoColor=white" alt="TypeORM">
  &nbsp;
  <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white" alt="Caddy">
  &nbsp;
  <img src="https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white" alt="Turborepo">
</p>

<p align="center">
  <sub>
    <b>day to day:</b> NestJS · PostgreSQL · Redis + BullMQ · Docker Compose · GitHub Actions<br>
    <b>operating:</b> Linux servers · reverse proxies · DNS / HTTPS · Cloudflare Tunnel · self-hosted runners · container networking
  </sub>
</p>

---

<h3 align="center">🚀 Featured Projects</h3>

<table border="0" cellspacing="0" cellpadding="0" width="100%">
<tr>
<td width="50%" valign="top" style="padding-right: 14px;">

### 🎬 MediaForce
**Async media processing platform** · [↗ repo](https://github.com/ritikkumar27/media-force)

Work doesn't happen inside the request. Every upload lands as a **job in a queue**, and a fleet of workers picks it up.

```text
POST /upload
   └─▶ BullMQ queue ──▶ worker ──▶ object store
              │
              ├─▶ Postgres  (job state)
              └─▶ Redis     (cache + retries)
```

**TypeScript · NestJS · PostgreSQL + TypeORM · Redis + BullMQ · Turborepo monorepo · multi-stage Docker · GitHub Actions → GHCR → self-hosted runner · Caddy + Cloudflare Tunnel**

Runs on my own Linux server — where I learn **backend architecture and distributed systems**.

</td>
<td width="50%" valign="top">

### 🏠 Homelab
**The home datacenter** · [↗ dotfiles](https://github.com/ritikkumar27/dotFiles)

An old PC that teaches me what happens **underneath** services — the parts tutorials skip.

```text
 Intel i5 (3rd gen) · 8 GB DDR4
 SSD 256 GB  +  HDD 500 GB
 Ubuntu Server · always on
```

**Ubuntu Server · Docker + Compose · Caddy reverse proxy · Cloudflare Tunnel · Tailscale mesh · GitHub Actions self-hosted runner · storage + networking experiments**

</td>
</tr>
<tr>
<td width="50%" valign="top" style="padding-right: 14px;">

### 🔗 URL Shortener
**System design practice, not CRUD** · [↗ repo](https://github.com/ritikkumar27/URL-shortener-production-ready)

Used it to explore what happens **at scale** — where a 300-line tutorial project starts to hurt.

```text
 click → Caddy → NestJS
   ├─▶ Redis hit?  →  301 redirect  (~1 ms)
   └─▶ miss  →  Postgres indexed lookup
              →  background analytics job
```

**NestJS · PostgreSQL + Prisma · Redis · rate limiting · DB indexing · background processing**

</td>
<td width="50%" valign="top">

### 🎮 Modded Minecraft Server
**Stateful services on a budget**

146 mods, one CPU, 8 GB RAM — a masterclass in **resource constraints**.

```text
 146 mods · Fabric 1.21.1
 JVM tuned · Lithium + FerriteCore
 cron backup → off-box
 RCON autosave · ssh + tmux
```

**Docker · JVM memory tuning · Lithium + FerriteCore · automated bash + cron backups · RCON · SSH + tmux**

Lessons that transfer to real infra: **stateful services, resource limits, backups, reliability.**

</td>
</tr>
</table>

---

<h3 align="center">🔁 The Learning Loop</h3>

<p align="center">
  <sub>I don't learn infrastructure by memorizing commands. I build, deploy, break, and read the logs.</sub>
</p>

```text
BUILD ──▶ DEPLOY ──▶ BREAK ──▶ READ LOGS ──▶ WHY?
                                            │
   ┌────────────────────────────────────────┘
   │
   ▼
   FIX ──▶ DOCUMENT ──▶ (then back to BUILD)

   it loops. that's the whole point.
```

---

<h3 align="center">🧠 Now Learning</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,redis,postgres,docker,linux,aws&theme=dark&perline=6" alt="Technologies I'm currently learning: TypeScript, Redis, PostgreSQL, Docker, Linux, AWS" />
</p>

<table border="0" cellspacing="0" cellpadding="0" width="100%">
<tr>
<td width="33%" valign="top">

**Systems**
&nbsp;
- System design
- Distributed systems
- Linux internals
- Container networking

</td>
<td width="33%" valign="top">

**Backend**
&nbsp;
- Redis & BullMQ
- Queues & workers
- Async processing
- Caching strategies

</td>
<td width="33%" valign="top">

**Operations**
&nbsp;
- CI/CD pipelines
- Observability
- Monitoring
- Infrastructure reliability

</td>
</tr>
</table>

---

<h3 align="center">🛠️ Homelab Architecture</h3>

<p align="center">
  <sub>how a request reaches my homelab — with no open inbound ports on my router</sub>
</p>

```text
        ┌───────────────┐
        │ INTERNET      │
        │ public DNS    │
        │ client → :443 │
        └───────────────┘
        ╎
        ▼
        ┌────────────────────┐
        │ CLOUDFLARE         │
        │ outbound tunnel    │
        │ zero inbound ports │
        └────────────────────┘
        ╎
        ▼
        ┌──────────────────┐
        │ CADDY            │
        │ reverse proxy    │
        │ auto TLS + HTTPS │
        └──────────────────┘
        ╎
        ▼
┌────────────────────────────────────────────────────────┐
│          UBUNTU SERVER  ·  DOCKER  ·  HOMELAB          │
│                                                        │
│ ┌─────────────┐   ┌────────────────┐   ┌────────────┐  │
│ │ NestJS APIs │   │ Redis + BullMQ │   │ PostgreSQL │  │
│ └─────────────┘   └────────────────┘   └────────────┘  │
│                                                        │
└────────────────────────────────────────────────────────┘
```

**The path, in one line:** a request resolves to Cloudflare → rides an outbound tunnel (so my router opens **zero** inbound ports) → Caddy terminates TLS and proxies by hostname → lands in a container on the Ubuntu box.

**Where the interesting parts live:**
- **Cloudflare Tunnel** — no port forwarding, no exposed IP; the tunnel is an outbound persistent connection.
- **Caddy** — automatic TLS + reverse proxy by hostname, so adding a service means one block in a `Caddyfile`, not a port map.
- **Docker + Compose** — each service in its own network namespace; cross-service traffic only where a port is published.
- **Tailscale** — a second path in for admin (SSH) that doesn't touch the public route at all.

&nbsp;

<table border="0" cellspacing="0" cellpadding="0" width="100%">
<tr>
<td width="50%" valign="top" style="padding-right: 14px;">

**hardware**

```text
┌───────────────────────────┐
│ THE HOMELAB               │
│ Ubuntu Server · always on │
└───────────────────────────┘
     ╎
     ╎  zero inbound ports on the router
     ▼
┌────────────────────────────────┐
│ CPU    Intel i5 (3rd gen)      │
│ RAM    8 GB DDR4               │
│ DISK   SSD 256 GB + HDD 500 GB │
└────────────────────────────────┘
```

</td>
<td width="50%" valign="top">

**why bother**

> An old i5 with 8 GB RAM forces real engineering decisions: what fits in memory, what gets swapped to the HDD, and what a 3rd-gen CPU does to a JIT'd workload at 2am.

That constraint is the point. A fleet of managed services hides the tradeoffs — a 146-mod Minecraft server, a Postgres instance, a NestJS API and a Redis queue fighting over 8 cores teaches you what a **memory budget** actually is, and why **backups and resource limits** aren't optional on stateful workloads.

</td>
</tr>
</table>

---



<!--
<p align="center"><sub>README handcrafted in Vim. Built, broken, and rebuilt — many times.</sub></p>
-->
