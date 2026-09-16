# Mochammad Alamsyah

Senior Platform Engineer · Go, Kubernetes, AWS, GCP

hi@malamsyah.com | [linkedin.com/in/malamsyah](https://www.linkedin.com/in/malamsyah) | [malamsyah.com](https://malamsyah.com)
Indonesian citizen based in BSD City (Greater Jakarta), Indonesia | Open to remote roles, or relocation to Singapore with Employment Pass sponsorship
English, Indonesian, Japanese

---

## Projects

**[leakfix](https://github.com/malamsyah/leakfix)**
- Built a Go CLI that turned secret-scanning findings into provider-specific revocation runbooks and review-ready pull requests, using the Claude Agent SDK, Kingfisher, git-filter-repo, and go-github.
- Designed the agent so key revocation and git history rewrites were never executed automatically, keeping every irreversible operation behind human review.
- Ran leakfix as a pre-merge CI gate on my own repositories to stop new secrets before they reached the main branch.

**[mindgraph-mcp](https://github.com/malamsyah/mindgraph-mcp)**
- Built an MCP memory server in Go (mark3labs/mcp-go) backed by Neo4j AuraDB and Voyage AI embeddings, deployed on Google Cloud Run.
- Implemented hybrid retrieval by fusing full-text and semantic search with reciprocal rank fusion, so agents could recall stored context by keyword or by meaning.
- Added suggested links on write and code references as first-class nodes, so stored knowledge formed a connected graph instead of flat notes.

**toygrad-serve**
- Trained a character-level GPT in Python on a Sundanese text corpus and served it through a Go inference layer.
- Implemented prefill/decode separation and continuous batching in the serving layer to reproduce how production LLM inference engines schedule requests.

---

## Work History

*Senior Software Engineer (Independent Contractor), Mural Health, Remote* — *Feb 2023 to Current*
- Built and operated Go backend services for Mural Health's HIPAA-regulated clinical-trial payments platform as it scaled from a single-country launch to dozens of markets.
- Owned production authentication and authorization for regulated workloads, including the Auth0 login flow and the partner-facing service that let third parties connect to the API and initiate payments.
- Built the multi-currency calculation layer across countries and payment processors, so the platform could settle payments in each market's local currency.
- Shipped ride (Uber, Lyft) and travel (FROSCH) integrations on AWS Lambda in Go, reducing manual operational work around patient logistics.
- Built a multilingual notification engine so patient communications went out in each market's language.

*Tech Lead, Platform Application Division, Money Forward, Tokyo, Japan* — *Dec 2025 to Aug 2026*
- Owned Money Forward's shared email-delivery platform, sending about 300 million messages per month for consumer and B2B products, on Go, Kubernetes, and AWS.
- Designed and shipped rate limiting in two months, from ADR through load testing to production, and retuned HPA autoscaling and MTA resources, which ended a recurring weekend incident pattern with zero error alerts afterward.
- Defined the division's service reliability maturity standard and assessment method, then took two production services through it by writing the documentation and aligning engineering, SRE, and the assessing team.
- Led the migration of a production orchestration service built on AWS Step Functions from ECS to Kubernetes, covering architecture analysis, orchestrator-layer gap identification, and bootstrapping with SRE.
- Wrote a circuit-breaking ADR and tightened incident-handling protocols to reduce MTTR across the team's services.

*Lead Software Engineer (Principal, AI & Data Platform), S-Quantum Engine (Sinar Mas), Jakarta, Indonesia* — *Mar 2023 to Mar 2025*
- Architected and led the engineering team that built GARASI, a used-car loan-origination system, on Go, React, and PostgreSQL.
- Provisioned highly available GCP and GKE infrastructure for the loan platform from development through production.
- Migrated the company-wide data warehouse from on-prem Apache Hive to AWS Redshift Serverless, decoupling compute from storage to match reporting cadence and cutting warehouse cost by about 90%.
- Built an AI assistant for C-level executives using LLM function calling over the data warehouse, letting them ask about revenue, cost drivers, and period-over-period trends in plain language.
- Built data pipelines and Metabase dashboards that served multiple lines of business.

*Software Engineer Trainee to Senior Software Engineer, Gojek, Jakarta, Indonesia* — *Jun 2018 to Mar 2023*
- Reduced ride-hailing alert volume from about 30 per week to fewer than 5 as part of the platform reliability initiative.
- Led the decoupling of domains from the core transport monolith into Go microservices to improve scalability and maintainability.
- Built a Go distributed-locking library on Redis Cluster and service integration tests for five critical ride-hailing APIs.
- Helped migrate the primary ride-hailing services from VM-based deployment to Kubernetes.
- Built phone-number masking to protect customer and driver privacy, which was later adopted across the organization.
- Redesigned the ride-hailing homepage on a backend-for-frontend (BFF) architecture to cut client API calls, and upgraded JRuby and Rails on the core monolith for about 30% better performance.
- Mentored junior engineers on clean code, TDD, and system design in the Core Engineering Bootcamp.

*Co-Founder and CTO, Teco Technology (bejo.id), Jakarta, Indonesia* — *Sep 2017 to May 2018*
- Built the MVP of bejo.id, a bidding-based e-commerce website and iOS app, with Go, React, Node.js, and Swift.
- Built a real-time WebSocket bidding engine and integrated multiple payment gateways, using MySQL, Redis, and Amazon SQS.

---

## Certifications

- Google Cloud Professional Machine Learning Engineer
- Google Cloud Associate Cloud Engineer

## Education

- Bachelor's degree in Computer Science, Bina Nusantara University, Jakarta — Status: Graduated
