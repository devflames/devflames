<div align="center">

# Albert Camings.
### Full-stack developer · Blockchain engineer
**Built end to end.**

I’m **devflames**, a senior full-stack developer building scalable products and the infrastructure behind them. From interfaces and backend systems to blockchain and deployment, I take the work from idea to implementation—and keep it running. My hands-on developer journey began in 2010, evolving from self-taught programming into full-stack development, Web3 infrastructure, and enterprise platform engineering.

📍 Philippines · Open to remote collaboration  
[Email Albert](mailto:devflames@gmail.com) · [GitHub](https://github.com/devflames) · [ApkayA ecosystem](#apkaya-ecosystem)

</div>

---

## About me

I taught myself programming starting in 2010, learning by building—from enterprise IT and game-server systems to full-stack development and blockchain engineering. I still like owning the work end to end: interfaces, services, infrastructure, and deployment.

That path now shapes three separate ApkayA initiatives: **ApkayASocial** for customer-owned social platforms, **ApkayA Web3Platform** for on-chain developer infrastructure, and **ApkayA Enterprise Platform** for a private enterprise control plane. Each solves a different problem, with its own architecture and build status. They are separate projects, not one product with interchangeable features.

| | |
|---|---|
| Based in | Philippines |
| Self-taught beginnings | 2010 |
| Also known as | devflames |
| Website listed on portfolio | ApkayA Inc |
| Focus | Web · Web3 · AI |

```ts
// building across the stack
const developer = {
  name: "Albert Camings",
  alias: "devflames",
  basedIn: "Philippines",
  started: 2010,
  focus: ["web", "Web3", "AI"]
};
// keep building
```

**Origin:** Self-taught developer building software, infrastructure, and platforms since 2010.  
**Practice:** Hands-on full-stack delivery.  
**Systems:** Platform engineering.  
**Specialism:** Blockchain / Web3.  
**Scale:** Enterprise and infrastructure.

---

## Selected work

Selected work across AI, blockchain, web, and game infrastructure. The three ApkayA startups are distinct platforms, each with a different audience and status.

### ApkayASocial
**Pre-deployment · Active build**

A customer-deployable social-platform foundation built for audience, data, branding, and monetization ownership. This is a greenfield TypeScript system, not a legacy fork; inherited legacy code is a functional reference only and no legacy source is used.

- **For:** Platform operators.
- **Built with:** TypeScript; Next.js 15, React 19, Fastify 5, PostgreSQL, Prisma 6, Socket.IO, Redis, BullMQ, Zod, Node.js.
- **Direction:** Potential commercially licensed customer deployment; product license is undecided.
- **Source:** Commercial direction; product under active build and not yet live.

### ApkayA Web3Platform
**v0 · Roadmap complete through Phase 9**

Open, self-hostable developer infrastructure for on-chain applications: transaction Engine, Insight indexer, dashboard, CLI, SDKs, and contracts.

- **For:** Developers building blockchain applications.
- **Architecture:** Independently deployable Engine, indexer, dashboard, and SDKs.
- **Direction:** Reusable tooling and self-hosted infrastructure.
- **Source:** Public official repository. The supplied portfolio copy did not include its URL.
- Roadmap completion is not a claim of production scale or adoption.

### ApkayA Enterprise Platform
**Private · v6.0.0 Enterprise Final**

A private multi-tenant control plane for security, cloud, hosting, billing, licensing, white-label tooling, and AI operations.

- **For:** MSPs, security teams, hosting providers, and enterprise resellers.
- **Architecture:** Next.js, NestJS, Prisma, cloud adapters, and separated dashboard, API, licensing services, data packages, and deployment tooling.
- **Source:** Private proprietary source; public documentation and SDK are available separately.
- **Status:** Production Ready according to the supplied README; not independently verified as a live deployment.

### ApkayA AI
An ongoing multi-provider AI and developer platform. Major features are implemented, with some production verification still outstanding.

### Other selected work

- **AevaPay / AXL Token — Web3, blockchain, full-stack:** Full-stack work connected to the AXL Token ecosystem and blockchain applications.
- **Guild of Guilds — GameFi, full-stack:** Full-stack work on a GameFi platform, bringing web application development together with blockchain-focused systems.
- **Chaucer’s Literary & Talent Bureau — web development:** Completed website; its domain has since been retired.
- **MMORPG infrastructure — game servers, backend:** Custom game-server systems and infrastructure work grounded in hands-on server development.

---

## ApkayA ecosystem

Three distinct initiatives with different audiences, architectures, repositories, and build stages. They belong to a broader ecosystem, but this does **not** imply that they already integrate or share features. Licensing, deployment, extensibility, identity, infrastructure, and developer tooling are strengths that could inform future work across the ecosystem; those are possibilities, not existing integrations or verified outcomes.

| Project | Focus | Audience | Repository / source | Current status |
|---|---|---|---|---|
| **ApkayASocial** | Social-platform product and infrastructure | Customer-deployable social-platform operators | Commercial licensed direction; product license undecided | Pre-deployment · under active build |
| **ApkayA Web3Platform** | On-chain developer infrastructure | Developers building blockchain applications | Public official repository | v0 roadmap complete through Phase 9 |
| **ApkayA Enterprise Platform** | Security, cloud, hosting, billing, licensing, white-label, and AI control plane | MSPs, security teams, hosting providers, enterprise resellers | Private proprietary source; public docs and SDK | v6.0.0 · Production Ready according to supplied README |

**Status legend:** “Production Ready” is README-stated; “v0 roadmap complete” means Phase 9; “pre-deployment / under active build” indicates ongoing work. Planned, parked, architecture-only, and deferred work is not shipped. Roadmap completion and repository claims are not live-deployment verification. Details here are summarized from the supplied project README descriptions, not independent audits.

### 01 / Social infrastructure — ApkayASocial

A greenfield TypeScript rebuild for commercial licensed distribution and customer deployment. It is not a legacy fork. The product thesis is to give customers a way to own their audience, data, branding, and monetization without platform lock-in.

**Owner / maintainer:** Albert Camings · ApkayA Inc.

#### Build status

Core domains are feature-complete across API and web layers, with the exceptions below. The latest README reports **1,768 tests across five suites**: API 1,025 (1,020 passing, 5 environment-gated skips), shared 480/480, web 233/233, realtime 10/10, and license server 20/20. This is test coverage, not a claim of live or production-ready deployment.

#### Product scope and current boundaries

Identity and authentication; profiles and social graph; posts and feeds; messaging; notifications and realtime; media, stories, camera and effects; forums, blogs, jobs, crowdfunding, movies and games; plans and verification; admin console; extensibility; and a separate license server.

- **Communities:** API layer complete; web UI pending.
- **Store and commerce:** Shared contract only; no shipped surface.
- **Live streaming and podcasts:** Architecture only.
- **Creator economy, marketplace, AI, native mobile, and Web3:** Planned.

#### Foundation and architecture

- Greenfield TypeScript rebuild rather than a legacy fork.
- Shared Zod contracts between API and web.
- Typed provider ports that report unavailable capabilities honestly.
- Centralized authorization boundaries and privacy policies.
- Ledger-first money modeling; payment gateway not yet wired.
- Signed extension distribution and a separate Ed25519 license control plane.
- **Experience → API:** Next.js 15 + React 19 web app → Fastify 5 REST API in a Node.js TypeScript monorepo.
- **Realtime + data:** Socket.IO delivery service; PostgreSQL through Prisma 6; shared Zod contracts between web and API.
- **Media + jobs:** sharp and ffmpeg processing, BullMQ + Redis queues, local or S3-compatible storage.
- **Licensing:** Separate Ed25519 license server for signed licenses, activation, and entitlements; not deployed.
- The customer app, shared contracts, data layer, and licensing control plane are maintained as separate architectural concerns.

#### Initial MVP, in plain language

Create an account; establish identity and privacy preferences; discover people and content; make connections; publish posts and stories; communicate in direct and group chats; receive notifications and build communities (community web UI still pending); operate with admin and monetization foundations (license deployment, entitlement wiring, and payment provider still pending).

#### Security and trust foundations

Implemented controls, not a guarantee of security or production readiness:

- Argon2id password hashing; 15-minute access JWTs and hashed one-time refresh tokens.
- TOTP 2FA and recovery codes; rate limiting.
- Privacy controls and viewer-bound signed media URLs.
- Secret scanning; no private signing keys in the customer application.

#### Commercial architecture and next steps

The customer application is under active build. The license server is code-complete with 20/20 tests but not deployed. A release and distribution service is architecture-only; the web installer is deferred; the product license is undecided.

Deployment is parked by owner direction while feature completion continues. Future or parked work includes a live database, production hosting, payment provider wiring, end-to-end live verification, email/push delivery, entitlement consumption, license-server deployment, production hardening, creator economy, marketplace, live streaming, podcasting, advertising, AI, native mobile, and Web3. Advertising architecture has inert slices only; no advertising feature is shipped.

### 02 / Developer infrastructure — ApkayA Web3Platform

A separate, open, self-hostable foundation for on-chain applications—contracts, wallets, and a transaction backend. The supplied v0 roadmap is complete through Phase 9; that does not establish production scale or adoption.

#### Engine-first architecture

- **Engine:** Independently deployable REST transaction backend with a durable Postgres-backed queue, backend wallets, transaction signing, sending, and status.
- **Insight:** Read-only EVM event indexer and query API for token balances, NFT ownership, and transfers.
- **Dashboard:** React developer UI for projects, API keys, backend wallets, and deployments.
- **CLI:** `apkaya create` and `apkaya deploy`, alongside login, wallet, transaction, and API-key commands.

#### SDKs, contracts, and access

Packages cover a TypeScript SDK; React Native and Flutter SDKs; Unity UPM and Unreal plugins; wallet connect, in-app email wallet and SIWE; ERC20, ERC721 and ERC1155 Solidity templates with extensions; and deployment helpers. Connect includes an end-user wallet modal. Bridge includes BuyWidget and SwapWidget through Coinbase CDP.

API keys are hashed per customer and individually revocable, managed through a separate admin-only key—not one shared static secret.

#### v0 roadmap · completed through Phase 9

Engine queue, backend wallets and send/status endpoints → ERC20/ERC721 templates and deployment → thin TypeScript SDK → Dashboard → CLI login/create/deploy/wallet/tx/apikey → Connect and SIWE → Bridge widgets → Insight indexing → self-host polish (Docker Compose and QUICKSTART) → React Native and Flutter → Unity and Unreal → Solana ChainAdapter, wallets/transfers and Insight slot indexer.

**Local development references only:** Docker Compose or native development; Dashboard `localhost:5173`, Engine `:3005`, Insight `:3006`. These are not public deployment endpoints.

The reusable Engine-first foundation could support developer tooling across contract deployment, wallet connections, indexing, mobile, game engines, and multiple chains. These are product possibilities, not claims of usage or commercial outcomes. See the official public repository for source and project details.

### 03 / Private commercial control plane — ApkayA Enterprise Platform

**v6.0.0 Enterprise Final · Production Ready according to supplied README.** Private proprietary source; public documentation and SDK are available separately. The stated release status is not independent assurance of live deployment.

#### At a glance

The repository description reports 69 Next.js dashboard pages plus middleware and dynamic module router; 60+ sidebar entries in six groups; 40+ NestJS API modules under `/api/v1`; 101+ Prisma models; 14 cloud-provider adapters; 241 API unit tests across 69 suites; 15 license-server tests; and Playwright E2E. Listed payment options include Stripe, PayPal, Razorpay, wallet, coupons, and metered billing. These are repository-reported figures.

#### Security and WAF

OWASP CRS inspection, firewall events, live attack feed, IP/ASN/geo blocking, bot protection, rate limiting, DDoS dashboard, API security, incident center, threat map, custom rules, and real-time analytics.

**Listed controls, not guarantees:** JWT and bcrypt; RBAC across nine roles; plan-based feature gating; organization-scoped multi-tenancy; Helmet, CORS, and throttling; audit logs; Stripe webhook verification; AES-256-GCM for cloud credentials; HMAC verification for plugins, themes, and updates; service-key protection for license-server APIs.

#### Cloud, hosting, and business

Fourteen adapters: AWS, GCP, Azure, DigitalOcean, Vultr, Linode, OVH, Hetzner, Oracle, Alibaba, Cloudflare, BunnyCDN, Wasabi, and Backblaze. Includes encrypted credential handling, async sync jobs, DNS/SSL tools, a hosting marketplace, server-side cart, wallet checkout, provisioning, bundles, coupons, and an order lifecycle.

Billing covers Stripe, PayPal, Razorpay, PayMongo, Coinbase Commerce, and wallet payments, plus dunning and invoicing. Reseller tiers, sub-resellers, differential commission chains, per-reseller branding, custom domains, wallet and payouts, referral registration, and an admin console form the white-label direction. MSSP console, SSO/SAML, compliance, and edition-driven flags round out the business platform.

#### Extensibility, licensing, and AI

Signed plugin marketplace with HMAC-verified manifests and semver lifecycle; theme marketplace with design tokens, preview, and licensing; enterprise updater with channels, backups, rollback, and signature verification. The standalone license server has admin/customer portals, machine-bound activation, and a service-key API; customer portal covers licenses, billing, downloads, and support.

AI operations at `/ai-operations` cover security analysis, threat detection, cost optimization, capacity forecasting, billing insights, and a support assistant.

#### Architecture and delivery

- **Dashboard · `:3000`:** Next.js 14 App Router, React 18, TypeScript, and Tailwind CSS.
- **API · `:4000`:** NestJS 10, Express, class-validator DTOs, and JWT authentication.
- **Data and jobs:** PostgreSQL 16 + Prisma ORM 5; Redis 7 + BullMQ; metrics, tracing, and compression.
- **Optional licensing:** License server `:4100` and license portal `:3100`.
- **Deployment:** Docker Compose development/production, Kubernetes Helm HA/autoscaling, and Terraform AWS multi-region; installation wizard; Prometheus, OpenTelemetry, Grafana, and Loki; GitHub Actions CI/CD and Docker multi-stage builds.

The dashboard, API, licensing services, data packages, and deployment tooling are separated by responsibility. Architecture descriptions are not public endpoints.

#### Commercial direction and potential

The private commercial source monorepo is proprietary, with access restricted to ApkayA Enterprise Inc. maintainers and licensed customers. A unified multi-tenant control plane could support recurring licensed distribution, white-label and reseller expansion, cloud/hosting marketplace workflows, signed extensibility, and AI-assisted operations. These are intended product possibilities, not verified commercial outcomes. Public documentation and SDK are separate from platform source.

---

## Technical capabilities

Grouped by where they fit in the build—from interfaces and services to infrastructure and Web3.

| Area | Technologies and capabilities |
|---|---|
| Frontend & languages | JavaScript, TypeScript, React, Next.js, Vue, Angular, C++, C# |
| Backend & data | Node.js, NestJS, Laravel, PostgreSQL, MongoDB |
| Cloud & delivery | Docker, AWS, Azure, GCP, CI/CD |
| Blockchain | Web3, smart contracts |
| Data & queues | Prisma, Redis, BullMQ, indexing |
| Security | RBAC, WAF, signed licensing, privacy controls |
| Realtime & media | Socket.IO, messaging, media processing |
| Deployment | Docker Compose, Kubernetes, Terraform, CI/CD |

---

## Experience

A hands-on path across full-stack development, blockchain engineering, platform infrastructure, and enterprise systems.

- **2010 · Self-taught beginnings:** Started learning programming by building, and kept moving toward deeper ownership of the systems behind each product.
- **Enterprise IT & game servers:** Hands-on work across enterprise systems, custom MMORPG server infrastructure, and backend development.
- **Full-stack & blockchain:** Web applications, AevaPay / AXL Token, and Guild of Guilds brought interfaces, services, and Web3 systems together.
- **ApkayASocial:** Building a customer-deployable social-platform product and foundation, designed so customers can own their platform and audience.
- **ApkayA Web3Platform:** Developing self-hostable developer infrastructure for on-chain applications, from transaction services to indexing and tooling.
- **ApkayA Enterprise Platform:** Working on a separate, private commercial control plane for WAF, cloud, hosting, billing, licensing, white-label, and AI operations.

---

## Contact

I’m open to remote opportunities, client projects, and international collaboration. If you have a project or role in mind, send me a note.

- **Email:** [devflames@gmail.com](mailto:devflames@gmail.com)
- **GitHub:** [github.com/devflames](https://github.com/devflames)
- **Public work:** Explore the public repositories on [GitHub](https://github.com/devflames).
- **Upcoming venture:** ApkayA Inc.

---

<div align="center">

© Albert Camings · devflames

*Built end to end. Keep building.*

</div>

---

> **Portfolio source note:** This profile README reflects the portfolio copy supplied by Albert Camings. Project statuses, test counts, architecture details, and security controls are presented as described in that supplied material; they have not been independently audited or verified as live deployments.
