# SambaNova (sambanova)

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

SambaNova Systems designs the SN-series Reconfigurable Dataflow Unit (RDU) AI chips and operates SambaCloud, a managed inference platform serving open-source models including the DeepSeek, Llama, Gemma, MiniMax, and gpt-oss families. The SambaCloud API is OpenAI-compatible and is consumed through first-party Python and TypeScript SDKs as well as the SambaNova AI Starter Kit collection on GitHub. SambaNova additionally ships SambaStack as an integrated chips-to-model on-prem appliance, SambaManaged managed services, and SambaRack rack-scale systems. The company emphasizes sovereign AI partnerships in Australia, Europe, and the UK and a recently announced heterogeneous inference collaboration with Intel.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sambanova/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sambanova/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- AI Inference
- Large Language Models
- Dataflow
- Hardware
- Cloud
- OpenAI Compatible
- Sovereign AI
- SDK
- Accelerator
- Open Source

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### SambaCloud API

The SambaCloud API exposes OpenAI-compatible chat completions over SambaNova's RDU-accelerated infrastructure. It serves multiple open model families including DeepSeek V3, Llama 3.3 and Llama 4, Gemma 3, MiniMax, and gpt-oss, with text and vision capabilities depending on the model. The API is consumed via the sambanova-python and sambanova-typescript SDKs and through OpenAI client libraries.

- **Human URL:** [https://docs.sambanova.ai](https://docs.sambanova.ai)
- **Base URL:** `https://api.sambanova.ai/v1`

#### Tags

- Inference
- LLM
- Chat Completions
- OpenAI Compatible
- Multimodal
- REST

#### Properties

- [Documentation](https://docs.sambanova.ai)
- [Getting Started](https://docs.sambanova.ai/cloud/docs/get-started)
- [Developer  Portal](https://cloud.sambanova.ai)
- [SDK](https://github.com/sambanova/sambanova-python)
- [SDK](https://github.com/sambanova/sambanova-typescript)
- [Starter Kits](https://github.com/sambanova/ai-starter-kit)
- [Postman Collection](collections/sambanova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sambanova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://sambanova.ai)
- [Documentation](https://docs.sambanova.ai)
- [Developer  Portal](https://cloud.sambanova.ai)
- [Community](https://community.sambanova.ai)
- [GitHub Organization](https://github.com/sambanova)
- [Starter Kits](https://github.com/sambanova/ai-starter-kit)
- [Hardware](https://sambanova.ai/products/sn50-rdu)
- [Blog](https://sambanova.ai/blog)
- [LinkedIn](https://www.linkedin.com/company/sambanova-systems)
- [Twitter](https://twitter.com/SambaNovaAI)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
