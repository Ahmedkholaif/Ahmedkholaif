<div align="center">

<a href="https://ahmedkholaif.github.io"><img src="avatar-circle.png" width="150" alt="Ahmad Kholaif"></a>

# Ahmad Kholaif

**Senior Full-Stack Engineer** · Cairo, Egypt · Remote

<a href="https://ahmedkholaif.github.io"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2600&pause=900&color=F05A28&center=true&vCenter=true&width=480&lines=I+build+payment+platforms;I+build+cloud+migrations;I+build+data+pipelines;I+build+third-party+integrations" alt="I build payment platforms, cloud migrations, data pipelines, integrations"></a>

<a href="https://ahmedkholaif.github.io"><img src="https://img.shields.io/badge/Portfolio-ahmedkholaif.github.io-e11d48?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/ahmedkholaif"><img src="https://img.shields.io/badge/LinkedIn-ahmedkholaif-f05a28?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:ahmad.kholaif2@gmail.com"><img src="https://img.shields.io/badge/Email-ahmad.kholaif2-f59e0b?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://ahmedkholaif.github.io/Ahmad_Kholaif_CV.pdf"><img src="https://img.shields.io/badge/CV-Download-15161a?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Download CV"></a>

</div>

---

I've spent 7+ years building backend services, React front ends and cloud infrastructure across **fintech, food-tech and the public sector**. My track record includes cutting cloud costs, hardening reliability and leading migrations. I work AI-first every day with Claude Code, Cursor and Codex.

| | |
|---|---|
| 💳 **Now** | Senior Software Engineer at **Fena**, working on open banking and e-commerce: payments, invoicing, and Xero / QuickBooks / Shopify integrations in Go and Node.js |
| 🍳 **Before** | Founding engineer at **The Food Lab** (led the GCP → AWS migration, built Airbyte + dbt pipelines) |
| 🏛️ | **IBM**: TAMM Abu Dhabi and TradeLens; 🏆 IBM Excellence Award |
| ⚡ | **Fixed Solutions**: Egypt's electricity modernization project (EEHC / Digital Egypt) |

### 🛠️ Stack

<p>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS">
<img src="https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white" alt="React">
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<br>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
<img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis">
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ">
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka">
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt">
<br>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
<img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana">
</p>

### ⭐ Featured: two small, production-grade systems

**Ledger platform**: one API contract, two interchangeable backends, one console. CI proves the backends are interchangeable on a shared database.

| Project | Stack | Highlights |
|---|---|---|
| **[ledgerd](https://github.com/Ahmedkholaif/ledgerd)** | Go · PostgreSQL | Idempotent transfers, deadlock-free locking, DB-enforced invariants, concurrency stress tests |
| **[ledger-nest](https://github.com/Ahmedkholaif/ledger-nest)** | NestJS · TypeScript | Drop-in replacement for ledgerd: DI and dynamic modules, DTO validation, generated OpenAPI, interceptors, guards |
| **[ledger-console](https://github.com/Ahmedkholaif/ledger-console)** | Next.js 16 · React 19 | Cache Components and PPR, Server Actions with `updateTag`, double-submit-safe transfers, streaming CSV, Playwright vs both backends |

**Webhook platform**: deliver webhooks reliably, then watch them land live.

| Project | Stack | Highlights |
|---|---|---|
| **[hookline](https://github.com/Ahmedkholaif/hookline)** | Go · PostgreSQL | `SKIP LOCKED` queue with leases, full-jitter retries, dead-letter queue, circuit breaker, HMAC signing |
| **[hookscope](https://github.com/Ahmedkholaif/hookscope)** | Node.js · React 19 | Zero-dependency Node server: SSE fan-out with `Last-Event-ID` resume, backpressure, streamed bodies; live React UI |

### 📂 Earlier side projects

| Project | What it is | Stack |
|---|---|---|
| [Voucher Pool API](https://github.com/Ahmedkholaif/simple-nestjs) | Customer vouchers & special offers service | NestJS, PostgreSQL, Redis, Docker |
| [Mailing Microservices](https://github.com/Ahmedkholaif/simple-mailing-microservices) | API + mailer worker over a message queue | NestJS, RabbitMQ, MySQL, React |
| [Async Job Manager](https://github.com/Ahmedkholaif/unspalsh-job-app) | Delayed jobs with live results over WebSockets | Express, WebSocket, React |
| [ITI Reads](https://github.com/Ahmedkholaif/MERN_ITI_READS) | Goodreads-style book tracker | MERN |

### 🌍 Languages

🇪🇬 **Arabic**: native  ·  🇬🇧 **English**: professional working proficiency

<div align="center"><sub>More at <a href="https://ahmedkholaif.github.io">ahmedkholaif.github.io</a></sub></div>
