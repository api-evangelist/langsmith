# LangSmith (langsmith)

LangSmith is the observability, debugging, and evaluation platform for LLM applications, built by LangChain. The LangSmith API exposes tracing, dataset management, evaluation, prompt-hub, and Fleet agent functionality for AI engineering teams.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/langsmith/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/langsmith/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Observability
- Evaluations
- LangChain

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### LangSmith Tracing API

Capture, ingest, and inspect traces for LLM, agent, and chain executions. Traces include nested runs (spans), latency, token counts, errors, inputs/outputs, and metadata. Tracing is the primary unit of pricing on LangSmith.

- **Human URL:** [https://docs.langchain.com/langsmith/tracing](https://docs.langchain.com/langsmith/tracing)
- **Base URL:** `https://api.smith.langchain.com`

#### Tags

- Tracing
- Observability
- LLM

#### Properties

- [Documentation](https://docs.langchain.com/langsmith)
- [API Reference](https://docs.langchain.com/langsmith/tracing)
- [OpenAPI](openapi/langsmith-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langsmith.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langsmith.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangSmith Datasets API

Manage datasets and example records used as ground-truth or test inputs for evaluating LLM applications. Supports CRUD on datasets, examples, and dataset splits.

- **Human URL:** [https://docs.langchain.com/langsmith/datasets](https://docs.langchain.com/langsmith/datasets)
- **Base URL:** `https://api.smith.langchain.com`

#### Tags

- Datasets
- Examples
- Evaluations

#### Properties

- [Documentation](https://docs.langchain.com/langsmith/datasets)
- [OpenAPI](openapi/langsmith-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langsmith.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langsmith.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangSmith Evaluations API

Run offline and online evaluations against datasets, attach feedback and scores to runs, and compare experiments. Supports LLM-as-judge, code-based, and human evaluators.

- **Human URL:** [https://docs.langchain.com/langsmith/evaluation](https://docs.langchain.com/langsmith/evaluation)
- **Base URL:** `https://api.smith.langchain.com`

#### Tags

- Evaluations
- Experiments
- LLM

#### Properties

- [Documentation](https://docs.langchain.com/langsmith/evaluation)
- [OpenAPI](openapi/langsmith-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langsmith.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langsmith.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangSmith Prompt Hub API

Versioned prompt repository (Prompt Hub) for storing, retrieving, and collaborating on LLM prompts. Supports tagged versions, public/private prompts, and pull/push from SDKs.

- **Human URL:** [https://docs.langchain.com/langsmith/prompt-hub](https://docs.langchain.com/langsmith/prompt-hub)
- **Base URL:** `https://api.smith.langchain.com`

#### Tags

- Prompts
- Prompt Management
- LLM

#### Properties

- [Documentation](https://docs.langchain.com/langsmith/prompt-hub)
- [OpenAPI](openapi/langsmith-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langsmith.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langsmith.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangSmith Feedback API

Attach human or programmatic feedback (scores, comments, correction labels) to runs and trace nodes for evaluation, monitoring, and reinforcement signal collection.

- **Human URL:** [https://docs.langchain.com/langsmith/feedback](https://docs.langchain.com/langsmith/feedback)
- **Base URL:** `https://api.smith.langchain.com`

#### Tags

- Feedback
- Scoring
- Evaluations

#### Properties

- [Documentation](https://docs.langchain.com/langsmith/feedback)
- [OpenAPI](openapi/langsmith-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langsmith.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langsmith.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangSmith Annotation Queues API

Route runs to human reviewers via annotation queues. Reviewers grade outputs, attach corrections, and feed labels back into datasets for evaluation and fine-tuning.

- **Human URL:** [https://docs.langchain.com/langsmith/annotation-queues](https://docs.langchain.com/langsmith/annotation-queues)
- **Base URL:** `https://api.smith.langchain.com`

#### Tags

- Annotation
- Human Review
- Evaluations

#### Properties

- [Documentation](https://docs.langchain.com/langsmith/annotation-queues)
- [OpenAPI](openapi/langsmith-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langsmith.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langsmith.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangSmith Fleet (Agent Deployment) API

Deploy and manage LangGraph agents in production via Fleet. Provides agent invocation, run management, scheduled jobs, and uptime billing for hosted agent deployments.

- **Human URL:** [https://docs.langchain.com/langsmith/deployments](https://docs.langchain.com/langsmith/deployments)
- **Base URL:** `https://api.smith.langchain.com`

#### Tags

- Agents
- Deployment
- LangGraph

#### Properties

- [Documentation](https://docs.langchain.com/langsmith/deployments)
- [OpenAPI](openapi/langsmith-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langsmith.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langsmith.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://smith.langchain.com/)
- [Documentation](https://docs.langchain.com/langsmith)
- [Pricing](https://www.langchain.com/pricing)
- [Plans](plans/langsmith-plans-pricing.yml)
- [Rate Limits](rate-limits/langsmith-rate-limits.yml)
- [Fin Ops](finops/langsmith-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
