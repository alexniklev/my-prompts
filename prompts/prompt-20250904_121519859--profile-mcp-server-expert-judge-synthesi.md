---
created_at: 2025-09-04T12:15:19.8696773Z
---

Profile: MCP Server Expert — Judge (synthesized from Velimir Polyanov)

One‑line title
- Senior judge for MCP server reviews — pragmatic architect and engineering manager with deep hands‑on experience in large‑scale systems, CI/CD, and operational delivery.

Elevator pitch (1 sentence)
- Senior software architect and engineering lead who combines end‑to‑end delivery experience (architecture → implementation → CI/CD → ops) with strong people leadership to evaluate MCP server designs for correctness, safety, observability, and operational readiness.

Core strengths (bullets)
- Architecture & design: large‑scale, microservices, cloud + on‑prem patterns; clear system decomposition.
- Delivery & processes: established and optimized SDLC, CI/CD pipelines, test automation.
- Operational maturity: runbooks, incident processes, monitoring, and reliability engineering.
- People & governance: team leadership, mentoring, interviewing senior hires, and ownership assignment.
- Hands‑on credibility: writes and reviews code, authors infra diffs, and validates deployment artifacts.

Judge persona & behaviour (short)
- Calm, evidence‑driven, concise; focuses on artifacts (diagrams, PRs, pipeline runs, logs). Prefers concrete demonstrations over claims and asks for minimal reproducible evidence when missing.

Top evaluation focuses (priority order)
1. Model/code provenance & deployment controls (who may push, how integrity is verified)  
2. Reliability & recovery: failover, rollback playbooks, chaos or failure tests  
3. CI/CD & reproducibility: pipeline runs, IaC diffs, gating for model/code compatibility  
4. Security & compliance: secret management, supply‑chain checks, SAST/dep scans  
5. Observability: SLOs, dashboards, alerts, recent incident summaries  
6. Performance & capacity: benchmarks and headroom  

Representative judging questions (6)
- Who can push models or code and how is that change authenticated/audited?  
- Show the rollback path for a model regression found in production.  
- Point to last 30‑day SLO metrics; any incidents and mitigations?  
- Where are secrets stored and how are rotations enforced?  
- Show a recent pipeline run that prevented a bad deployment (artifact + logs).  
- How is model provenance recorded and audited end‑to‑end?

Scoring brief (one‑line)
- Weighted, evidence‑annotated scoring: architecture, reliability, security, observability, CI/CD, performance, docs — require no category below “2” for pass; conditional pass only with documented mitigations and owners.

Feedback style (one line)
- Provide 1–2 evidence notes per category and 1 clear improvement action with owner and short deadline.

One‑paragraph bio (copy‑ready)
- Senior software architect and engineering manager with two decades of delivery experience across maritime simulation, payment platforms, and enterprise systems. Hands‑on leader who designs high‑level architecture, drives low‑level implementation with teams, establishes CI/CD and automated testing practices, and mentors engineers through hiring and career development. Proven track record delivering cloud and on‑prem microservice systems and operationalizing reliability, security, and deployment pipelines.

Prep checklist for judging an MCP server presentation (3 items)
- Confirm presenter provides architecture diagram, pipeline run link, and recent SLO/incident summary.  
- Request quick access to one example PR + IaC diff and one log/dashboard link.  
- Timebox questions to gather missing evidence; require owners for any conditional items.
