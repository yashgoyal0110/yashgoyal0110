<div align="center">

# Yash Goyal

**Backend & Infrastructure Engineer** — distributed systems, real-time control loops, and the observability to prove they work.

<p>
  <a href="https://portfolio.yashgoyal.sbs"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=22C55E" alt="Portfolio" /></a>
  <a href="https://cv.yashgoyal.sbs"><img src="https://img.shields.io/badge/Résumé-0D1117?style=for-the-badge&logo=readdotcv&logoColor=22C55E" alt="Résumé" /></a>
  <a href="https://www.linkedin.com/in/yashgoyal0110"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=22C55E" alt="LinkedIn" /></a>
  <a href="https://x.com/yashgoyal0110"><img src="https://img.shields.io/badge/Twitter-0D1117?style=for-the-badge&logo=x&logoColor=22C55E" alt="Twitter" /></a>
  <a href="mailto:yashgoyal.dev@zohomail.in"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=maildotru&logoColor=22C55E" alt="Email" /></a>
</p>

<p>
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2600&pause=700&color=22C55E&center=true&vCenter=true&width=620&lines=Teleoperating+robot+arms+at+250+Hz;Keeping+~15+Kubernetes+clusters+alive;Shipping+to+OWASP+%2F+LitmusChaos+%2F+Palisadoes" alt="Typing SVG" />
  <br />
  <img src="https://komarev.com/ghpvc/?username=yashgoyal0110&label=Profile%20Views&color=22c55e&style=flat-square" alt="Profile Views" />
</p>

</div>

---

## 🤖 What I'm Building

**Founding Engineering Intern @ [mrfood.ai](https://mrfood.ai)** · *June 2026 – Present*

Real-time bimanual teleoperation for 2× 6-DOF AgileX PiPER arms driven from Meta Quest controllers:

- Controller poses → **250 Hz** Pink/Pinocchio differential-IK solver → **100 Hz** SocketCAN control loop, with velocity/accel limiting, jump rejection, and hold-on-fault safety at the hardware boundary.
- Remote-resilient over lossy links: 4 interchangeable network transports, per-frame `frame_seq` packet-drop detection, self-healing CAN fault recovery.
- Owned the data pipeline: 4 concurrent video paths (WebRTC, cloud RTC, GCS recorder), telemetry → BigQuery, RGBD → GCS, Prometheus + Grafana + Slack alerting, and a LeRobot writer pushing training-ready datasets to HuggingFace.

<details>
<summary><b>Previously</b></summary>

**Forward Deployed Engineer @ Emergent Labs** · *Mar 2026 – May 2026*
Primary technical engineer for 50+ customers on production apps — Kubernetes crashloops/scheduling, reverse-proxy and container runtime failures across ~15 clusters. 200+ infra incidents resolved, ~45% faster support turnaround, 99.9% uptime held.

**Software Engineer @ Successship Technologies** · *Jan 2025 – July 2025*
Built a distributor management platform end-to-end (inventory classification, double-entry ledger, payouts) on Spring Boot / Redis / PostgreSQL — drove the company's first client signing and first successful payout. Cut server costs ~20% via multi-stage Docker builds across 5+ services.

</details>

---

## 🌱 Open Source

I contribute where the infrastructure is: CI/CD, observability, and developer experience.

| Org | What I shipped |
| :-- | :-- |
| **[OWASP Nest](https://github.com/OWASP/Nest)** | Django models + tests for new features, SlackBot commands, schema validations, frontend/UI work |
| **[LitmusChaos](https://github.com/litmuschaos)** | Docker linting in CI quality gates, streamlined contributor setup scripts |
| **[Palisadoes Foundation](https://github.com/PalisadoesFoundation)** | Reusable CI/CD workflows, large-scale repo migration, OpenTelemetry observability |

📊 **[Live PR Dashboard →](https://portfolio.yashgoyal.sbs)**

---

## 🚀 Projects

### [Axon](https://github.com/yashgoyal0110) — multi-tenant WhatsApp automation SaaS
`NestJS` `React` `PostgreSQL` `Prisma` `Redis` `Gemini` `Docker` `GCP`

Drag-and-drop chatbot canvas across 8 node types with workspace-scoped RBAC and immutable published flow versions. One provider-agnostic conversation engine serves Meta Cloud API, Twilio, and a credential-free sandbox — HMAC-SHA256/SHA1 webhook verification, Redis-backed redelivery de-dup, 24h session windows, Gemini fallback for off-script queries. Ships as a single Docker image (API + SPA, one port) behind Caddy with AES-256-GCM credential encryption and rotating refresh tokens.

### [Wanderlust](https://github.com/yashgoyal0110) — 3-tier app on self-managed Kubernetes
`AWS EC2` `Kubernetes` `Docker` `Node.js` `MongoDB` `Redis`

Cloud-native deployment on a Kubernetes cluster provisioned by hand on EC2 — Deployments, Services, ConfigMaps. Built DevOps-first, optimizing for infrastructure reliability over feature count.

---

## 🛠️ Stack

<div align="center">

**Languages** &nbsp;·&nbsp; <img src="https://skillicons.dev/icons?i=python,java,ts,js" height="32" />

**Backend & Frontend** &nbsp;·&nbsp; <img src="https://skillicons.dev/icons?i=spring,nodejs,express,nestjs,react" height="32" />

**Data** &nbsp;·&nbsp; <img src="https://skillicons.dev/icons?i=postgresql,mongodb,redis" height="32" />

**Cloud & Ops** &nbsp;·&nbsp; <img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,gcp,grafana,prometheus,linux,nginx,githubactions" height="32" />

</div>

---

## 📈 Stats

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=yashgoyal0110&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=22C55E&icon_color=3B82F6&text_color=F8FAFC" alt="GitHub Stats" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yashgoyal0110&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=22C55E&text_color=F8FAFC" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=yashgoyal0110&hide_border=true&background=0D1117&stroke=1F2937&ring=22C55E&fire=22C55E&currStreakLabel=F8FAFC&sideLabels=F8FAFC&currStreakNum=22C55E&sideNums=3B82F6&dates=94A3B8" alt="Streak" />
</div>

---

## 🎓 Education & Achievements

**B.Tech, CS & AI** — Rishihood University · *Aug 2023 – Present* · CGPA 8.5/10

- 🏅 **GDG on Campus '24 Lead** — ran flagship tech events, workshops, and community initiatives with Google's GDG network
- 🥇 **AIR 1200**, ICPC Prelims 2023

---

<div align="center">

**Building something that needs to stay up at 3am?** &nbsp;·&nbsp; [Let's talk →](mailto:yashgoyal.dev@zohomail.in)

<sub>⭐ Star anything you find useful.</sub>

</div>
