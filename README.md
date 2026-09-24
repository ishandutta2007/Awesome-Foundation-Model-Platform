# Awesome-Foundation-Model-Platform

# Top Foundation Model Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on LLM Inference, Fine-Tuning, Model Hosting, Serverless Endpoints & Open-Weight Serving*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Foundation Model Platforms**. These systems provide hosted inference, fine-tuning, dedicated endpoints, and infrastructure for running and serving large language and multimodal foundation models.

**Examples** include Together AI, Fireworks AI, Baseten, Predibase, Anyscale, Mosaic AI (Databricks), OctoAI, Lepton AI, Nebius AI, and GroqCloud (the category leaders).

**Open-source emphasis**: Foundation model serving has exceptional open-source engines. **vLLM**, **Text Generation Inference (TGI)**, **Ollama**, and related projects power a large share of self-hosted and hybrid deployments. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Together AI](https://www.together.ai/)**  
  Comprehensive platform for serverless and dedicated inference, fine-tuning, and GPU access across a wide catalog of open models.

- **[Fireworks AI](https://fireworks.ai/)**  
  High-performance inference platform optimized for production agentic workloads, function calling, structured outputs, and low-latency serving.

- **[Baseten](https://www.baseten.co/)**  
  Model deployment platform focused on custom model serving with autoscaling endpoints and developer-friendly infrastructure.

- **[Predibase](https://predibase.com/)**  
  Platform for fine-tuning and serving open models with LoRA and related efficient training techniques.

- **[Anyscale](https://www.anyscale.com/)**  
  Ray-powered platform for scaling AI and Python workloads, including foundation model training and serving.

- **[Mosaic AI (Databricks)](https://www.databricks.com/)**  
  Databricks’ foundation model and generative AI platform for training, fine-tuning, and governed serving inside the lakehouse.

- **[OctoAI](https://octo.ai/)**  
  Efficient model serving and fine-tuning platform oriented toward cost-effective inference of open models.

- **[Lepton AI](https://www.lepton.ai/)**  
  Developer-focused platform for deploying and scaling AI models with simple APIs and infrastructure abstractions.

- **[Nebius AI](https://nebius.com/)**  
  Cloud and AI infrastructure provider offering GPU capacity and model-serving capabilities.

- **[GroqCloud](https://groq.com/)**  
  Inference platform built on Groq LPU hardware, emphasizing extremely high token throughput and low latency.

## Open-Source GitHub Projects
- **[vLLM](https://github.com/vllm-project/vllm)**  
  Leading high-throughput, memory-efficient open-source LLM inference and serving engine (PagedAttention, continuous batching, OpenAI-compatible API).

- **[Text Generation Inference (TGI)](https://github.com/huggingface/text-generation-inference)**  
  Hugging Face’s open-source production inference server optimized for transformer models, with strong ecosystem integration.

- **[Ollama](https://github.com/ollama/ollama)**  
  Popular open-source tool for running and serving LLMs locally with simple commands and OpenAI-compatible API; ideal for development and single-node use.

- **[LocalAI](https://github.com/mudler/LocalAI)**  
  Open-source, self-hosted alternative to OpenAI-compatible APIs supporting multiple backends and local model execution.

- **[Hugging Face Transformers + Optimum](https://github.com/huggingface/transformers)**  
  Core open libraries for loading, fine-tuning, and optimizing foundation models across frameworks.

- **[Ray / Ray Serve](https://github.com/ray-project/ray)**  
  Open distributed computing framework widely used for scaling model serving and training (foundation of Anyscale).

- **[llama.cpp and GGUF ecosystem](https://github.com/ggerganov/llama.cpp)**  
  Highly efficient open C/C++ inference for quantized models on CPU and edge devices.

- **[OpenLLM / BentoML serving stacks](https://github.com/)**  
  Open platforms for packaging and serving LLMs as production APIs.

- **[Fine-tuning open frameworks (Axolotl, LLaMA-Factory, etc.)](https://github.com/)**  
  Community tools for efficient SFT, DPO, and LoRA fine-tuning of open foundation models.

- **[Kubernetes model-serving open operators (KServe, etc.)](https://github.com/)**  
  Open operators and Helm charts for deploying vLLM, TGI, and similar engines on Kubernetes.

### Additional Strong Open-Source Options
- Running **vLLM** or **TGI** for high-throughput multi-user production inference on your own GPUs.
- Using **Ollama** or **LocalAI** for local development, prototyping, and private single-node serving.
- Combining open engines with commercial platforms for burst capacity or specialized hardware (Groq, etc.).
- Accepting that global serverless catalogs, managed fine-tuning pipelines, compliance, and zero-ops endpoints still favor commercial platforms (Together, Fireworks, Baseten, Anyscale, Databricks Mosaic, GroqCloud, etc.).
- Focusing open-source efforts on performance, cost control, and data/model sovereignty.

**Frameworks for building custom systems**: Fine-tune with open frameworks → serve with vLLM or TGI on Kubernetes or bare GPUs → expose OpenAI-compatible APIs → scale with Ray or KServe → optionally front with a commercial gateway for multi-provider routing. Suitable for teams with GPU infrastructure and MLOps capacity. Many production systems use open engines self-hosted and commercial platforms for additional models or peak load.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Foundation model platforms process prompts and potentially sensitive data. Proper access control, logging, and compliance are required. This list is not security or operational advice.

---
**Made for AI engineers, platform teams, and organizations serving foundation models at scale.**
Let's keep model inference fast, efficient, and as open as practical.
