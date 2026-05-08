# LangSmith (langsmith)

LangSmith is the observability, debugging, and evaluation platform for LLM applications, built by LangChain. The LangSmith API exposes tracing, dataset management, evaluation, prompt-hub, and Fleet agent functionality for AI engineering teams.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/langsmith/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=langsmith-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - AI, LLM, Observability, Evaluations, LangChain

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| LangSmith Tracing API | Capture and inspect traces for LLM, agent, and chain executions; primary unit of pricing. |
| LangSmith Datasets API | Manage datasets and example records for evaluation. |
| LangSmith Evaluations API | Run offline and online evaluations against datasets, with LLM-as-judge, code-based, and human evaluators. |
| LangSmith Prompt Hub API | Versioned prompt repository for storing, retrieving, and collaborating on LLM prompts. |
| LangSmith Feedback API | Attach human or programmatic feedback to runs and trace nodes. |
| LangSmith Annotation Queues API | Route runs to human reviewers and feed labels back into datasets. |
| LangSmith Fleet (Agent Deployment) API | Deploy and manage LangGraph agents in production via Fleet. |

## Common Properties

- [Website](https://smith.langchain.com/)
- [Documentation](https://docs.langchain.com/langsmith)
- [Pricing](https://www.langchain.com/pricing)
- [Plans](plans/langsmith-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/langsmith-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/langsmith-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/langsmith-plans-pricing.yml` | Developer (free) / Plus ($39/seat/mo + usage) / Enterprise |
| Rate Limits | `rate-limits/langsmith-rate-limits.yml` | Quota-based: monthly base traces and Fleet runs per plan |
| FinOps | `finops/langsmith-finops.yml` | Subscription + Usage billing model |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
