<!--lint disable awesome-heading awesome-github-badge-url awesome-git-repo-age-->

<div align="center">

<!-- title -->

# Awesome LLMOps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- image -->

<img src="media/logo.svg" alt="Awesome LLMOps" width="200">

<!-- subtitle -->

A curated list of awesome tools, platforms, and resources for deploying, monitoring, and managing large language models in production.

<!-- description -->

LLMOps encompasses the practices and tools needed to operationalize LLMs, covering the full lifecycle from fine-tuning and serving to evaluation, observability, and cost management.

</div>

## Contents

- [Model Serving and Inference](#model-serving-and-inference)
- [Fine-Tuning](#fine-tuning)
- [Evaluation and Benchmarking](#evaluation-and-benchmarking)
- [Observability and Monitoring](#observability-and-monitoring)
- [Prompt Management](#prompt-management)
- [Guardrails and Safety](#guardrails-and-safety)
- [Gateway and Routing](#gateway-and-routing)
- [Caching](#caching)
- [Platforms](#platforms)

## Model Serving and Inference

- [llama.cpp](https://github.com/ggerganov/llama.cpp) - Pure C/C++ LLM inference with broad quantization support, runs on CPU and edge devices.
- [LMDeploy](https://github.com/InternLM/lmdeploy) - Toolkit for compressing, deploying, and serving LLMs with TurboMind engine.
- [LoRAX](https://github.com/predibase/lorax) - Multi-LoRA inference server that scales to thousands of fine-tuned LLMs on shared GPU.
- [MLC LLM](https://github.com/mlc-ai/mlc-llm) - Universal LLM deployment engine using ML compilation for any hardware backend.
- [Ollama](https://github.com/ollama/ollama) - Local LLM runner wrapping llama.cpp with a clean CLI and REST API for easy model management.
- [OpenLLM](https://github.com/bentoml/OpenLLM) - Run any open-source LLM as an OpenAI-compatible API endpoint via BentoML.
- [SGLang](https://github.com/sgl-project/sglang) - Fast serving framework optimized for structured generation workflows and high-performance inference.
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) - NVIDIA's optimized inference backend for maximum GPU throughput via Triton.
- [Text Generation Inference](https://github.com/huggingface/text-generation-inference) - Hugging Face's production-grade serving framework with token streaming and distributed inference.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput inference engine using PagedAttention for memory-efficient KV cache management.

## Fine-Tuning

- [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) - Production-ready fine-tuning framework supporting LoRA, QLoRA, SFT, RLHF, and GRPO.
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) - Unified fine-tuning framework with web UI supporting 100+ LLMs and multiple training methods.
- [Ludwig](https://github.com/ludwig-ai/ludwig) - Declarative deep learning framework with built-in LLM fine-tuning via simple YAML configs.
- [PEFT](https://github.com/huggingface/peft) - Parameter-Efficient Fine-Tuning library implementing LoRA, QLoRA, Prefix Tuning, and more.
- [torchtune](https://github.com/pytorch/torchtune) - PyTorch-native library for LLM fine-tuning with clean, abstraction-free design.
- [TRL](https://github.com/huggingface/trl) - Hugging Face's library for RLHF, PPO, DPO, and alignment training.
- [Unsloth](https://github.com/unslothai/unsloth) - 2-5x faster fine-tuning with 80% less memory using optimized kernels.
- [xTuring](https://github.com/stochasticai/xTuring) - Fast and efficient fine-tuning of LLMs with a simple interface and multiple method support.

## Evaluation and Benchmarking

- [DeepEval](https://github.com/confident-ai/deepeval) - Pytest-native LLM evaluation framework with 30+ metrics including G-Eval and RAG assessment.
- [EvalScope](https://github.com/modelscope/evalscope) - Streamlined framework integrating OpenCompass, VLMEvalKit, and RAGEval backends.
- [Giskard](https://github.com/Giskard-AI/giskard) - Quality testing framework for ML/LLM models covering bias, robustness, and hallucination.
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) - The standard evaluation framework powering Hugging Face's Open LLM Leaderboard with 60+ benchmarks.
- [OpenCompass](https://github.com/open-compass/opencompass) - One-stop evaluation platform with 50+ datasets and distributed evaluation for billion-scale models.
- [Opik](https://github.com/comet-ml/opik) - Open-source LLM evaluation and observability platform with automated metrics and dashboards.
- [promptfoo](https://github.com/promptfoo/promptfoo) - CLI-first prompt testing, red-teaming, and evaluation with CI/CD integration.
- [RAGAS](https://github.com/explodinggradients/ragas) - Evaluation framework specifically designed for RAG pipelines with faithfulness and relevancy metrics.

## Observability and Monitoring

- [Arize Phoenix](https://github.com/Arize-AI/phoenix) - OpenTelemetry-native observability for LLMs with notebook-friendly tracing and RAG analysis.
- [Helicone](https://github.com/Helicone/helicone) - One-line proxy-based integration for request logging, cost tracking, and caching.
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM observability with tracing, prompt management, evaluation, and cost tracking.
- [LangSmith](https://smith.langchain.com/) - LangChain's observability platform with deep debugging for chains and agents.
- [LangWatch](https://github.com/langwatch/langwatch) - OpenTelemetry-native LLMOps platform combining observability, evaluations, and CI/CD test suites.
- [Lunary](https://github.com/lunary-ai/lunary) - Production monitoring for LLM apps with analytics, logging, and prompt management.
- [OpenLLMetry](https://github.com/traceloop/openllmetry) - OpenTelemetry-based instrumentation for LLM apps with per-user cost attribution.
- [Weave](https://github.com/wandb/weave) - Weights & Biases LLM-focused tracing and evaluation toolkit.

## Prompt Management

- [Agenta](https://github.com/Agenta-AI/agenta) - Open-source LLMOps platform with prompt playground, versioning, evaluation, and deployment.
- [Braintrust](https://www.braintrust.dev/) - AI gateway plus prompt registry with version comparison, branching, and rollback.
- [Humanloop](https://humanloop.com/) - Prompt management platform with evaluation, versioning, and fine-tuning data collection.
- [Latitude](https://github.com/latitude-dev/latitude-llm) - Open-source prompt engineering platform with versioning, evaluations, and collaborative workflows.
- [Pezzo](https://github.com/pezzolabs/pezzo) - Developer-first open-source LLMOps for prompt design, version management, and instant delivery.
- [PromptLayer](https://promptlayer.com/) - Centralized prompt registry with versioning, A/B testing, and analytics across LLM providers.

## Guardrails and Safety

- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Pydantic-style validation for LLM outputs with a hub of pre-built validators.
- [Lakera Guard](https://www.lakera.ai/) - Commercial API for prompt injection defense with sub-50ms response times.
- [LLaMA Guard](https://github.com/meta-llama/PurpleLlama) - Meta's safety classifier model for input/output content moderation in LLM apps.
- [LLM Guard](https://github.com/protectai/llm-guard) - Comprehensive security toolkit with 35 built-in scanners for prompt injection, PII detection, and toxicity.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - NVIDIA's toolkit for programmable guardrails with content moderation, fact-checking, and jailbreak detection.
- [Rebuff](https://github.com/protectai/rebuff) - Prompt injection detection using heuristics, embeddings, and pattern matching.
- [Vigil](https://github.com/deadbits/vigil-llm) - LLM security scanner detecting prompt injections, jailbreaks, and data exfiltration attempts.

## Gateway and Routing

- [Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/) - Edge-based AI gateway with caching, rate limiting, and analytics at Cloudflare's global network.
- [Cortex.cpp](https://github.com/janhq/cortex.cpp) - Local AI API platform acting as a gateway for self-hosted model serving.
- [Kong AI Gateway](https://github.com/Kong/kong) - Enterprise API gateway extended with AI plugins for routing, rate limiting, and load balancing.
- [LiteLLM](https://github.com/BerriAI/litellm) - OpenAI-compatible proxy for 100+ LLM providers with cost tracking, load balancing, and guardrails.
- [Martian](https://github.com/withmartian/martian) - Intelligent model router that automatically selects the best LLM for each request.
- [Portkey AI Gateway](https://github.com/Portkey-AI/gateway) - Production AI gateway with routing, caching, observability, and governance for 1600+ models.

## Caching

- [GPTCache](https://github.com/zilliztech/GPTCache) - Semantic caching for LLMs that reduces API calls by matching similar queries.
- [Momento](https://www.gomomento.com/) - Serverless caching service with built-in LLM response caching and TTL management.
- [Redis Semantic Cache](https://github.com/redis/redis-py) - Redis-based semantic caching using vector similarity for LLM response deduplication.

## Platforms

- [BentoML](https://github.com/bentoml/BentoML) - Unified model serving platform for building, shipping, and scaling AI applications.
- [Dify](https://github.com/langgenius/dify) - Open-source platform combining prompt engineering, RAG, agents, and observability with visual workflows.
- [Haystack](https://github.com/deepset-ai/haystack) - End-to-end NLP/LLM framework for building production RAG pipelines and AI applications.
- [MLflow](https://github.com/mlflow/mlflow) - Open-source MLOps platform with LLM tracking, evaluation, and model registry by Databricks.
- [TrueFoundry](https://www.truefoundry.com/) - Kubernetes-native platform covering training, serving, observability, guardrails, and CI/CD.
- [Weights & Biases](https://wandb.ai/) - Experiment tracking, evaluation, and deployment platform extended for LLM workflows.
- [ZenML](https://github.com/zenml-io/zenml) - Open-source MLOps framework for reproducible LLM pipelines across any infrastructure.

## Footnotes

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
