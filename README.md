# Blazer


# Hi, I'm Josh 👋

**Full-stack & systems engineer.** I build and ship across the TypeScript ecosystem, cloud infrastructure, and web3 — from startup MVPs to production distributed systems.

I care about clean, maintainable code, security by default, and software that holds up under real load.

- 🔭 Building distributed systems in **Go** and **Rust**, and going deeper on **web3** (Rust smart contracts, ZK proofs)
- 🌍 Based in Nigeria (**UTC+1**) · open to **remote roles** and **freelance**
- 📫 Reach me: **joshblazerwillie@gmail.com**
- 🔗 [Portfolio](https://joshblazer.vercel.app) · [LinkedIn](https://linkedin.com/in/joshua-willie-3920181b9)

---

## 🧰 Tech

**Languages:** TypeScript · JavaScript · Rust · Go · Python · SQL
**Frontend:** React · Next.js · Tailwind CSS
**Backend:** Node.js · PostgreSQL · Prisma · Redis
**Cloud & Infra:** AWS (Lambda, SAM, DynamoDB, EventBridge, STS) · Docker · GitHub Actions · Linux
**Web3:** Rust smart-contract development · Solidity · ZK proofs (Circom, Noir) *— actively building*

---

## 🚀 Featured projects

### [Sluice](https://github.com/JoshBlazer/sluice) — Distributed job scheduler
`Go · PostgreSQL · Redis · etcd`
Horizontally scalable, durable scheduler with at-least-once delivery and idempotency keys. PostgreSQL as the durable source of truth with a Redis hot path; leader election via etcd for high availability. Instrumented with Prometheus metrics and OpenTelemetry traces. Designed for **10k+ jobs/sec** on commodity hardware.

### [Cloud Shield](https://github.com/JoshBlazer/cloud-shield) — Serverless cloud-security posture manager (CSPM)
`Python · AWS SAM · Lambda · DynamoDB`
Continuously audits AWS accounts against security policies on an hourly schedule. Assumes read-only roles into member accounts via STS for multi-account coverage; tracks every finding through a full lifecycle (acknowledge / snooze / exempt / resolve) with an append-only audit trail. Run-over-run diffing distinguishes new, regressed, and exempted findings. **104 passing tests.**

### [Velora](https://github.com/JoshBlazer/velora) — Kanban board app
`Next.js · Prisma · NextAuth · PostgreSQL`
Drag-and-drop board with label and priority management, plus full credential auth including email verification and password-reset flows.

### [Best Secondary](https://github.com/JoshBlazer/best-secondary) — Educational platform
`Next.js · TypeScript · Tailwind CSS`
Educational web platform for secondary-school students — designed, built, and deployed to production.

---

*Currently a B.Tech Software Engineering student at FUTA (Federal University of Technology, Akure), shipping production work alongside my degree.*
