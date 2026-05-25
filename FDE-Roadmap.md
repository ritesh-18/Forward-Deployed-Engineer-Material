# The Forward Deployed Engineer Roadmap

*A complete path from your current level to a Forward Deployed Engineer / Solutions Engineer / AI Field Engineer role at top companies.*

---

## Table of Contents

1. [What is a Forward Deployed Engineer](#1-what-is-a-forward-deployed-engineer)
2. [Why This Role Is Exploding Right Now](#2-why-this-role-is-exploding-right-now)
3. [The Full Skill Tree](#3-the-full-skill-tree)
4. [Phase 1 — Software Engineering Foundation](#4-phase-1--software-engineering-foundation)
5. [Phase 2 — Cloud & Infrastructure](#5-phase-2--cloud--infrastructure)
6. [Phase 3 — Deployment Engineering](#6-phase-3--deployment-engineering)
7. [Phase 4 — Distributed Systems & Scale](#7-phase-4--distributed-systems--scale)
8. [Phase 5 — GenAI Systems](#8-phase-5--genai-systems)
9. [Phase 6 — Customer & Solutions Skills](#9-phase-6--customer--solutions-skills)
10. [Phase 7 — Security, Observability, Production](#10-phase-7--security-observability-production)
11. [Portfolio Projects](#11-portfolio-projects)
12. [Target Companies — Names, What They Want, How to Apply](#12-target-companies--names-what-they-want-how-to-apply)
13. [Interview Preparation](#13-interview-preparation)
14. [Compensation & Negotiation](#14-compensation--negotiation)
15. [Daily, Weekly, Monthly Plan](#15-daily-weekly-monthly-plan)
16. [Common Mistakes to Avoid](#16-common-mistakes-to-avoid)

---

## 1. What is a Forward Deployed Engineer

A Forward Deployed Engineer (FDE) is a software engineer who works **embedded with customers** to build, deploy, and customize solutions in real production environments. The role is part software engineer, part solutions architect, part product engineer, part DevOps engineer, part customer engineer.

**An FDE owns the path from "the customer's problem" to "running production system."**

What an FDE actually does in a typical week:
- Sits with the customer's engineering team and learns their stack and constraints
- Designs an end-to-end system that solves the business problem
- Builds prototypes in days, not months
- Deploys to the customer's cloud (AWS / Azure / GCP / on-prem)
- Integrates the customer's data sources, identity systems, internal APIs
- Sets up observability so the customer can debug after you leave
- Trains the customer's team to maintain the system
- Travels to the customer's site when needed (for high-value accounts)
- Owns the outcome — "did this make the customer successful"

**The defining property:** an FDE is judged by *customer outcomes*, not by *internal product velocity*.

---

## 2. Why This Role Is Exploding Right Now

Three forces are creating massive demand:

**Force 1 — AI made deployment the bottleneck.** Foundation models are easy to call; turning them into a working product inside a Fortune 500 environment is hard. Every AI company needs people who can go into an enterprise, navigate its mess, and ship.

**Force 2 — Customers buy outcomes, not products.** Enterprises spend millions on "AI platforms" that fail because no one helped them deploy. FDEs are the antidote.

**Force 3 — High-growth AI startups can't scale traditional sales engineering.** They need engineers who can do everything from a discovery call to writing production Kubernetes manifests.

The result: companies are paying $200k-$500k+ total comp for engineers who can do all of this.

---

## 3. The Full Skill Tree

```
Forward Deployed Engineer
│
├── 1. Software Engineering Foundation
│   ├── Strong language (Python or Node.js + TypeScript)
│   ├── API design (REST, gRPC, GraphQL, WebSocket, SSE)
│   ├── Databases (Postgres, Redis, MongoDB)
│   ├── Auth (JWT, OAuth2, SSO, mTLS)
│   ├── Async & concurrency
│   ├── Testing & code quality
│   └── Git, code review, software process
│
├── 2. Cloud & Infrastructure
│   ├── AWS (or GCP / Azure)
│   │   ├── IAM, VPC, Security Groups
│   │   ├── EC2, ECS, EKS, Lambda
│   │   ├── S3, RDS, ElastiCache, OpenSearch
│   │   ├── ALB, NLB, CloudFront, Route53
│   │   ├── Secrets Manager, Parameter Store, KMS
│   │   └── CloudWatch, CloudTrail
│   ├── Kubernetes
│   │   ├── Pods, Deployments, Services, Ingress
│   │   ├── ConfigMap, Secret, RBAC
│   │   ├── HPA, VPA, Cluster Autoscaler
│   │   ├── StatefulSets, DaemonSets
│   │   ├── Helm, Kustomize
│   │   ├── GPU scheduling, NVIDIA GPU Operator
│   │   └── Service mesh (Istio, Linkerd)
│   └── Networking deep dive
│       ├── DNS, TLS, mTLS
│       ├── VPC peering, PrivateLink
│       ├── Load balancing patterns
│       └── Zero Trust architecture
│
├── 3. Deployment Engineering
│   ├── Docker (multi-stage builds, slim images)
│   ├── CI/CD (GitHub Actions, GitLab CI, ArgoCD, Flux)
│   ├── Terraform (modules, state, workspaces)
│   ├── Pulumi (alternative IaC)
│   ├── Deployment strategies (blue-green, canary, shadow)
│   └── Feature flags, kill switches
│
├── 4. Distributed Systems & Scale
│   ├── CAP / PACELC
│   ├── Queues (Kafka, RabbitMQ, NATS, Redis Streams)
│   ├── Event-driven architecture
│   ├── Workflow engines (Temporal, Restate, Inngest)
│   ├── Caching strategies
│   ├── Circuit breakers, retries, backpressure
│   └── System design at scale
│
├── 5. GenAI Systems
│   ├── LLM fundamentals (transformers, tokens, sampling)
│   ├── Prompt engineering (system prompts, JSON mode, tools)
│   ├── RAG (chunking, hybrid retrieval, reranking, evaluation)
│   ├── Vector DBs (Pinecone, Qdrant, Weaviate, pgvector)
│   ├── Embeddings (BGE, E5, OpenAI, Cohere)
│   ├── Agents (LangChain, LangGraph, MCP, CrewAI)
│   ├── Inference servers (vLLM, TGI, TensorRT-LLM, Triton)
│   ├── GPU economics (H100, A100, L40S, quantization)
│   ├── Fine-tuning (LoRA, QLoRA, SFT, DPO)
│   └── AI observability (LangSmith, Phoenix, Langfuse)
│
├── 6. Customer & Solutions Skills
│   ├── Discovery questions
│   ├── Architecture whiteboarding
│   ├── Technical writing
│   ├── Demo skills
│   ├── Stakeholder management
│   ├── Ambiguity handling
│   └── Reading business needs vs technical asks
│
└── 7. Security, Observability, Production
    ├── OWASP top 10 + AI top 10
    ├── Secrets management (Vault, cloud KMS)
    ├── OpenTelemetry, Prometheus, Grafana
    ├── Loki, Tempo, Jaeger
    ├── SLOs and incident response
    ├── Compliance basics (SOC 2, GDPR, HIPAA)
    └── Cost optimization (FinOps for AI)
```

---

## 4. Phase 1 — Software Engineering Foundation

**Duration:** 2-3 months if starting from solid programming. 4-6 months if newer.

### 4.1 Pick Your Primary Stack

You should have **one** stack you can ship anything in. Two great choices for FDE:

| Stack | When to Pick | Strength |
|---|---|---|
| **Python + FastAPI** | AI-heavy companies, infra-heavy roles | Best AI ecosystem |
| **Node.js + NestJS + TypeScript** | Web-heavy companies, full-stack roles | Type safety, frontend overlap |

Pick one. Be deep, not wide. You'll learn the other later.

### 4.2 What to Master

**Language fundamentals**
- Async / await, promises, event loop (Node) or asyncio (Python)
- Generators and streams
- Error handling patterns
- Type systems (TypeScript strict mode, Python type hints + mypy)

**API design**
- REST (idempotency, pagination, versioning, status codes)
- gRPC (protobuf, streaming, deadlines)
- WebSocket (handshake, ping/pong, scaling)
- SSE (when to choose over WebSocket)
- GraphQL (resolvers, N+1, federation)

**Databases**
- PostgreSQL deeply (indexes, query plans, transactions, JSONB, full-text)
- Redis (data structures, pub/sub, streams, persistence trade-offs)
- MongoDB basics (when document model fits)

**Auth & Identity**
- JWT (signing, refresh tokens, revocation pitfalls)
- OAuth2 / OIDC flows
- SSO (SAML, Okta, Auth0)
- API keys, service accounts, mTLS

### 4.3 Resources

**Books**
- "Designing Data-Intensive Applications" — Martin Kleppmann (this book is the FDE bible)
- "The Pragmatic Programmer" — Hunt & Thomas
- "Database Internals" — Alex Petrov

**Courses**
- ThePrimeagen's "FullStack" content (YouTube + Frontend Masters)
- Hussein Nasser's "Backend Engineering" YouTube channel — exceptional for fundamentals
- Theo - t3.gg (modern TypeScript backend)
- "Postgres for Everything" by Stephan Schmidt

**Docs to read end-to-end**
- PostgreSQL official docs (the "Server Administration" + "SQL Language" sections)
- FastAPI tutorial
- NestJS official docs
- gRPC.io concepts section

**Practice**
- Build a production-quality URL shortener
- Build a multi-tenant SaaS skeleton with proper auth
- Solve LeetCode mediums until comfortable (50-100 problems)

---

## 5. Phase 2 — Cloud & Infrastructure

**Duration:** 3-4 months. This is the biggest investment area for FDE work.

### 5.1 AWS (Primary Cloud to Master)

AWS is dominant in enterprise. Master it first. Add GCP and Azure later as needed.

**Core services to know cold:**
- **Compute:** EC2, ECS, EKS, Lambda, Fargate
- **Networking:** VPC, subnets, security groups, NACLs, route tables, NAT, IGW, VPC peering, Transit Gateway, PrivateLink
- **Edge:** Route53, CloudFront, WAF, Shield
- **Storage:** S3 (storage classes, lifecycle, encryption, versioning, replication), EBS, EFS, FSx
- **Database:** RDS, Aurora, DynamoDB, ElastiCache, OpenSearch
- **Identity:** IAM (users, roles, policies, trust relationships), STS, AWS SSO (Identity Center)
- **Secrets:** Secrets Manager, Parameter Store, KMS, ACM
- **Observability:** CloudWatch (Logs, Metrics, Alarms), CloudTrail, X-Ray
- **Messaging:** SQS, SNS, EventBridge, MSK (Kafka)
- **AI services:** Bedrock, SageMaker (you'll integrate with these often)

**Getting hands-on:**
- Earn the **AWS Solutions Architect Associate** certification (great signal)
- Then either AWS DevOps Pro or AWS Solutions Architect Professional
- Build everything in a personal AWS account; set a $20 budget alarm

### 5.2 Kubernetes (Mandatory)

Every modern infra-heavy role expects K8s fluency.

**Concepts to internalize:**
- Pods, ReplicaSets, Deployments, StatefulSets, DaemonSets, Jobs, CronJobs
- Services (ClusterIP, NodePort, LoadBalancer, ExternalName), Endpoints
- Ingress controllers (nginx, Traefik, AWS Load Balancer Controller)
- ConfigMap, Secret, mounting strategies
- Namespaces, RBAC (Roles, RoleBindings, ClusterRoles)
- PersistentVolume, PersistentVolumeClaim, StorageClass
- HPA (Horizontal Pod Autoscaler), VPA, Cluster Autoscaler, Karpenter
- Probes (liveness, readiness, startup)
- Resource requests and limits, QoS classes
- Taints, tolerations, node selectors, affinities
- Operators and CRDs
- Helm (charts, values, templating, hooks)
- Kustomize (base + overlays)
- GPU scheduling (NVIDIA Device Plugin, GPU Operator, MIG)

**Service mesh basics:**
- Istio vs Linkerd
- mTLS automatic between services
- Traffic shifting for canary deployments

### 5.3 Networking Deep Dive

Most engineers are weak here. Being strong here is a differentiator.

- DNS (records, propagation, split-horizon)
- TLS handshake, certificate chains, SNI
- HTTP/2 vs HTTP/3
- Load balancer types (L4 vs L7)
- VPC peering, Transit Gateway, hub-and-spoke
- PrivateLink / VPC Endpoints (critical for enterprise FDE work)
- Site-to-site VPN, Direct Connect
- Zero Trust architecture basics

### 5.4 Resources

**Books**
- "Kubernetes Up and Running" — Hightower, Burns, Beda
- "Programming Kubernetes" — Hausenblas, Schimanski (for operators)
- "AWS Certified Solutions Architect Study Guide" — Ben Piper / David Clinton

**Courses**
- **Stephane Maarek** on Udemy — AWS Solutions Architect Associate (the gold standard)
- **Adrian Cantrill** — AWS courses (deeper than Maarek, harder)
- **KodeKloud** — Kubernetes hands-on labs
- **Mumshad Mannambeth** — CKA / CKAD / CKS prep on Udemy

**YouTube**
- TechWorld with Nana — Kubernetes and DevOps explainers
- Be A Better Dev — AWS solutions architect content
- Anton Putra — cloud and Kubernetes deep dives

**Certifications worth pursuing (signal value):**
- AWS Solutions Architect Associate (SAA-C03)
- Certified Kubernetes Administrator (CKA)
- Certified Kubernetes Application Developer (CKAD)
- HashiCorp Certified: Terraform Associate

**Practice labs**
- KillerCoda interactive scenarios
- AWS Skill Builder labs
- Set up a personal EKS cluster, deploy a Python/Node app, expose via ALB Ingress, add HPA, add CloudWatch dashboards

---

## 6. Phase 3 — Deployment Engineering

**Duration:** 2 months parallel with Phase 2.

### 6.1 Docker Mastery

- Multi-stage builds (lean production images)
- Layer caching strategy
- Dockerfile best practices (non-root user, COPY vs ADD, .dockerignore)
- Image scanning (Trivy, Grype, Snyk)
- BuildKit features (cache mounts, secrets)
- Distroless and slim base images

### 6.2 CI/CD Pipelines

You should be able to build a complete pipeline from scratch.

**Tools to learn:**
- GitHub Actions (most common in startups)
- GitLab CI (common in enterprises)
- ArgoCD (GitOps for Kubernetes)
- Flux (alternative GitOps)
- CircleCI, Buildkite (alternatives)

**Pipeline patterns:**
- PR validation (lint, test, build, security scan)
- Image build and push to registry
- Helm chart versioning
- Environment promotion (dev → staging → prod)
- Approval gates
- Rollback automation

### 6.3 Infrastructure as Code

**Terraform** is the must-know tool.

- Providers, resources, data sources
- Variables, outputs, locals
- Modules (writing, consuming, registry)
- State management (remote backend, locking, workspaces)
- Plan/apply lifecycle and drift detection
- Workspaces vs separate state files
- Terragrunt for managing complex setups

Then **Pulumi** as an alternative (lets you write infra in TypeScript/Python/Go).

### 6.4 Deployment Strategies

Know cold:
- Rolling update (Kubernetes default)
- Blue-green (cutover with rollback)
- Canary (progressive traffic shift)
- Shadow (mirror traffic to new version)
- Feature flags (LaunchDarkly, Unleash, custom)
- A/B testing infrastructure

Tools: Argo Rollouts, Flagger, Spinnaker.

### 6.5 Resources

**Courses**
- HashiCorp Terraform Associate prep — Zeal Vora or Bryan Krausen on Udemy
- "GitOps with ArgoCD" — KodeKloud
- "Docker Mastery" — Bret Fisher (Udemy)

**Reading**
- Terraform Up & Running — Yevgeniy Brikman
- The official ArgoCD docs (small but excellent)
- Google's SRE Book (free online) — chapters on release engineering

**Build**
- A complete GitOps pipeline: push to main → GitHub Actions builds Docker image → ArgoCD deploys to EKS → canary rollout via Argo Rollouts

---

## 7. Phase 4 — Distributed Systems & Scale

**Duration:** 2-3 months ongoing.

### 7.1 Theoretical Foundations

- CAP theorem and PACELC
- Consistency models (strong, eventual, causal, read-your-writes)
- ACID vs BASE
- Distributed consensus (Raft, Paxos — at a high level)
- Vector clocks and logical time
- Idempotency and exactly-once vs at-least-once semantics

### 7.2 Practical Patterns

- **Queues:** Kafka, RabbitMQ, NATS, Redis Streams, SQS
- **Event-driven architectures:** event sourcing, CQRS, sagas
- **Workflow engines:** Temporal (the most important new tool), Restate, Inngest, AWS Step Functions
- **Caching:** cache-aside, read-through, write-through, write-back; cache invalidation strategies
- **Circuit breakers:** Hystrix patterns, retry with exponential backoff and jitter
- **Backpressure:** bounded queues, load shedding, admission control
- **Rate limiting:** token bucket, sliding window, distributed rate limit with Redis

### 7.3 System Design

The interview format you will face repeatedly.

**Practice designing:**
- URL shortener
- News feed (Twitter / Instagram)
- Chat system (WhatsApp / Slack)
- Ride sharing (Uber)
- Video streaming (YouTube)
- Distributed key-value store
- Search autocomplete
- Notification system
- Payment system
- **AI-specific:** ChatGPT-like, enterprise RAG, multi-agent platform, AI search engine, voice AI

### 7.4 Resources

**Books**
- "Designing Data-Intensive Applications" — Martin Kleppmann (read twice)
- "System Design Interview Volume 1 & 2" — Alex Xu
- "Database Internals" — Alex Petrov

**Courses**
- ByteByteGo (Alex Xu) — YouTube + paid course
- Hello Interview — system design interview prep
- Educative.io — "Grokking the System Design Interview"

**Free resources**
- The MIT 6.824 Distributed Systems course (lectures on YouTube)
- Martin Kleppmann's distributed systems lectures (free on YouTube)
- Jepsen analyses (jepsen.io) — case studies of where distributed systems break

---

## 8. Phase 5 — GenAI Systems

**Duration:** 3-4 months.

This is the differentiator. Most FDE roles in 2025-2026 are AI roles. Your handbook (GenAI-FullStack-Handbook in this repo) covers everything below in depth.

### 8.1 LLM Fundamentals
- Transformers, attention, tokenization
- Context windows, KV cache, sampling parameters
- Open vs closed models, when to use which
- Quantization (FP16, FP8, INT8, INT4)

### 8.2 Prompt Engineering
- System prompts, tool definitions
- Structured outputs (JSON mode, schema constraints)
- Few-shot, chain-of-thought
- Prompt injection defenses
- Prompt versioning and evaluation

### 8.3 RAG (Retrieval Augmented Generation)
- Chunking strategies
- Hybrid retrieval (vector + BM25)
- Reranking (cross-encoders)
- Citation systems
- Evaluation harnesses (RAGAS, TruLens, Phoenix)
- Multi-tenant RAG with ACL

### 8.4 Vector Databases
- HNSW vs IVF vs PQ
- Pinecone, Qdrant, Weaviate, pgvector, Milvus
- Hybrid search, filtering, multi-tenancy
- Scaling and re-indexing strategies

### 8.5 Agents
- Tool calling patterns (ReAct, Plan-and-Execute)
- LangChain, LangGraph, CrewAI, AutoGen
- Model Context Protocol (MCP)
- Workflow engines for durable agents (Temporal)
- Multi-agent orchestration

### 8.6 Inference Serving
- vLLM (the dominant open server)
- TGI (Hugging Face)
- TensorRT-LLM (NVIDIA max performance)
- Triton Inference Server
- Continuous batching, paged attention, speculative decoding
- GPU autoscaling

### 8.7 GPU Economics
- H100, A100, L40S, A10G tier differences
- Memory bandwidth vs FLOPs trade-offs
- Tensor parallelism vs pipeline parallelism
- Cost per million tokens calculations
- Spot vs reserved vs on-demand

### 8.8 Fine-tuning
- When to fine-tune vs prompt vs RAG
- LoRA, QLoRA, full fine-tuning
- SFT, DPO, RLHF basics
- Data preparation discipline

### 8.9 AI Observability
- LangSmith, Langfuse, Phoenix, Helicone
- Tracing every LLM call
- Eval pipelines
- Cost dashboards per feature

### 8.10 Resources

**The complete handbook in this repo** covers all of the above. Read it cover to cover:
[GenAI-FullStack-Handbook/](GenAI-FullStack-Handbook/)

**External courses**
- Andrej Karpathy's "Zero to Hero" series on YouTube (free; foundational)
- "LangChain & Vector Databases in Production" — DeepLearning.AI / ActiveLoop
- "Building RAG Applications" — DeepLearning.AI short courses
- "ChatGPT Prompt Engineering for Developers" — Andrew Ng + Isa Fulford

**YouTube channels**
- Sam Witteveen (LLM + LangChain practical)
- AI Jason (agent and RAG tutorials)
- AI Engineer (conference talks)
- 1littlecoder
- Greg Kamradt (Data Independent)

**Newsletters**
- Latent Space (Swyx)
- The Pragmatic Engineer (Gergely Orosz)
- Import AI (Jack Clark)
- AI Engineer
- The Rundown AI

**Hands-on**
- Build the six projects from Chapter 28 of the handbook
- Contribute to one open-source AI infra project (vLLM, LangChain, Qdrant, etc.)

---

## 9. Phase 6 — Customer & Solutions Skills

**Duration:** Ongoing. Often the hardest part for engineers.

### 9.1 Discovery Skills

FDEs need to extract real requirements from confused stakeholders.

**Questions to practice asking:**
- "What does success look like 90 days from now?"
- "What is broken today that this needs to fix?"
- "Who else is involved in the decision?"
- "What's the budget envelope?"
- "What are the must-haves vs nice-to-haves?"
- "What systems will this need to integrate with?"
- "What are your compliance and security constraints?"
- "What does your current architecture look like?"

### 9.2 Architecture Whiteboarding

You must be able to draw a system architecture in front of customers and explain trade-offs in real time.

Practice:
- Sketch any system you discuss in 5 minutes on a whiteboard
- Explain every box with "why" before "what"
- Always show data flow with arrows
- Identify failure modes during the discussion
- Estimate cost in real time

### 9.3 Technical Writing

FDEs write a *lot*: design docs, deployment runbooks, postmortems, customer-facing reports.

**Practice:**
- Write a one-page "How this system works" doc for every project you build
- Write a runbook for one common production incident
- Write a customer-facing executive summary of a technical project

**Resources:**
- "The Sense of Style" — Steven Pinker
- Google's "Technical Writing One" course (free)
- "Show Your Work" — Austin Kleon

### 9.4 Demo Skills

The 15-minute customer demo is a make-or-break art.

**Structure:**
- 1 minute: the customer's problem in their words
- 2 minutes: the high-level architecture
- 8 minutes: the working demo
- 2 minutes: what's customizable
- 2 minutes: questions

Record yourself doing demos. Watch them back. They will be cringeworthy at first.

### 9.5 Stakeholder Management

You will work with:
- **Technical leads** (CTOs, principal engineers) — want depth
- **Product managers** — want roadmap and metrics
- **Procurement / security** — want compliance evidence
- **Executives** — want business value in plain language

Adjust your communication for each audience without losing accuracy.

### 9.6 Resources

**Books**
- "The Trusted Advisor" — David Maister
- "Crucial Conversations" — Patterson, Grenny, McMillan, Switzler
- "The Mom Test" — Rob Fitzpatrick (great for customer discovery)
- "How to Win Friends and Influence People" — Dale Carnegie (yes, still relevant)

**Other**
- Watch any conference talk by Charity Majors (Honeycomb founder, exceptional communicator)
- Practice mock customer calls with a friend acting as the customer

---

## 10. Phase 7 — Security, Observability, Production

**Duration:** Ongoing.

### 10.1 Security

- OWASP Top 10 (memorize)
- OWASP Top 10 for LLM Applications
- IAM least privilege patterns
- Secrets management (HashiCorp Vault, AWS Secrets Manager)
- Zero Trust architecture
- mTLS, SPIFFE/SPIRE
- Network policies in Kubernetes
- Container security (image scanning, runtime security with Falco)
- SOC 2, GDPR, HIPAA basics

**Resources:**
- "The Tangled Web" — Michal Zalewski
- HackTricks (online wiki for security testing)
- Snyk's security learning resources

### 10.2 Observability

The three pillars + GenAI extensions:

**Tools to know:**
- Prometheus + Grafana (metrics)
- Loki or ELK (logs)
- Tempo or Jaeger (traces)
- OpenTelemetry (the unified standard)
- Datadog or New Relic (managed alternatives)
- LangSmith / Phoenix / Langfuse (AI-specific)

**Concepts:**
- SLO, SLI, SLA, error budgets
- RED method (Rate, Errors, Duration)
- USE method (Utilization, Saturation, Errors)
- Distributed tracing
- Cardinality explosion (the silent metric killer)

**Resources:**
- "Observability Engineering" — Charity Majors, Liz Fong-Jones, George Miranda
- Google's SRE book (free online)
- "Site Reliability Workbook" (free online)

### 10.3 Production Engineering

- Incident response (detect, triage, mitigate, resolve, postmortem)
- Runbooks
- On-call rotations
- Blameless postmortems
- Chaos engineering basics
- Cost optimization (FinOps)

---

## 11. Portfolio Projects

You need 3-4 projects that demonstrate the full FDE skill set. Each project should be deployed publicly, with documentation, observability, and a written architecture explanation.

### Project 1 — Enterprise RAG Platform

A production-grade RAG system that you would actually deploy at a customer.

**Must include:**
- Multi-tenant document ingestion
- Hybrid retrieval (vector + BM25)
- Cross-encoder reranking
- Streaming chat UI with citations
- SSO (Auth0 or Cognito)
- ACL-aware retrieval
- Deployed to AWS EKS via Terraform
- ArgoCD GitOps pipeline
- Prometheus + Grafana dashboards
- Eval harness with 50+ questions
- Cost dashboard

**Write-up to publish:**
- Architecture diagram and rationale
- Trade-off decisions
- Cost analysis
- Demo video

### Project 2 — Multi-Agent System

A working agent that solves a real task end-to-end.

**Must include:**
- Planner agent that decomposes goals
- 3+ specialist agents with scoped tools
- Tool integrations via MCP
- Durable workflow execution via Temporal
- Memory store (Redis + vector DB)
- Step limits, cost caps, human-in-the-loop
- Trace UI showing each agent step
- Deployed to Kubernetes

### Project 3 — Production AI Chat Platform

A ChatGPT-like product deployed at scale.

**Must include:**
- Streaming chat UI (Next.js)
- FastAPI or NestJS backend
- Multi-model routing (small for easy, frontier for hard)
- LLM gateway with caching (LiteLLM or custom)
- Rate limiting and per-user budgets
- EKS deployment with autoscaling
- OpenTelemetry tracing
- A/B testing infra for prompt changes
- CI/CD with eval gates

### Project 4 — Infrastructure Showcase

A pure-infra project demonstrating your Terraform + Kubernetes depth.

**Must include:**
- Complete VPC + EKS + RDS + ElastiCache + S3 setup via Terraform modules
- Helm charts for an internal service
- ArgoCD app-of-apps pattern
- Network policies, RBAC, OPA policies
- Multi-environment (dev/staging/prod) via Terraform workspaces
- Documented disaster recovery plan

### How to Showcase

For each project, publish:
- **GitHub repo** with README, architecture diagram, deployment instructions
- **Blog post** explaining decisions and trade-offs
- **Live demo** (or video if cost prohibits a permanent deployment)
- **LinkedIn post** announcing each one

---

## 12. Target Companies — Names, What They Want, How to Apply

This is the actionable list. Each company has a specific name for the role and specific things they prioritize.

### 12.1 Tier 1 — The Companies That Invented or Popularized FDE

#### Palantir Technologies
- **Role title:** Forward Deployed Engineer, Forward Deployed Software Engineer
- **Locations:** NYC, DC, Denver, London, Tokyo, Sydney
- **What they want:** Strong generalist engineers who can build prototypes fast, integrate with messy customer data, and work on classified/regulated environments
- **Stack signals:** Python, Java, TypeScript, React, Kubernetes
- **Compensation:** $180k-$350k+ base; significant equity
- **How to stand out:** Show prototype velocity. Build something end-to-end in 2 weeks and document the speed. Demonstrate work in regulated/messy data environments.
- **Apply:** palantir.com/careers — search "Forward Deployed"

#### OpenAI
- **Role titles:** Solutions Engineer, Forward Deployed Engineer, Applied AI Engineer
- **Locations:** San Francisco, NYC, London, Tokyo, Dublin
- **What they want:** Engineers who can deeply implement OpenAI's products in customer environments — fine-tuning, RAG, agents, evals
- **Stack signals:** Python, OpenAI SDK, LangChain, vector DBs, AWS/GCP/Azure
- **Compensation:** $250k-$500k+ total comp
- **How to stand out:** Build with OpenAI products publicly. Contribute to OpenAI cookbooks or write technical blog posts about advanced patterns.
- **Apply:** openai.com/careers

#### Anthropic
- **Role titles:** Applied AI Engineer, Solutions Architect, Forward Deployed Engineer
- **Locations:** San Francisco, NYC, Seattle, London
- **What they want:** Customer-facing engineers who can deploy Claude in complex enterprise environments and develop agent + tool-use solutions
- **Stack signals:** Python, Claude API, MCP, RAG, vector DBs
- **Compensation:** $250k-$500k+ total comp
- **How to stand out:** Build with Claude + MCP. Demonstrate agent and tool-use depth.
- **Apply:** anthropic.com/careers

#### Scale AI
- **Role titles:** Solutions Engineer, Forward Deployed Engineer, AI Engineer
- **Locations:** San Francisco, NYC, DC (defense focus)
- **What they want:** Engineers who can deploy custom AI evaluation, fine-tuning, and data labeling pipelines for enterprise and government customers
- **Stack signals:** Python, ML platforms, data engineering, AWS GovCloud
- **Compensation:** $200k-$400k+ total comp
- **How to stand out:** Show data-pipeline work, model evaluation expertise, security clearance is a major plus
- **Apply:** scale.com/careers

#### Anduril Industries
- **Role titles:** Forward Deployed Engineer, Mission Software Engineer
- **Locations:** Costa Mesa CA, DC, Boston, Seattle
- **What they want:** Engineers who can deploy autonomous defense systems in field environments
- **Stack signals:** C++, Rust, Python, real-time systems, embedded, distributed systems
- **Compensation:** $200k-$400k+ base
- **Constraint:** US citizenship required for most roles
- **How to stand out:** Robotics, real-time systems, defense or aerospace background
- **Apply:** anduril.com/careers

### 12.2 Tier 2 — AI Infrastructure & Foundation Model Companies

#### Cohere
- **Role:** Solutions Architect, Field Engineer
- **What they want:** Enterprise AI deployment expertise, retrieval-augmented systems
- **Apply:** cohere.com/careers

#### Mistral AI
- **Role:** Solutions Engineer, Forward Deployed Engineer
- **Locations:** Paris, San Francisco, London
- **What they want:** European AI deployments, custom fine-tuning
- **Apply:** mistral.ai/careers

#### Hugging Face
- **Role:** Solutions Engineer, Customer Engineer
- **What they want:** Open-source AI deployment, model serving, ecosystem expertise
- **Apply:** huggingface.co/jobs

#### Together AI
- **Role:** Solutions Engineer, AI Engineer
- **What they want:** Inference platform deployments, GPU workloads
- **Apply:** together.ai/careers

#### Fireworks AI, Replicate, Modal, Lambda Labs
- **Roles:** Solutions Engineer, Developer Advocate
- **What they want:** Inference platform expertise, developer experience

#### Glean
- **Role:** Forward Deployed Engineer, Solutions Engineer
- **What they want:** Enterprise search and RAG deployments
- **Apply:** glean.com/careers

#### Sierra (Bret Taylor's company)
- **Role:** Forward Deployed Engineer
- **What they want:** Conversational AI deployment for enterprise customer service
- **Apply:** sierra.ai/careers

#### Adept, Imbue, Inflection, Character AI (and successors)
- **Roles:** Applied AI Engineer, Solutions Engineer

### 12.3 Tier 3 — Cloud Providers & AI Infrastructure

#### Amazon Web Services
- **Role:** Solutions Architect, Specialist SA (AI/ML), ProServe Consultant
- **Compensation:** $180k-$350k
- **Apply:** amazon.jobs

#### Google Cloud
- **Role:** Customer Engineer, AI Specialist, Professional Services Engineer
- **Compensation:** $180k-$400k
- **Apply:** careers.google.com

#### Microsoft / Azure
- **Role:** Cloud Solution Architect, AI Specialist
- **Compensation:** $180k-$350k
- **Apply:** careers.microsoft.com

#### Databricks
- **Role:** Resident Solutions Architect, Specialist SA, Field Engineer
- **What they want:** ML platform expertise, Spark, lakehouse architecture
- **Compensation:** $200k-$400k
- **Apply:** databricks.com/company/careers

#### Snowflake
- **Role:** Field CTO, Solutions Engineer, Sales Engineer
- **What they want:** Data warehouse and analytics expertise
- **Apply:** careers.snowflake.com

### 12.4 Tier 4 — Developer Tools / Infrastructure

#### HashiCorp (now IBM)
- **Role:** Solutions Engineer
- **What they want:** Terraform, Vault, Consul expertise

#### Confluent
- **Role:** Solutions Engineer
- **What they want:** Kafka deep expertise, streaming architectures

#### Datadog
- **Role:** Solutions Engineer
- **What they want:** Observability expertise, customer onboarding

#### Stripe
- **Role:** Solutions Engineer, Developer Solutions Engineer
- **What they want:** Payments integration, developer experience

#### Cloudflare
- **Role:** Solutions Engineer, Specialist SE (AI/ML, Zero Trust)
- **What they want:** Edge computing, security, networking

#### Vercel
- **Role:** Solutions Engineer, Developer Experience Engineer
- **What they want:** Next.js, edge, AI SDK expertise

#### Supabase, Neon, PlanetScale, Turso
- **Roles:** Developer Advocate, Solutions Engineer
- **What they want:** Database + developer experience

### 12.5 Tier 5 — Enterprise AI & Vertical AI Startups

These are growing fastest. Many seed/Series A companies hire FDEs as employee #5-#30.

- **Harvey** (legal AI) — Applied AI Engineer
- **Hippocratic AI** (healthcare AI) — Forward Deployed Engineer
- **Hebbia** (knowledge work AI) — Forward Deployed Engineer
- **Reka** (enterprise AI) — Solutions Engineer
- **Decagon** (customer service AI) — Forward Deployed Engineer
- **Cresta** (contact center AI) — Solutions Engineer
- **Writer.com** (enterprise generative AI) — Solutions Engineer
- **Jasper** — Solutions Engineer
- **Robust Intelligence, Lakera, Lasso Security** (AI safety) — various

### 12.6 What They Look At in Your Application

Across nearly all of these companies, the common signals:

**Mandatory:**
- Production deployment experience (not just code, but actually running things)
- Strong written communication
- One end-to-end project that proves you can ship

**Strong differentiators:**
- AI / LLM hands-on experience
- Kubernetes + cloud certifications
- Public technical writing (blog, GitHub)
- Open-source contributions
- Customer-facing experience in any form (consulting, support, devrel)

**Red flags they screen for:**
- All theory, no shipping
- Resume listing tools without depth
- No public artifacts
- Poor written communication in cover letter / outreach

---

## 13. Interview Preparation

### 13.1 The Typical Loop

FDE loops are 4-6 rounds, more varied than typical SWE loops:

1. **Recruiter screen** — culture fit, motivation, basic background
2. **Hiring manager screen** — depth check on past projects, problem-solving style
3. **Technical / coding** — usually 1-2 rounds. Lighter on algorithms than SWE, heavier on systems
4. **System design** — at least 1 round. Often AI-specific (design a RAG, design an agent platform)
5. **Customer simulation** — you walk into a "customer call" and have to extract requirements + propose a solution. This is unique to FDE/SE roles
6. **Executive / culture / final** — vision, communication, leadership

### 13.2 Coding Prep

Don't spend months on LeetCode. Aim for fluency at medium level (50-100 problems is enough).

Focus areas:
- Arrays, strings, hashmaps
- Trees and graphs basics
- Sliding window, two pointers
- Dynamic programming (just the common patterns)

Practice on:
- LeetCode (focus on medium)
- NeetCode 150 (curated list)
- Hello Interview (more practical questions)

### 13.3 System Design Prep

This is where you should spend most prep time.

**Resources:**
- ByteByteGo YouTube channel
- Hello Interview (specifically the AI/ML system design section)
- "Grokking the System Design Interview" on Educative
- "System Design Interview Volume 1 & 2" — Alex Xu
- Your handbook's Chapter 22 (AI System Design)

**Practice:**
- Pick one design per day for 30 days
- Whiteboard it on paper, then write up
- Time yourself to 45 minutes
- Cover: requirements, HLD, LLD, scale, failure modes, cost

### 13.4 Customer Simulation Prep

Many candidates flunk this round because they don't prepare.

**Practice:**
- Have a friend roleplay a confused customer
- They ask vague things like "we want AI for our docs"
- You must ask discovery questions, propose architecture, handle pushback
- 45 minutes

Read "The Mom Test" before this round.

### 13.5 Behavioral Prep

Have 10-12 stories ready, using the STAR format:

- A time you shipped under ambiguity
- A time you owned a production incident
- A time you disagreed with a stakeholder
- A time you simplified an over-engineered system
- A time you went outside your role to help a customer
- A time you said no to a customer request
- A time you learned a new technology fast
- A time you mentored someone
- A time you handled conflicting priorities
- A time you missed a deadline

### 13.6 Mock Interviews

- Pramp (free peer mocks)
- Interviewing.io (paid mocks with engineers from target companies)
- Hello Interview (paid AI-focused mocks)
- Or just trade with a friend

---

## 14. Compensation & Negotiation

### 14.1 Realistic Ranges (US, 2025-2026)

| Level | Base | Equity (annual) | Total |
|---|---|---|---|
| Mid (L3-L4 equiv) | $150-200k | $30-100k | $180-300k |
| Senior (L5) | $200-280k | $100-250k | $300-500k |
| Staff (L6) | $250-350k | $200-500k | $450-800k |
| Principal (L7) | $300-400k+ | $400k-1M+ | $700k-1.5M+ |

AI-first companies pay top of these ranges. Defense companies pay strong base, lower equity. Cloud providers (AWS, GCP, Azure) are mid-range.

International ranges are lower but still strong (especially in London, Singapore, Tokyo).

### 14.2 Negotiation Levers

- Base salary
- Equity grant (refresh schedule matters — ask)
- Sign-on bonus
- Target bonus (varies by company)
- Relocation
- Start date
- Title and level (affects all future bands)
- WFH / hybrid arrangement

### 14.3 Resources

- **levels.fyi** — actual comp data by company and level
- **"Negotiating Your Salary"** — Jack Chapman
- **Patrick McKenzie's negotiation essay** (kalzumeus.com) — read 3 times
- **"Never Split the Difference"** — Chris Voss

---

## 15. Daily, Weekly, Monthly Plan

### Daily (90 min minimum, 3 hours ideal)
- 30 min reading (books, docs, papers)
- 60 min hands-on building (project work)
- 30 min one focused skill (LeetCode, system design, or AWS labs)

### Weekly
- One blog post, GitHub commit, or written artifact
- One mock interview or system design practice
- One networking touchpoint (LinkedIn message, community engagement)

### Monthly
- Complete one major milestone on a portfolio project
- One newsletter / Twitter / LinkedIn post summarizing learnings
- Review and adjust the roadmap

### Quarterly
- Apply to 10-15 target companies
- Complete a major certification or finish a project
- Review compensation data and update target range

---

## 16. Common Mistakes to Avoid

- **Learning everything shallow.** Pick one cloud, one language, one inference server. Be deep before being wide.
- **No public artifacts.** Reviewers cannot evaluate what they cannot see.
- **All learning, no shipping.** Three deployed projects beat ten certifications.
- **Skipping customer/communication skills.** This is what separates an FDE from a SWE. Practice it.
- **Treating LeetCode as the priority.** For FDE roles, system design and project depth matter more.
- **Hopping companies for tiny raises early.** Stay 2+ years in your first role to learn the full lifecycle of customer engagements.
- **Avoiding "boring" enterprise work.** The hardest, best-paid FDE roles are at companies serving banks, hospitals, governments. Embrace messy enterprise environments.
- **Underestimating writing.** FDEs who can write clearly get promoted twice as fast.

---

## Final Notes

The FDE role is one of the highest-leverage software engineering paths in 2025-2026 because:

1. **Demand outstrips supply.** Every AI company needs deployment-fluent engineers.
2. **Compensation is at the top of the engineering market.**
3. **Career optionality is unusually wide.** You can pivot to founding, to architecture, to engineering management, to deep technical IC tracks.
4. **The work is hard, varied, and meaningful** — you see customers succeed because of work you did.

The roadmap above is long, but you don't need to finish it before applying. Aim to be **60-70% there** with one strong portfolio project, then start applying. The remaining 30% you'll learn faster on the job than alone.

Bookmark this file. Open it weekly. Mark off items as you complete them. Revise as the field evolves.

Good luck.
