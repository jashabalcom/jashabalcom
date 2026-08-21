## Hey, I'm Jasha

**Baseball Technologist · Platform Reliability & Operations · Former Pro Athlete**

I build and operate production cloud platforms, with a focus on sports technology. Former Chicago Cubs prospect, scout, and player agent — 17+ years running baseball programs and developing athletes, including MLB All-Stars. Now I build the tools: markerless pose detection for swing biomechanics, AI swing analysis on AWS, and the reliability engineering that keeps it running.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jashabalcom)

---

### What I'm Shipping

**[Swing Institute](https://github.com/jashabalcom/swing-institute-architecture)** — Live SaaS platform for baseball player development. Video coaching, structured curriculum, real-time community, Stripe subscriptions. Deployed on AWS Amplify, serving paying athletes.

> 37 PostgreSQL tables · 9 serverless functions · 6 Stripe subscription tiers · 10 transactional email templates · Real-time community · $0.15/user/month at scale

**[Terrava](https://github.com/jashabalcom/terrava-architecture)** — AI-powered real estate investment platform across 11 global markets. Chrome Extension analyzes listings on 40+ sites with instant AI verdicts.

> 14 CDK Stacks · 77 Lambda functions (ARM64) · Multi-Model Bedrock AI · RAG pipeline · Aurora Serverless v2 · $72/month total cost

---

### How I Build

I own the full stack — architecture decisions, infrastructure, backend, frontend, billing, and deployment. Every project ships with production security, cost optimization, and a migration path.

```
Architecture    AWS CDK (TypeScript) · Serverless-first · Multi-AZ · Cost-optimized
AI/ML           Amazon Bedrock · Claude · RAG with Knowledge Bases · Multi-model routing
Compute         Lambda (ARM64) · API Gateway · Edge Functions
Data            Aurora Serverless v2 · DynamoDB · PostgreSQL with RLS · Redis
Security        WAF · Cognito · KMS · Row-Level Security · CloudTrail
Frontend        React 18 · TypeScript · Tailwind · Shadcn/UI
Payments        Stripe (subscriptions, webhooks, customer portal, usage metering)
Observability   CloudWatch · X-Ray · Synthetics Canaries · Alarms
```

---

### Architecture Decisions (In the Open)

- **[Swing Institute Architecture](https://github.com/jashabalcom/swing-institute-architecture)** — Serverless SaaS on AWS. Why PostgreSQL RLS over application-level auth. Why code splitting matters for a multi-role app. Cost analysis at $0.15/user/month. Full AWS migration roadmap.

- **[Terrava Architecture](https://github.com/jashabalcom/terrava-architecture)** — Enterprise multi-tenant platform. Multi-model AI routing (60% cost savings). 3-tier VPC design. Event-driven architecture with EventBridge + SQS + DLQ. Defense-in-depth security.

---

### By the Numbers

| | Swing Institute | Terrava |
|-|----------------|---------|
| **Status** | Live, paying users | Production architecture |
| **Functions** | 9 edge functions | 77 Lambda (ARM64) |
| **Database** | 37 tables, RLS | Aurora Serverless v2 + DynamoDB |
| **AI** | Planned (Bedrock) | 3 models, RAG pipeline |
| **Billing** | 6 Stripe tiers | 8 Stripe tiers |
| **Infra Cost** | $30/month | $72/month |
| **IaC** | CDK (planned) | 14 CDK stacks |

---

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jashabalcom)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jashabalcom@gmail.com)

---

*Former MLB Draft Pick (Chicago Cubs) · Scout & player agent · Trained MLB All-Stars Cedric Mullins, Brandon Marsh & Byron Buxton · Chadwick Boseman's stunt double in "42" · Atlanta Fine Homes Sotheby's International Realty · Building production platforms on AWS*
