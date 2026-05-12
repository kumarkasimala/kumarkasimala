<p align="center">
  <img src="./assets/header.svg" alt="Kumar Kasimala profile banner" />
</p>

# Kumar Kasimala

Software Engineering Architect focused on enterprise AI platform architecture, prompt runtime systems, context engineering, and agentic AI.

![Prompt Runtime Architecture](https://img.shields.io/badge/Prompt%20Runtime-Enterprise%20AI-0ea5e9?style=flat-square)
![Context Engineering](https://img.shields.io/badge/Context%20Engineering-Grounded%20AI-0f766e?style=flat-square)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-Orchestration-f97316?style=flat-square)
![AI Governance](https://img.shields.io/badge/AI%20Governance-Trust%20%26%20Safety-7c3aed?style=flat-square)

I work on enterprise AI systems where prompts, context, tools, models, policies, evaluation, and observability behave like production runtime infrastructure.

My focus is not prompt writing alone. I work on the architecture behind reliable AI systems: reusable prompt templates, context grounding, runtime data resolution, retrieval, structured outputs, tool/action orchestration, evaluation, governance, and secure execution at enterprise scale.

## Focus Areas

- Enterprise prompt runtime architecture
- Context engineering and grounded AI
- Prompt lifecycle management and PromptOps
- Agentic AI orchestration with tools, actions, and workflow state
- Runtime data resolution, RAG, and trusted context assembly
- Structured outputs, validation, and evaluation
- Observability, telemetry, governance, and trust controls
- Prompt injection boundaries and safe handling of untrusted data
- Cloud-native, API-driven, multi-tenant AI platform architecture

## Public Architecture Work

### Enterprise Prompt Runtime Architecture

Production AI systems need more than well-written prompts.

In enterprise environments, prompts often define behavior, context access, tool usage, output format, escalation logic, safety constraints, and observability metadata. That makes them closer to governed runtime objects than static text assets.

My public architecture work explores how prompt-driven systems can be designed as reusable, testable, observable, and governed software infrastructure.

Core ideas include:

- versioned prompt templates
- typed and trust-labeled inputs
- context builders and grounding resolvers
- tool and action contracts
- model routing policies
- lifecycle hooks
- structured output contracts
- evaluation suites
- telemetry envelopes
- prompt injection boundaries

## Technical Themes

| Theme | What it means in practice |
| --- | --- |
| Prompt runtime architecture | Modeling prompts as governed runtime objects with metadata, policies, inputs, outputs, tools, and observability |
| Context engineering | Resolving, assembling, grounding, and governing enterprise context before model execution |
| Agentic orchestration | Coordinating prompts, tools, actions, retrieval, workflow state, and human review |
| PromptOps | Managing prompt lifecycle, versioning, testing, evaluation, release, rollback, and observability |
| AI trust and governance | Separating trusted instructions from untrusted data, enforcing policy boundaries, and improving traceability |
| Multi-tenant AI platforms | Designing scalable, secure, reusable AI infrastructure for enterprise applications |

## Reference Implementations

| Repository | Focus |
| --- | --- |
| [prompt-control-plane](https://github.com/kumarkasimala/prompt-control-plane) | Vendor-neutral reference architecture for enterprise prompt runtime infrastructure |
| [salesforce-agentforce-prompt-templates](https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates) | Public CRM-style prompt template examples for service, sales, field service, and governance workflows |

## Open Source Study and Contribution Areas

These repositories reflect areas I study, experiment with, and contribute ideas around:

| Area | Repositories |
| --- | --- |
| Agent orchestration | [langgraph](https://github.com/kumarkasimala/langgraph), [agent-framework](https://github.com/kumarkasimala/agent-framework), [openai-agents-python](https://github.com/kumarkasimala/openai-agents-python) |
| Prompt evaluation and PromptOps | [promptfoo](https://github.com/kumarkasimala/promptfoo), [langfuse](https://github.com/kumarkasimala/langfuse) |
| RAG and context engineering | [llama_index](https://github.com/kumarkasimala/llama_index), [haystack](https://github.com/kumarkasimala/haystack), [graphrag](https://github.com/kumarkasimala/graphrag) |
| Observability | [phoenix](https://github.com/kumarkasimala/phoenix), [semantic-conventions](https://github.com/kumarkasimala/semantic-conventions) |
| AI safety and governance | [OWASP LLM Top 10](https://github.com/kumarkasimala/www-project-top-10-for-large-language-model-applications), [PurpleLlama](https://github.com/kumarkasimala/PurpleLlama), [Guardrails](https://github.com/kumarkasimala/Guardrails) |
| Model routing and AI gateways | [litellm](https://github.com/kumarkasimala/litellm) |

## Selected Public Work

- [Google Scholar](https://scholar.google.com/citations?user=K5Q8wwoAAAAJ)
- [Patent: US11199944B2](https://patents.google.com/patent/US11199944B2/en)
- [SF Bay ACM talk: From Prompt Grounding to Edge Delivery](https://www.sfbayacm.org/event/from-prompt-grounding-to-edge-delivery-agentic-ai-at-scale/)
- [WCSC 2026 keynote](https://www.scrs.in/conference/wcsc2026/speaker/talk/2069)
- [TDX 2026: Lock in Prompt Response Formats with Structured Outputs](https://reg.salesforce.com/flow/plus/tdx26/sessioncatalog/page/catalog/session/1771032017004001Utp2)
- [Selected references, talks, publications, patent, and public links](./REFERENCES.md)
- [Open-source work and contribution areas](./OPEN_SOURCE_WORK.md)

## Current Technical Work

I am currently exploring public patterns for:

- treating prompts as runtime control-plane objects
- combining prompt engineering with context engineering
- building prompt lifecycle management systems
- designing reusable context resolution pipelines
- evaluating prompt-driven systems before and after release
- enforcing prompt injection boundaries between trusted instructions and untrusted data
- adding observability and telemetry to AI execution paths
- connecting prompt templates, tools, actions, and agent workflows

## Useful Starting Points

- [Enterprise Prompt Runtime Architecture](https://github.com/kumarkasimala/prompt-control-plane)
- [Prompt runtime design notes](https://github.com/kumarkasimala/prompt-control-plane/blob/main/docs/original-contribution.md)
- [Prompt runtime schema](https://github.com/kumarkasimala/prompt-control-plane/blob/main/schemas/prompt-runtime.schema.json)
- [CRM support prompt example](https://github.com/kumarkasimala/prompt-control-plane/blob/main/examples/crm-support/templates/case-summary.prompt.json)
- [Public CRM-style prompt templates](https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates)
- [Prompt template design notes](https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates/blob/main/docs/prompt-template-design.md)
- [Prompt injection boundary notes](https://github.com/kumarkasimala/salesforce-agentforce-prompt-templates/blob/main/docs/prompt-injection-boundaries.md)

## Reference Links

- [Salesforce Prompt Builder](https://www.salesforce.com/artificial-intelligence/prompt-builder/)
- [Agentforce announcement](https://www.salesforce.com/news/press-releases/2024/09/12/agentforce-announcement/)
- [Salesforce Engineering: modular, multi-model framework for enterprise AI agents](https://engineering.salesforce.com/engineering-agentforce-building-a-modular-multi-model-framework-for-enterprise-ai-agents/)
- [Salesforce Engineering: grounding enterprise AI with live retrieval and citations](https://engineering.salesforce.com/grounding-enterprise-ai-with-live-web-retrieval-and-verifiable-citations/)
