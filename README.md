# LangSmith (langsmith)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
