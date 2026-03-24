# Qubrid AI (qubrid-ai)
Qubrid AI is a cloud platform that provides GPU-accelerated infrastructure and AI services for enterprise developers. Their developer platform offers OpenAI-compatible inference endpoints, GPU compute provisioning, model fine-tuning, and retrieval-augmented generation capabilities, all running on NVIDIA GPU infrastructure.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/qubrid-ai/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Artificial Intelligence, Cloud Computing, GPU, Inference, Large Language Models, Machine Learning, NVIDIA, Serverless

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-03-24

## APIs

### Qubrid AI Inference API
The Qubrid AI Inference API provides a single, OpenAI-compatible endpoint for orchestrating 40+ open-source models running on NVIDIA GPU infrastructure. By abstracting hardware orchestration through TensorRT-LLM and Triton Inference Server, the API allows enterprise developers to run inference on models without managing underlying infrastructure. The API supports serverless endpoints as well as dedicated GPU clusters, enabling workloads to scale with zero code changes. Authentication uses bearer tokens, and the chat completions endpoint is compatible with standard OpenAI SDKs across Python, JavaScript, Go, and cURL.

**Human URL:** [https://docs.platform.qubrid.com](https://docs.platform.qubrid.com)


#### Tags:

 - Artificial Intelligence, Inference, Large Language Models, Machine Learning, NVIDIA, Serverless

#### Properties

- [Documentation](https://docs.platform.qubrid.com)
- [OpenAPI](openapi/qubrid-ai-inference-openapi.yml)
- [JSONSchema](json-schema/qubrid-ai-inference-schema.json)

### Qubrid AI Compute API
The Qubrid AI Compute API provides programmatic access to GPU cloud infrastructure including NVIDIA H100, H200, and B200 accelerators. Developers can provision and manage GPU instances for AI and machine learning workloads through API calls. The service supports on-demand compute for training, fine-tuning, and batch inference jobs, with usage-based billing and enterprise features such as team collaboration and usage tracking.

**Human URL:** [https://docs.platform.qubrid.com](https://docs.platform.qubrid.com)


#### Tags:

 - Cloud Computing, GPU, NVIDIA, Infrastructure

#### Properties

- [Documentation](https://docs.platform.qubrid.com)
- [OpenAPI](openapi/qubrid-ai-compute-openapi.yml)
- [JSONSchema](json-schema/qubrid-ai-compute-schema.json)

### Qubrid AI Fine-Tuning API
The Qubrid AI Fine-Tuning API enables developers and enterprises to customize open-source AI models using their own data. The API provides endpoints for uploading training datasets, configuring fine-tuning parameters, launching training jobs on GPU infrastructure, and retrieving fine-tuned model artifacts. Qubrid supports both no-code and API-driven fine-tuning workflows, making it accessible to teams with varying levels of ML expertise.

**Human URL:** [https://docs.platform.qubrid.com](https://docs.platform.qubrid.com)


#### Tags:

 - Artificial Intelligence, Fine-Tuning, Machine Learning, Model Training

#### Properties

- [Documentation](https://docs.platform.qubrid.com)
- [Documentation](https://docs.platform.qubrid.com/Fine%20Tuning)
- [OpenAPI](openapi/qubrid-ai-fine-tuning-openapi.yml)
- [JSONSchema](json-schema/qubrid-ai-fine-tuning-schema.json)

### Qubrid AI RAG API
The Qubrid AI RAG API provides retrieval-augmented generation capabilities that allow developers to upload departmental or enterprise data and query it using large language models. The API handles document ingestion, embedding generation, vector storage, and context-aware retrieval to ground model responses in organizational knowledge. This enables enterprises to build AI applications that answer questions based on proprietary data with near real-time performance.

**Human URL:** [https://docs.platform.qubrid.com](https://docs.platform.qubrid.com)


#### Tags:

 - Artificial Intelligence, RAG, Retrieval Augmented Generation, Search, Knowledge Management

#### Properties

- [Documentation](https://docs.platform.qubrid.com)
- [OpenAPI](openapi/qubrid-ai-rag-openapi.yml)
- [JSONSchema](json-schema/qubrid-ai-rag-schema.json)

## Common Properties

- [Portal](https://platform.qubrid.com)
- [Documentation](https://docs.platform.qubrid.com)
- [Website](https://qubrid.com)
- [Login](https://platform.qubrid.com/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
