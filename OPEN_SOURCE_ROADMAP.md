# Open Source Roadmap

This roadmap tracks public open-source communities that align with my field: `Prompt Engineering for Enterprise AI Systems`.

The goal is not to accumulate passive forks. The goal is to make focused contributions around prompt lifecycle management, context engineering, agent orchestration, AI observability, guardrails, prompt injection defense, and multi-model runtime architecture.

## Flagship Original Repositories

| Repository | Purpose |
| --- | --- |
| [prompt-control-plane](https://github.com/kumarkasimala/prompt-control-plane) | Reference architecture for prompt systems as enterprise runtime infrastructure |
| [salesforce-agentforce-prompt-templates](https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates) | Public Salesforce/Agentforce-style prompt templates, grounding rules, and evaluation patterns |

## Primary Contribution Targets

| Area | Target repos | Contribution direction |
| --- | --- | --- |
| PromptOps and evals | [promptfoo](https://github.com/kumarkasimala/promptfoo), [langfuse](https://github.com/kumarkasimala/langfuse), [phoenix](https://github.com/kumarkasimala/phoenix) | Prompt-template regression suites, prompt lifecycle metadata, RAG/agent eval examples |
| Agent orchestration | [langgraph](https://github.com/kumarkasimala/langgraph), [agent-framework](https://github.com/kumarkasimala/agent-framework), [openai-agents-python](https://github.com/kumarkasimala/openai-agents-python) | Governed agent workflows, tool-call policy gates, structured outputs, human review paths |
| Observability standards | [semantic-conventions](https://github.com/kumarkasimala/semantic-conventions) | GenAI semantic attributes for prompt template version, grounding source, guardrail result, tool execution, and tenant-safe redaction |
| Security and guardrails | [OWASP LLM Top 10](https://github.com/kumarkasimala/www-project-top-10-for-large-language-model-applications), [PurpleLlama](https://github.com/kumarkasimala/PurpleLlama), [Guardrails](https://github.com/kumarkasimala/Guardrails) | Prompt injection boundaries, trusted instruction separation, policy-aware runtime patterns |
| Runtime routing and grounding | [litellm](https://github.com/kumarkasimala/litellm), [graphrag](https://github.com/kumarkasimala/graphrag), [llama_index](https://github.com/kumarkasimala/llama_index), [haystack](https://github.com/kumarkasimala/haystack) | Multi-model routing, cost/fallback telemetry, GraphRAG, context assembly, retrieval quality |

## First Public Contribution Ideas

1. OpenTelemetry semantic-conventions proposal for prompt runtime attributes.
2. promptfoo example pack for enterprise prompt-template regression tests.
3. LangGraph governed CRM agent workflow example with RAG, tool calls, structured output, and policy checks.
4. OWASP prompt injection boundary pattern for trusted instructions and untrusted enterprise data.
5. Phoenix or Langfuse example mapping prompt runtime metadata into traces and evals.

## What Counts as Evidence

- Merged PRs in active projects.
- Maintainer engagement on issues or design discussions.
- Examples accepted into official docs or example folders.
- Tagged releases in original repos.
- Reusable schemas, diagrams, eval cases, and runnable demos.

