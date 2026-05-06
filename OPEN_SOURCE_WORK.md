# Open Source Work

This page tracks public open-source areas that align with my technical focus: `Prompt Engineering for Enterprise AI Systems`.

The goal is focused work around prompt lifecycle management, context engineering, agent orchestration, AI observability, guardrails, prompt injection defense, and multi-model runtime architecture.

## Primary Repositories

| Repository | Purpose |
| --- | --- |
| [prompt-control-plane](https://github.com/kumarkasimala/prompt-control-plane) | Reference architecture, schema, CRM support example, telemetry notes, and promptfoo eval config for prompt systems as enterprise runtime infrastructure |
| [salesforce-agentforce-prompt-templates](https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates) | Public Salesforce/Agentforce-style prompt templates, grounding rules, and evaluation patterns |

## Current Artifacts

| Artifact | Link |
| --- | --- |
| Prompt runtime JSON schema | https://github.com/kumarkasimala/prompt-control-plane/blob/main/schemas/prompt-runtime.schema.json |
| Design notes | https://github.com/kumarkasimala/prompt-control-plane/blob/main/docs/original-contribution.md |
| Runtime architecture diagram | https://github.com/kumarkasimala/prompt-control-plane/blob/main/docs/architecture.md |
| Telemetry attribute notes | https://github.com/kumarkasimala/prompt-control-plane/blob/main/docs/telemetry.md |
| CRM support prompt example | https://github.com/kumarkasimala/prompt-control-plane/blob/main/examples/crm-support/templates/case-summary.prompt.json |
| Promptfoo regression config | https://github.com/kumarkasimala/prompt-control-plane/blob/main/examples/crm-support/evals/promptfoo.yaml |
| prompt-control-plane v0.1.0 release | https://github.com/kumarkasimala/prompt-control-plane/releases/tag/v0.1.0 |
| Public CRM prompt template examples | https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates/tree/main/templates |
| Agentforce-style prompt template docs | https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates/tree/main/docs |
| salesforce-agentforce-prompt-templates v0.1.0 release | https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates/releases/tag/v0.1.0 |

## Active Areas

| Area | Target repos | Work direction |
| --- | --- | --- |
| PromptOps and evals | [promptfoo](https://github.com/kumarkasimala/promptfoo), [langfuse](https://github.com/kumarkasimala/langfuse), [phoenix](https://github.com/kumarkasimala/phoenix) | Prompt-template regression suites, prompt lifecycle metadata, RAG/agent eval examples |
| Agent orchestration | [langgraph](https://github.com/kumarkasimala/langgraph), [agent-framework](https://github.com/kumarkasimala/agent-framework), [openai-agents-python](https://github.com/kumarkasimala/openai-agents-python) | Governed agent workflows, tool-call policy gates, structured outputs, human review paths |
| Observability standards | [semantic-conventions](https://github.com/kumarkasimala/semantic-conventions) | GenAI semantic attributes for prompt template version, grounding source, guardrail result, tool execution, and tenant-safe redaction |
| Security and guardrails | [OWASP LLM Top 10](https://github.com/kumarkasimala/www-project-top-10-for-large-language-model-applications), [PurpleLlama](https://github.com/kumarkasimala/PurpleLlama), [Guardrails](https://github.com/kumarkasimala/Guardrails) | Prompt injection boundaries, trusted instruction separation, policy-aware runtime patterns |
| Runtime routing and grounding | [litellm](https://github.com/kumarkasimala/litellm), [graphrag](https://github.com/kumarkasimala/graphrag), [llama_index](https://github.com/kumarkasimala/llama_index), [haystack](https://github.com/kumarkasimala/haystack) | Multi-model routing, cost/fallback telemetry, GraphRAG, context assembly, retrieval quality |

## Near-Term Ideas

1. OpenTelemetry semantic-conventions proposal for prompt runtime attributes.
2. promptfoo example pack for enterprise prompt-template regression tests.
3. LangGraph governed CRM agent workflow example with RAG, tool calls, structured output, and policy checks.
4. OWASP prompt injection boundary pattern for trusted instructions and untrusted enterprise data.
5. Phoenix or Langfuse example mapping prompt runtime metadata into traces and evals.
