<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img width="100%" src="./assets/banner.svg" alt="Pavan Sai R — Senior Data and AI Engineer">
</picture>

<p align="center">
  <a href="https://github.com/PSR94?tab=repositories">Repositories</a>
  ·
  <a href="https://github.com/search?q=is%3Apr+author%3APSR94&type=pullrequests">Open-source contributions</a>
  ·
  <a href="https://psr94.github.io/ai-engineer-roadmap-custom/">AI Engineer Roadmap</a>
</p>

## About

I build data and AI systems for real operating environments. My work spans governed data foundations, retrieval and knowledge systems, agent workflows, evaluation, observability, APIs, and product interfaces.

I focus on engineering concerns that determine whether an AI system survives beyond a demo: data quality, explicit system boundaries, measurable behavior, reviewable decisions, failure recovery, and maintainable delivery.

Current areas of emphasis include Microsoft Fabric and Azure modernization, enterprise retrieval, model-risk evaluation, agent operations, and full-stack AI products.

## Selected systems

### [TransitionIQ](https://github.com/PSR94/TransitionIQ)

Workforce health transition navigator with role-specific workflows for employers, employees, consultants, and administrators. Covers coverage scenarios, recommendation review, stipend planning, and audit history.

*TypeScript · React · Express · PostgreSQL · Drizzle*

### [FabricShift](https://github.com/PSR94/fabricshift)

Microsoft Fabric migration-readiness workbench for legacy estate inventory, target mapping, blocker analysis, reconciliation, lineage, migration-wave planning, and executive reporting.

*Microsoft Fabric · TypeScript · React · Express · Python*

### [VANGUARD](https://github.com/PSR94/VANGUARD)

Engineering-intelligence platform for pull-request risk scoring, blast-radius analysis, CI and test-gap diagnostics, policy decisions, and release readiness.

*Python · FastAPI · Next.js · Neo4j · OpenSearch · Redis*

### [ContextMesh](https://github.com/PSR94/ContextMesh)

Private knowledge platform combining dense and sparse retrieval, graph-aware context, query planning, reranking, evidence packaging, and persisted execution traces.

*Python · FastAPI · Qdrant · Neo4j · RAG*

### [ARGUS](https://github.com/PSR94/ARGUS)

LLM risk-evaluation platform covering prompt injection, unsafe tool use, PII leakage, citation failures, guardrail behavior, reviewable findings, and CI policy gates.

*Python · FastAPI · LLM evaluation · Guardrails · CI*

### [ResumeTailor](https://github.com/PSR94/resume-tailor)

Local-first resume tailoring that scores bullets against a role, generates targeted replacements through a prompt bridge, preserves DOCX structure, and keeps every change reviewable.

*React · TypeScript · FastAPI · python-docx*

## Portfolio by domain

- **Agent systems and operations:** [VANGUARD](https://github.com/PSR94/VANGUARD), [ARGUS](https://github.com/PSR94/ARGUS), [ORION](https://github.com/PSR94/ORION), [CALLSIGNAL](https://github.com/PSR94/CALLSIGNAL)
- **Knowledge and retrieval:** [ContextMesh](https://github.com/PSR94/ContextMesh), [CITADEL](https://github.com/PSR94/citadel), [Evidence Graph RAG](https://github.com/PSR94/knowledge_graph_rag)
- **Data and enterprise workflows:** [FabricShift](https://github.com/PSR94/fabricshift), [HELIOS](https://github.com/PSR94/helios), [TransitionIQ](https://github.com/PSR94/TransitionIQ)
- **Developer and learning products:** [ResumeTailor](https://github.com/PSR94/resume-tailor), [AI Engineer Roadmap 2026](https://psr94.github.io/ai-engineer-roadmap-custom/)

Earlier work includes a [Streamlit image-to-text application](https://github.com/PSR94/image2textapp) and [applied machine-learning notebooks](https://github.com/PSR94/AML).

## Open source

Recent upstream work includes:

- **Pydantic** — corrected the contributor-guide pre-commit installation command. [Merged PR #13435](https://github.com/pydantic/pydantic/pull/13435)
- **Vertex AI Python SDK** — multi-turn agent response normalization, safer execution-credential defaults, and prompt version metadata. [#6975](https://github.com/googleapis/python-aiplatform/pull/6975), [#6983](https://github.com/googleapis/python-aiplatform/pull/6983), [#6984](https://github.com/googleapis/python-aiplatform/pull/6984)
- **vLLM** — parallel-sampling output tests and ModelOpt loading documentation. [#48062](https://github.com/vllm-project/vllm/pull/48062), [#48063](https://github.com/vllm-project/vllm/pull/48063)
- **Semantic Kernel** — preserved explicit `None` defaults in Python function metadata. [#14145](https://github.com/microsoft/semantic-kernel/pull/14145)
- **Altair GraphQL Client** — added support for deeply nested schema types. [#3300](https://github.com/altair-graphql/altair/pull/3300)
- **ComparIA** — repaired and documented the dataset export workflow. [#596](https://github.com/betagouv/ComparIA/pull/596)
- **Kubeflow Pipelines** — routed the SDK formatting workflow through project make targets. [#13703](https://github.com/kubeflow/pipelines/pull/13703)

[View all authored pull requests](https://github.com/search?q=is%3Apr+author%3APSR94&type=pullrequests)

## Engineering stack

- **Languages:** Python, TypeScript, JavaScript, SQL, C#, Java
- **AI systems:** RAG, agent workflows, evaluation, guardrails, semantic search, graph retrieval, LLMOps
- **Data platforms:** Microsoft Fabric, Azure, Databricks, Snowflake, Delta Lake, DuckDB
- **Application engineering:** FastAPI, React, Next.js, PostgreSQL, Redis, MongoDB
- **Infrastructure:** Docker, Kubernetes, Terraform, AWS, Azure, GCP, GitHub Actions
- **Observability and governance:** OpenTelemetry, execution tracing, policy gates, audit history, human review

## Engineering principles

- Ground outputs in trusted data and explicit evidence.
- Keep agent state, tool boundaries, and approval paths inspectable.
- Evaluate behavior with repeatable test cases and regression gates.
- Design for operators, failure recovery, and long-term ownership.
- Document limitations as clearly as capabilities.

---

<p align="center">
  <a href="https://github.com/PSR94?tab=repositories">View all repositories</a>
</p>
