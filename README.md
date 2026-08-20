# Mochammad Alamsyah
 
Tokyo, Japan · relocating to Indonesia, Oct 2026 · [hi@malamsyah.com](mailto:hi@malamsyah.com) · [github.com/malamsyah](https://github.com/malamsyah) · [malamsyah.com](https://malamsyah.com)
 
---
 
## Summary
 
Software engineer with nine years building consumer-scale platforms across fintech, ride-hailing, and AI. Track record of full-stack delivery and leading distributed teams across Japan, India, Indonesia, and US time zones. Currently shipping production AI systems on Claude Agent SDK and AWS, with a focus on AI-native platform engineering.
 
---
 
## Skills
 
- **Languages:** Go, TypeScript / JavaScript, Python, Ruby, Java, Kotlin, Swift
- **Frontend:** React, Next.js, GraphQL, WebSocket
- **Backend & Infra:** Kubernetes, Docker, AWS (Lambda, ECS, Step Functions, CloudWatch), GCP (GKE), PostgreSQL, Redis, Prometheus
- **AI:** Claude API, Claude Agent SDK, prompt engineering, LLM evaluation, retrieval-augmented systems
- **Practice:** Distributed systems, system design, SRE, ADRs, incident response, code review & mentorship
---
 
## Experience
 
### Senior Software Engineer (Independent Contractor) — Mural Health
*Remote · Feb 2023 – Present*
 
*Key contributor scaling the platform from single-market to **dozens of countries globally** — multi-currency, multi-language, and multi-payment-gateway operations.*
 
- Prototyped a bulk-upload validation engine — duplicate detection, regex-based validation, country/currency rule matching — turning a ticket-analysis task into a working MVP.
- Built new authentication flow with Auth0 integration.
- Built currency layer calculation across multiple countries and payment gateways.
- Built ride-service and travel management integrations with third-party providers.
- Created a multilingual notification engine.
- **Stack:** Go, GraphQL, PostgreSQL, WebSocket, Claude Agent SDK, AWS Lambda, SAM.
### Tech Lead, Platform Application Division — Money Forward
*Tokyo, Japan · Dec 2025 – Aug 2026*
 
- Owned the company's **shared email-delivery platform** — the path used by both consumer and B2B products, sending ~300 million messages per month.
- Ended a recurring weekend incident pattern tied to traffic bursts: designed and shipped **rate limiting** from ADR through load testing to production in two months, retuned HPA scaling and MTA resources, and held zero error alerts thereafter.
- Defined the division's **service reliability maturity standard** and the assessment methodology behind it, then took two production services through it — authoring the documentation and aligning engineering, SRE, and the assessing team.
- Led the migration of a production orchestration service from **ECS to Kubernetes**: architectural analysis, orchestrator-layer gap identification, and bootstrapping. Authored a circuit-breaking ADR and tightened incident protocols to cut MTTR.
- **Stack:** Go, Kubernetes, AWS (ECS, Step Functions), Prometheus.
### Lead Software Engineer · Principal (AI & Data Platform) — S-Quantum Engine (Sinarmas)
*Jakarta, Indonesia · Mar 2023 – Mar 2025*
 
- Architected and led a team of engineers to build a **loan application system** for the used-vehicle market; provisioned end-to-end GCP infrastructure (development → production) with high availability and scalability.
- Architected and led the migration of the **company-wide data warehouse** from on-premise to **cloud-native serverless analytics** — decoupled compute from storage to match the actual weekly/monthly reporting cadence (replacing always-on, 24/7 VMs); **reduced data warehouse costs by 90%**.
- Built an **AI assistant for C-level executives** using an LLM with function calling against a data warehouse, enabling natural-language queries over business metrics — e.g., monthly revenue, biggest cost drivers, period-over-period trends.
- Built data pipelines and analytics dashboards to support multiple lines of business.
- **Stack:** Go, React, PostgreSQL, BigQuery, AWS Redshift, GKE, GCP, AWS, LLM function calling.
### Co-Founder — AccessTime
*Jakarta / Remote · May 2025 – Dec 2025*

- Set technical direction for WCAG-aligned accessibility tooling, built around the EU Accessibility Act thesis.
- Wound down after enforcement proved weaker than modelled.

### Senior Software Engineer — Gojek
*Bangalore & Jakarta · Jun 2018 – Mar 2023*
 
*Joined as an engineering trainee in Jakarta; converted to full-time in Bangalore, then promoted to Senior Software Engineer.*
 
**Platform Engineering**
 
- Decomposed a monolith into multiple microservices, improving scalability and maintainability.
- Built service integration tests (SIT) for five critical APIs.
- Developed a Go distributed-locking library on top of Redis Cluster.
- Assisted migration of primary services from VM-based deployment to Kubernetes.
- Reduced alert volume from 30+/week to fewer than 5.
**Booking Experience**
 
- Designed and built the ride-hailing homepage using BFF architecture, reducing API calls and improving user experience.
- Developed a phone-number masking feature to protect customers and drivers; later adopted across the organization.
- Upgraded JRuby and Rails for a core monolith, improving reliability and performance by 30%.
**Engineering Bootcamp**
 
- Mentored junior engineers on Clean Code, TDD, system design, and structured technical argumentation.
### Co-Founder & CTO — Teco Technology
*Jakarta · Sep 2017 – May 2018*
 
- Built the MVP for a bidding-based e-commerce platform (web + iOS).
- Developed integrations with multiple payment gateways and a WebSocket-based bidding engine.
- **Stack:** Go, React, Node.js, Swift, MySQL, Redis, WebSocket, Amazon SQS.
---
 
## Selected Projects
 
**[leakfix](https://github.com/malamsyah/leakfix)** — Go agent that turns secret-scan findings into provider-specific revocation runbooks and review-ready pull requests. Built on the Claude Agent SDK; revocation is never automated by design. Go, Kingfisher, git-filter-repo, go-github.
 
**[mindgraph-mcp](https://github.com/malamsyah/mindgraph-mcp)** — MCP memory server backed by Neo4j and Voyage embeddings, with semantic, full-text, and graph traversal over stored context. Go, deployed on Cloud Run.
 
**[nihongo.malamsyah.com](https://nihongo.malamsyah.com)** — Japanese learning platform with spaced repetition and AI-powered conversation practice. Built with Next.js on Vercel.
 
---
 
## Certifications
 
- **Google Cloud Professional Machine Learning Engineer** — Jul 2025
- **Claude Certified Architect (CCA)** — In progress, 2026 (Anthropic)
- **Google Cloud Associate Cloud Engineer** — Dec 2023
- **Certified Kubernetes Administrator (CKA)** — Jan 2023, The Linux Foundation
- **AWS Certified Solutions Architect – Associate** — Sep 2022
---
 
## Education
 
**Bachelor's Degree, Computer Science** — Bina Nusantara University · Sep 2013 – Jun 2017
