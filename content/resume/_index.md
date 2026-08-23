---
title: ""
date: 2026-08-23T18:41:59+02:00
draft: false
---

## Profile

Staff Platform Engineer with 15+ years of experience architecting resilient, multi-cloud (AWS, GCP) platforms, FinOps strategies, and zero-trust self-service infrastructure for 200+ engineers.

Proven technical leader driving complex multi-region migrations, Kubernetes orchestration, and DORA compliance, establishing engineering standards, and aligning platform roadmaps with business priorities to eliminate operational risk and optimize TCO.

Authored cross-domain platform RFCs and established Architectural Decision Records (ADRs), driving consensus across 20+ teams for IaC and multi-region deployment standards.

## Top Skills

- **Containers & Orchestration** — Expert: Docker, Helm, Containerd, Podman, Kubernetes
- **GitOps & CI/CD** — Expert: FluxCD, GitHub Actions, ArgoCD
- **Languages** — Advanced: Go, Bash, TypeScript, Python
- **Cloud Providers** — Advanced: GCP, Azure, IBM Cloud, DigitalOcean, AWS
- **IaC & Automation** — Expert: Terraform, Nix, Ansible, Pulumi
- **Networking** — Advanced: Cert-Manager, Istio, Cloudflare
- **Observability & Monitoring** — Advanced: Datadog, Prometheus, Grafana, Elasticsearch, OpenTelemetry
- **Security & Compliance** — Advanced: SOC 2, IAM Governance, KMS / Vault, Zero Trust, DORA, HashiCorp Vault

## Work Experience

### Prima Assicurazioni (prima.it) — Staff Platform Engineer (Jan 2025 - Present)

_Remote (EU)_

- **Core Platform Leadership & IaC Standards:** Lead a 6-engineer Core Platform team within the Infrastructure Domain supporting 200+ engineers; defined the platform roadmap and overhauled core Pulumi (Python) libraries, standardizing IaC definitions across 20+ engineering squads.
- **Large-Scale RDS Modernization:** Directed end-to-end multi-region PostgreSQL (Aurora RDS) major upgrade program across 10TB+ data footprints in the UK, Spain, and Italy with zero unplanned downtime; eliminated legacy extended-support risks and lowered cloud spend by modernizing RDS instance families.
- **Kafka Governance & Security Compliance:** Overhauled enterprise Kafka security and IAM governance (Zero Trust access, service account consolidation, strict IaC alignment), reducing Kafka TCO by 30% (~€60K/year), cutting onboarding time by 50%, and aligning with DORA regulatory standards.
- **Reliability & Technical Governance:** Established pre-mortem documentation standards, migration guidelines, and operational runbooks, serving as technical anchor and resolving high-stakes architectural blockers during incidents.

### Sysdig — Staff Infrastructure Engineer (Jan 2023 - Jan 2025)

_Remote (EU)_

- **Platform Team Leadership & Talent Enablement:** Served as Tech Lead for a 3-engineer infrastructure squad; led technical hiring panels, onboarded 2 senior engineers, and fostered cross-team collaboration across all engineering departments to deliver quarterly infrastructure initiatives on schedule.
- **CI/CD Modernization:** Spearheaded company-wide CI migration from legacy Jenkins to GitHub Actions with auto-scaling self-hosted runners on Kubernetes across 100+ repositories, reducing CI queue times by 45% and cutting cloud compute costs by €45K/month.
- **GitOps Self-Service Adoption:** Architected and rolled out FluxCD-based GitOps Continuous Delivery across global Kubernetes clusters, accelerating release velocity by 10x and eliminating cluster drift through automated self-reconciliation.
- **Developer Experience & Nix Tooling:** Championed adoption of Nix shells and standardized OpenAPI specifications across customer-facing services, slashing local environment configuration time from hours to minutes.
- **Reliability Engineering & SRE:** Introduced and reviewed service-level objectives (SLOs/SLIs) across critical SaaS services, improving platform uptime and serving as Incident Commander on L2/L3 SaaS incident rotations.

### Sysdig — Sr. Infrastructure Engineer (Oct 2020 - Jan 2023)

_Remote (EU)_

- **Global Multi-Cloud Scale:** Maintained and scaled global SaaS infrastructure spanning 15 regions and 4 major cloud providers (AWS, GCP, IBM Cloud), ensuring high availability for enterprise customers.
- **Container Egress & Reliability Optimization:** Designed and deployed a Containerd pull-through caching layer across Kubernetes clusters, halving network data egress costs by ~€15K/month and eliminating single-point-of-failure risks during upstream registry outages.
- **IaC Standardization:** Replaced manual cloud provisioning by architecting comprehensive Terraform IaC modules with strict tagging and naming conventions across AWS, GCP, and IBM Cloud.
- **Stateful Data Services Lifecycle:** Managed distributed data stores at scale on Kubernetes (Kafka, Cassandra, Elasticsearch, Redis, PostgreSQL, NATS); led successful migration from self-hosted Redis to AWS ElastiCache to resolve chronic scaling bottlenecks.

### Kiratech — Sr. DevOps Engineer (Oct 2019 - Oct 2020)

_Remote (Italy)_

- **Enterprise Cloud & DevOps Consulting:** Delivered infrastructure modernization, cloud-native migrations, and platform sizing for 4 Tier-1 banking and fintech clients.
- **Kubernetes & GitOps Implementations:** Designed and deployed 3 production-ready Kubernetes clusters across 4 environments (dev, integration, pre-prod, prod) using Infrastructure as Code (Terraform) and GitOps principles, reducing provisioning cycle times by over 60%.
- **Technical Enablement & Training:** Linux Foundation Certified Instructor delivering high-impact corporate training and certification bootcamps with classes of 30+ engineers for CKA (Certified Kubernetes Administrator) and CKAD curricula.

### Facilitylive — DevOps Engineer / SCM (May 2016 - Oct 2019)

_Pavia (Italy)_

- **Microservices & Kubernetes Architecture:** Re-architected the core search engine product from a monolithic platform into a scalable microservices architecture on Kubernetes (vSphere, Spring Cloud, Consul, Prometheus/Grafana), boosting system resilience (limiting failure blast radius to <5% of product capabilities) and throughput.
- **Software-Defined Datacenter (SDDC) IaC:** Automated on-premise datacenter provisioning using Terraform, Packer, and VMware NSX-T, codifying bare-metal/virtualized infrastructure into repeatable IaC blueprints and improving development velocity by 2x.
- **CI/CD Pipelines & Developer Tooling:** Built and maintained organization-wide Jenkins CI/CD pipelines and authored custom Python/Go CLI and REST operational tools to streamline developer troubleshooting and reduce incident MTTR by 20%.
- **DevOps Evangelism & Production Reliability:** Mentored cross-functional development squads of 50+ engineers on cloud-native practices and served on L2 on-call rotations for production Kubernetes clusters.

### Early Career — System & Database Administrator (Jun 2007 - May 2016)

_Various Companies_

Held System Administrator, Software Configuration Manager, and Database Administrator roles across Murphy's Audio, Fastweb IT, Vodafone Italy, and Tecnobeta S.a.S.

**Tech Stack:** Linux, Bash, Oracle DB, VMware, vSphere, Unix, Windows Server 2008, Java, .NET, WebSphere, JBoss, Tomcat

## Projects

### PDH - PagerDuty for Humans (2020 - Present)

- Engineered an open-source Python/FastAPI CLI tool integrating PagerDuty REST APIs to automate rule-based alert triage and reactive incident workflows.
- Adopted across 20+ Sysdig SREs and on-call engineers, reducing incident response friction and alarm MTTR by 25%.
- Actively maintained as an open-source tool with 4 external contributors, 6 forks, and 15 GitHub stars.

[https://github.com/mbovo/pdh](https://github.com/mbovo/pdh)

### Autodoc Operator (2024)

- Authored a Go and Kubebuilder Kubernetes operator that dynamically discovers, merges, and serves unified OpenAPI documentation across deployed services.
- Eliminated documentation drift across 40+ microservices and reduced cross-team API onboarding friction by 50%.

[https://github.com/mbovo/autodoc](https://github.com/mbovo/autodoc)

### SDCAdmin Operator (2021)

- Developed a custom Go Kubernetes operator automating GitOps-driven IAM access governance, peer approvals, and privilege reconciliation.
- Slashed administrative access turnaround from hours to a 5-minute audited Git Pull Request while enforcing continuous Zero Trust compliance.

[https://github.com/mbovo/sdcadminoper](https://github.com/mbovo/sdcadminoper)

## Education

### Università Statale di Milano — Bachelor of Science, Computer Science (2008 - 2011)

_Milan, Italy_

## Certifications

### GitOps at Scale — Codefresh (2024)

[https://www.credly.com/badges/71da594b-68ae-4c4c-94ad-dfc397e7379d](https://www.credly.com/badges/71da594b-68ae-4c4c-94ad-dfc397e7379d)

### GitOps Fundamentals — Codefresh (2022)

[https://www.credly.com/badges/0b184bcf-53bf-4645-b4e3-3eb0856d3141](https://www.credly.com/badges/0b184bcf-53bf-4645-b4e3-3eb0856d3141)

### Certified Kubernetes Administrator — Linux Foundation (2019 - 2022)

[https://www.credly.com/badges/b03be37e-5e02-40e5-bc66-ccde0d81250c](https://www.credly.com/badges/b03be37e-5e02-40e5-bc66-ccde0d81250c)

## Languages

- **Italian** — native
- **English** — fluent
- **Spanish** — basic
