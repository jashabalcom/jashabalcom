## Hey, I'm Jasha 👋

**Real Estate Advisor · PropTech Builder · Former Pro Athlete**

I design and build cloud-native platforms on AWS. Former Chicago Cubs draft pick, Merrill Lynch financial advisor, and baseball academy owner who trained MLB All-Stars. Now architecting AI-powered tools that help investors analyze property across 11 global markets.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jashabalcom)
[![Architecture](https://img.shields.io/badge/Architecture_Showcase-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jashabalcom/terrava-architecture)

---

### 🚀 What I'm Building

**[Terrava](https://github.com/jashabalcom/terrava-architecture)** — AI-powered real estate investment platform serving 11 global markets.

**The Platform**
> AI investment analysis · 13 calculators with Deal Score engine · Multi-market intelligence · Community hub · Chrome Extension on 40+ property sites · 8 subscription tiers

**The Chrome Extension**
> Browse Zillow, Rightmove, Bayut, or any of 40+ listing sites — get an instant AI verdict: Strong Buy, Fair Price, or Overpriced. Works across 11 countries with local mortgage rates, tax rules, and market benchmarks built in.

---

### 🏗️ Solutions Architecture

I designed and deployed this entire platform — infrastructure, backend, AI, frontend, and billing.

```
14 CDK Stacks · 77 Serverless Functions · Multi-Model AI · RAG Pipeline
Aurora Serverless v2 · Real-time Messaging · 8 Stripe Billing Tiers · $72/mo Total Cost
```

| Layer | What's Deployed |
|-------|----------------|
| **AI/ML** | Amazon Bedrock (Claude Sonnet/Haiku) · RAG w/ Knowledge Bases · Multi-model routing with fallback · Guardrails |
| **Compute** | 77 Lambda (ARM64/Graviton2) · API Gateway HTTP v2 · Shared Lambda Layer |
| **Data** | Aurora Serverless v2 (PostgreSQL) · DynamoDB · ElastiCache Redis Serverless |
| **Networking** | 3-tier VPC (public/private/isolated) × 3 AZs · CloudFront CDN · Route 53 |
| **Security** | WAFv2 · KMS encryption · Cognito (MFA) · CloudTrail audit · Custom JWT authorizer (ES256) |
| **IaC** | AWS CDK (TypeScript, 14 stacks) · CI/CD with GitHub Actions + OIDC federation |
| **Billing** | Stripe (8 tiers) · Usage metering · Tier gating · 14-day trials |
| **Observability** | CloudWatch Synthetics canaries · X-Ray distributed tracing · Alarms · Budget anomaly detection |
| **Cost Optimization** | Serverless-first · ARM64/Graviton2 · HTTP v2 migration (71% savings) · Multi-model AI routing (60% savings) |

---

### 🛠️ Tech Stack

**AI/ML & Machine Learning**

![Bedrock](https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Sonnet-191919?style=flat)
![Claude](https://img.shields.io/badge/Claude_Haiku-191919?style=flat)
![RAG](https://img.shields.io/badge/RAG_Pipeline-4053D6?style=flat)
![Knowledge Bases](https://img.shields.io/badge/Knowledge_Bases-FF9900?style=flat)
![Guardrails](https://img.shields.io/badge/Bedrock_Guardrails-DC382D?style=flat)

**AWS Cloud Infrastructure**

![Lambda](https://img.shields.io/badge/Lambda_(77)-FF9900?style=flat&logo=awslambda&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway_v2-FF4F8B?style=flat&logo=amazonapigateway&logoColor=white)
![Aurora](https://img.shields.io/badge/Aurora_Serverless_v2-4053D6?style=flat&logo=amazonrds&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white)
![CDK](https://img.shields.io/badge/CDK_(14_stacks)-232F3E?style=flat&logo=amazonaws&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront+WAF-8C4FFF?style=flat)
![ElastiCache](https://img.shields.io/badge/ElastiCache_Redis-DC382D?style=flat)
![EventBridge](https://img.shields.io/badge/EventBridge-FF4F8B?style=flat)
![Cognito](https://img.shields.io/badge/Cognito-DD344C?style=flat)
![KMS](https://img.shields.io/badge/KMS-DD344C?style=flat)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat)
![X-Ray](https://img.shields.io/badge/X--Ray-FF4F8B?style=flat)
![Synthetics](https://img.shields.io/badge/Synthetics_Canaries-FF9900?style=flat)
![SES](https://img.shields.io/badge/SES_v2-DD344C?style=flat)
![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat)
![Secrets Manager](https://img.shields.io/badge/Secrets_Manager-DD344C?style=flat)

**Frontend & Payments**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)
![shadcn](https://img.shields.io/badge/shadcn/ui-000000?style=flat)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

---

### 📊 Platform Metrics

| Metric | Value |
|--------|-------|
| AWS CDK Stacks | 14 (all deployed, production) |
| Lambda Functions | 77 (ARM64/Graviton2, serverless) |
| AI Models | 3 (multi-model routing with automatic fallback) |
| Global Markets | 11 countries with local financial rules |
| Chrome Extension | 40+ listing platforms supported |
| Monthly Infrastructure Cost | $72 (scales to 100K users, zero code changes) |
| AI Cost Reduction | 60% via multi-model routing |
| API Cost Savings | 71% via HTTP v2 migration |
| Database | Aurora Serverless v2 with row-level security |
| Availability | Multi-AZ, 3-tier VPC, circuit breakers, DLQ |

---

### 🧠 Architecture Decisions

I document my architectural thinking in the open:

- **[Terrava Architecture Showcase](https://github.com/jashabalcom/terrava-architecture)** — Full system design, AWS service patterns, cost analysis, and architecture diagrams
- Why serverless over containers for this workload
- Multi-tenant data isolation with PostgreSQL RLS
- Multi-model AI routing (cost vs quality tradeoffs)
- Event-driven architecture with EventBridge + SQS + DLQ
- Defense-in-depth security (WAF → CloudFront → API GW → Cognito → VPC → RLS)

---

### 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jashabalcom)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jashabalcom@gmail.com)

---

*Atlanta Fine Homes Sotheby's International Realty · Former MLB Draft Pick (Chicago Cubs) · Trained All-Star Cedric Mullins & Brandon Marsh · Chadwick Boseman's stunt double in "42" · Building production cloud architecture on AWS*
