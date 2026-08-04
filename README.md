# Qubrid AI (qubrid-ai)

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

Qubrid AI is a cloud platform that provides GPU-accelerated infrastructure and AI services for enterprise developers. Their developer platform offers OpenAI-compatible inference endpoints, GPU compute provisioning, model fine-tuning, and retrieval-augmented generation capabilities, all running on NVIDIA GPU infrastructure.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Artificial Intelligence
- Cloud Computing
- GPU
- Inference
- Large Language Models
- Machine Learning
- NVIDIA
- Serverless

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### Qubrid AI Inference API

The Qubrid AI Inference API provides a single, OpenAI-compatible endpoint for orchestrating 40+ open-source models running on NVIDIA GPU infrastructure. By abstracting hardware orchestration through TensorRT-LLM and Triton Inference Server, the API allows enterprise developers to run inference on models without managing underlying infrastructure.

- **Human URL:** [https://docs.platform.qubrid.com](https://docs.platform.qubrid.com)
- **Base URL:** `https://platform.qubrid.com/api/v1`

#### Tags

- Artificial Intelligence
- Inference
- Large Language Models
- Machine Learning
- NVIDIA
- Serverless

#### Properties

- [Documentation](https://docs.platform.qubrid.com)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-inference-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-schema/qubrid-ai-inference-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/qubrid-ai-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-fine-tuning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-fine-tuning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-inference.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-inference.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-rag.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-rag.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qubrid AI Compute API

The Qubrid AI Compute API provides programmatic access to GPU cloud infrastructure including NVIDIA H100, H200, and B200 accelerators. Developers can provision and manage GPU instances for AI and machine learning workloads through API calls.

- **Human URL:** [https://docs.platform.qubrid.com](https://docs.platform.qubrid.com)
- **Base URL:** `https://platform.qubrid.com/api/v1`

#### Tags

- Cloud Computing
- GPU
- NVIDIA
- Infrastructure

#### Properties

- [Documentation](https://docs.platform.qubrid.com)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-compute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-schema/qubrid-ai-compute-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/qubrid-ai-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-fine-tuning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-fine-tuning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-inference.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-inference.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-rag.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-rag.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qubrid AI Fine-Tuning API

The Qubrid AI Fine-Tuning API enables developers and enterprises to customize open-source AI models using their own data. The API provides endpoints for uploading training datasets, configuring fine-tuning parameters, launching training jobs on GPU infrastructure, and retrieving fine-tuned model artifacts.

- **Human URL:** [https://docs.platform.qubrid.com](https://docs.platform.qubrid.com)
- **Base URL:** `https://platform.qubrid.com/api/v1`

#### Tags

- Artificial Intelligence
- Fine-Tuning
- Machine Learning
- Model Training

#### Properties

- [Documentation](https://docs.platform.qubrid.com)
- [Documentation](https://docs.platform.qubrid.com/Fine%20Tuning)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-fine-tuning-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-schema/qubrid-ai-fine-tuning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/qubrid-ai-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-fine-tuning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-fine-tuning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-inference.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-inference.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-rag.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-rag.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qubrid AI RAG API

The Qubrid AI RAG API provides retrieval-augmented generation capabilities that allow developers to upload departmental or enterprise data and query it using large language models. The API handles document ingestion, embedding generation, vector storage, and context-aware retrieval to ground model responses in organizational knowledge.

- **Human URL:** [https://docs.platform.qubrid.com](https://docs.platform.qubrid.com)
- **Base URL:** `https://platform.qubrid.com/api/v1`

#### Tags

- Artificial Intelligence
- RAG
- Retrieval Augmented Generation
- Search
- Knowledge Management

#### Properties

- [Documentation](https://docs.platform.qubrid.com)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/openapi/qubrid-ai-rag-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-schema/qubrid-ai-rag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/qubrid-ai-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-fine-tuning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-fine-tuning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-inference.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-inference.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/qubrid-ai-rag.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qubrid-ai-rag.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/QubridAI-Inc)
- [LinkedIn](https://www.linkedin.com/company/qubrid)
- [Portal](https://platform.qubrid.com)
- [Documentation](https://docs.platform.qubrid.com)
- [Website](https://qubrid.com)
- [Login](https://platform.qubrid.com/login)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/json-ld/qubrid-ai-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://qubrid.com/partners)
- [L L Ms Txt](https://docs.platform.qubrid.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
