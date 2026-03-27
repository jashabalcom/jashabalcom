## Hey, I'm Jasha 👋

**Senior AWS Solutions Architect** building production AI platforms and enterprise SaaS. Two products live in production — an AI investment intelligence platform and an AI-powered CRM for real estate agents.

[![Portfolio](https://img.shields.io/badge/Live_Product-dubairealestateinvestor.com-00C853?style=for-the-badge)](https://dubairealestateinvestor.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jashabalcom)

---

### 🚀 What I'm Building

**[Dubai Wealth AI](https://github.com/jashabalcom/dubai-wealth-ai)** — Two SaaS products on one platform, live in production:

**Product 1: AI Investment Platform** (B2C)
> 1,122+ property listings · 13 investment calculators with AI Deal Score · Community with trending market intelligence · Saved strategies · 4 subscription tiers

**Product 2: AI Agent CRM** (B2B)
> AI Voice Profiles · AI Draft Replies with sales psychology · Auto-Respond · Smart Notifications · Pipeline Management · Follow-up Sequences · 4 agent subscription tiers

---

### 🏗️ Architecture at a Glance

```
16 CDK Stacks · 77 Lambda Functions · Multi-Model Bedrock AI · RAG Pipeline
Aurora Serverless v2 · Real-time Messaging · 8 Stripe Billing Tiers · Live in Production
```

| Layer | What's Deployed |
|-------|----------------|
| **AI/ML** | Bedrock (Claude Sonnet/Haiku) · RAG w/ Knowledge Bases · AI Voice Profiles · AI Draft System · Guardrails |
| **Compute** | 77 Lambda (ARM64/Graviton2) · API Gateway HTTP v2 · Lambda Layer |
| **Data** | Aurora Serverless v2 · DynamoDB (6 tables) · ElastiCache Redis · Supabase Realtime |
| **Security** | 3-tier VPC × 3 AZs · WAFv2 · KMS · GuardDuty · CloudTrail · Custom JWT (ES256) |
| **Billing** | Stripe (8 tiers) · Usage metering · Tier gating · 14-day trials |
| **Observability** | CloudWatch Synthetics · X-Ray · Alarms · Budget anomaly detection |

---

### 🤖 AI Capabilities (Production)

| Feature | How It Works |
|---------|-------------|
| **Multi-Model Routing** | Claude Sonnet for deep analysis, Haiku for fast queries, Gemini Flash fallback — 60% cost reduction |
| **RAG Pipeline** | Bedrock Knowledge Bases + Titan Embeddings v2 + OpenSearch Serverless — regulatory Q&A with citations |
| **AI Voice Profiles** | Agents train AI to replicate their communication style — greeting, tone, emoji, sign-off |
| **AI Draft Replies** | Contextual replies using agent's voice + sales psychology (reciprocity, scarcity, social proof) |
| **AI Auto-Respond** | Offline messaging with configurable topics, schedule, and daily limits |
| **Smart Notifications** | Behavioral triggers: "Client just ran ROI Calculator — they might be ready to move" |
| **Deal Score Engine** | AI-powered 1-10 property rating with KPI cards and area comparisons |
| **Guardrails** | Financial compliance filtering, PII anonymization, prompt injection defense |

---

### 🛠️ Tech Stack

**AI/ML**

![Bedrock](https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Sonnet_4.5-191919?style=flat)
![Claude](https://img.shields.io/badge/Claude_Haiku_4.5-191919?style=flat)
![RAG](https://img.shields.io/badge/RAG_Pipeline-4053D6?style=flat)
![Knowledge Bases](https://img.shields.io/badge/Knowledge_Bases-FF9900?style=flat)
![Guardrails](https://img.shields.io/badge/Bedrock_Guardrails-DC382D?style=flat)
![Voice AI](https://img.shields.io/badge/AI_Voice_Profiles-8B5CF6?style=flat)

**AWS Infrastructure**

![Lambda](https://img.shields.io/badge/Lambda_(77)-FF9900?style=flat&logo=awslambda&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway_v2-FF4F8B?style=flat&logo=amazonapigateway&logoColor=white)
![Aurora](https://img.shields.io/badge/Aurora_Serverless_v2-4053D6?style=flat&logo=amazonrds&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB_(6_tables)-4053D6?style=flat&logo=amazondynamodb&logoColor=white)
![CDK](https://img.shields.io/badge/CDK_(16_stacks)-232F3E?style=flat&logo=amazonaws&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront+WAF-8C4FFF?style=flat)
![EventBridge](https://img.shields.io/badge/EventBridge-FF4F8B?style=flat)
![Synthetics](https://img.shields.io/badge/Synthetics_Canaries-FF9900?style=flat)

**Frontend & Real-time**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)
![shadcn](https://img.shields.io/badge/shadcn/ui-000000?style=flat)
![Supabase](https://img.shields.io/badge/Supabase_Realtime-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)

---

### 📊 Key Metrics

| Metric | Value |
|--------|-------|
| CDK Stacks | 16 (all deployed, production) |
| Lambda Functions | 77 (ARM64/Graviton2) |
| AI Models | 3 (Sonnet 4.5, Haiku 4.5, Gemini Flash) |
| Subscription Tiers | 8 (4 consumer + 4 agent) |
| Investment Calculators | 13 (all with AI Deal Score) |
| Property Listings | 1,122+ (expanding to 200K+) |
| AI Cost Reduction | 60% (multi-model routing) |
| API Cost Savings | 71% (HTTP v2 vs REST) |

---

### 📜 Certifications

- ✅ AWS Certified Cloud Practitioner (CLF-C02, 2025)
- 📚 AWS Solutions Architect Associate (SAA-C03 — In Progress)
- 📚 AWS AI Practitioner (AIF-C01 — 2026)

---

### 🤝 Open To

**Senior / Principal Solutions Architect** roles focused on AI platforms, enterprise SaaS, and cloud-native architecture. Remote or flexible.

Interested in: AI-first architectures on Bedrock · Multi-product SaaS · Real-time systems · Financial services · CRM platforms

---

### 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jashabalcom)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jashabalcom@gmail.com)
[![Portfolio](https://img.shields.io/badge/Live_Product-dubairealestateinvestor.com-00C853?style=for-the-badge)](https://dubairealestateinvestor.com)

---

*Sotheby's International Realty · Merrill Lynch · Former MLB Draft Pick (Chicago Cubs) · Now building AI-powered SaaS on AWS.*
