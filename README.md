# Kong AI Gateway

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Kong AI Gateway is the AI-native capability layer built on top of Kong Gateway and managed through Kong Konnect. It exposes a normalized, provider-agnostic LLM API across 16+ providers (OpenAI, Anthropic, Azure AI, Amazon Bedrock, Google Gemini, Vertex AI, Cohere, Hugging Face, Llama, Mistral, xAI, DashScope, Cerebras, Ollama, Databricks, DeepSeek, vLLM), and adds prompt firewalls, PII sanitization, semantic caching, automated RAG injection, token-level observability, per-agent cost allocation, MCP traffic governance, and Agent Gateway support for agent-to-agent (A2A) communication. It is profiled here as a standalone product surface; the parent provider profile lives at github.com/api-evangelist/kong.

**Areas:** AI Gateway · LLM · MCP · A2A · AI Governance · Konnect · Kong

## Kong AI Gateway on APIs.io

Everything profiled for Kong AI Gateway is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kong-ai-gateway/](https://apis.io/providers/kong-ai-gateway/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [Kong AI Gateway](https://apis.io/apis/kong-ai-gateway/kong-ai-gateway/) — Kong AI Gateway is the connectivity and governance layer for AI-native applications. Built on Kong Gateway, it provides a universal LLM API across 16+…
- [AI Proxy Plugin](https://apis.io/apis/kong-ai-gateway/ai-proxy-plugin/) — The AI Proxy plugin transforms and proxies requests to a configured AI provider and model, shielding client applications from provider-specific request and…
- [AI Proxy Advanced Plugin](https://apis.io/apis/kong-ai-gateway/ai-proxy-advanced-plugin/) — The AI Proxy Advanced plugin extends AI Proxy with load balancing, weighted distribution, and fallback across multiple providers and models simultaneously.
- [AI Rate Limiting Advanced Plugin](https://apis.io/apis/kong-ai-gateway/ai-rate-limiting-advanced-plugin/) — Token-aware rate limiting tailored for LLM traffic, with per-consumer and per-model budgets rather than just request counts.
- [AI Prompt Guard Plugin](https://apis.io/apis/kong-ai-gateway/ai-prompt-guard-plugin/) — Enforces allow- and deny-lists for prompts and text completions, blocking disallowed content before it reaches the model.
- [AI Semantic Prompt Guard Plugin](https://apis.io/apis/kong-ai-gateway/ai-semantic-prompt-guard-plugin/) — Topic-aware variant of AI Prompt Guard that classifies prompts by meaning and blocks restricted topics regardless of phrasing.
- [AI PII Sanitizer Plugin](https://apis.io/apis/kong-ai-gateway/ai-pii-sanitizer-plugin/) — Detects and redacts personally identifiable information from prompts and responses traversing the gateway.
- [AI Semantic Cache Plugin](https://apis.io/apis/kong-ai-gateway/ai-semantic-cache-plugin/) — Caches LLM responses by prompt similarity so semantically equivalent requests can be served from cache, reducing latency and provider spend.
- [AI RAG Injector Plugin](https://apis.io/apis/kong-ai-gateway/ai-rag-injector-plugin/) — Automates retrieval-augmented generation by injecting retrieved context into prompts at the gateway, so application code does not need to implement RAG…
- [AI Prompt Template Plugin](https://apis.io/apis/kong-ai-gateway/ai-prompt-template-plugin/) — Provides reusable, fill-in-the-blank prompt templates managed at the gateway layer.
- [AI Prompt Decorator Plugin](https://apis.io/apis/kong-ai-gateway/ai-prompt-decorator-plugin/) — Prepends or appends messages to chat history before requests reach the model.
- [AI Prompt Compressor Plugin](https://apis.io/apis/kong-ai-gateway/ai-prompt-compressor-plugin/) — Reduces prompt token count before forwarding to the provider to lower latency and cost.
- [AI Azure Content Safety Plugin](https://apis.io/apis/kong-ai-gateway/ai-azure-content-safety-plugin/) — Integrates Azure AI Content Safety for content moderation on prompts and responses.
- [AI AWS Guardrails Plugin](https://apis.io/apis/kong-ai-gateway/ai-aws-guardrails-plugin/) — Integrates Amazon Bedrock Guardrails for safety enforcement on traffic passing through Kong AI Gateway.
- [AI GCP Model Armor Plugin](https://apis.io/apis/kong-ai-gateway/ai-gcp-model-armor-plugin/) — Integrates Google Cloud Model Armor for safety inspection on prompts and responses.
- [AI Lakera Guard Plugin](https://apis.io/apis/kong-ai-gateway/ai-lakera-guard-plugin/) — Integrates Lakera Guard for prompt-injection and jailbreak detection.
- [AI Semantic Response Guard Plugin](https://apis.io/apis/kong-ai-gateway/ai-semantic-response-guard-plugin/) — Inspects model responses by meaning and blocks responses that violate configured semantic policies.
- [AI Custom Guardrail Plugin](https://apis.io/apis/kong-ai-gateway/ai-custom-guardrail-plugin/) — Lets operators define custom guardrail logic for prompts and responses without writing a full Kong plugin.
- [AI Request/Response Transformer Plugin](https://apis.io/apis/kong-ai-gateway/ai-request-response-transformer-plugin/) — Uses LLMs at the gateway to transform request and response payloads (for example, reshaping JSON or translating fields) on the data path.
- [Kong Agent Gateway](https://apis.io/apis/kong-ai-gateway/kong-agent-gateway/) — Kong Agent Gateway is a capability of Kong AI Gateway (GA April 2026 with AI Gateway 3.14) that governs agent-to-agent (A2A) communication. It enforces…
- [Kong MCP Registry](https://apis.io/apis/kong-ai-gateway/kong-mcp-registry/) — Kong MCP Registry (launched February 2026) is an enterprise directory inside Kong Konnect for registering, discovering, and governing MCP servers and…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Kong Konnect MCP Server](https://apis.io/servers/kong-ai-gateway/kong-konnect-mcp-server/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Kong Ai Gateway Domain Security](https://apis.io/security/kong-ai-gateway/kong-ai-gateway-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kong Ai Gateway Plans Pricing](https://apis.io/plans/kong-ai-gateway/kong-ai-gateway-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kong Ai Gateway Rate Limits](https://apis.io/rate-limits/kong-ai-gateway/kong-ai-gateway-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Kong Ai Gateway Finops](https://apis.io/finops/kong-ai-gateway/kong-ai-gateway-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://developer.konghq.com/ai-gateway/)
- [Getting started](https://developer.konghq.com/ai-gateway/get-started/)
- [API reference](https://developer.konghq.com/ai-gateway/ai-providers/)
- [Pricing](https://konghq.com/pricing)
- [Support](https://discuss.konghq.com/)
- [Changelog](https://developer.konghq.com/gateway/changelog/)
- [Blog](https://konghq.com/blog)
- [GitHub](https://github.com/Kong)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kong AI Gateway: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kong-ai-gateway/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
