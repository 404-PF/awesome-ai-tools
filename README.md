<!--lint disable awesome-git-repo-age awesome-github-->

<div align="center">

# 🤖 Awesome AI Tools

A curated list of remarkable AI tools, platforms, and resources for developers, creators, and businesses.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

</div>

[contributing]: CONTRIBUTING.md
[huggingface]: https://huggingface.co/
[huggingface-meta-llama]: https://huggingface.co/meta-llama
[huggingface-mistralai]: https://huggingface.co/mistralai
[huggingface-qwen]: https://huggingface.co/Qwen
[huggingface-deepseek-ai]: https://huggingface.co/deepseek-ai
[huggingface-microsoft]: https://huggingface.co/microsoft
[huggingface-google]: https://huggingface.co/google
[github-copilot]: https://github.com/features/copilot
[github-copilot-workspace]: https://github.com/features/copilot#workspace
[perplexity]: https://www.perplexity.ai/
[stability]: https://stability.ai/

---

<!--lint ignore no-undefined-references-->
> [!NOTE]
> **Contributions welcome!** Read the [contribution guidelines][contributing] first.

---

## Contents

- [🧠 LLM APIs & Providers](#-llm-apis--providers)
- [🤗 Open-Source LLMs](#-open-source-llms)
- [💻 AI Code Assistants](#-ai-code-assistants)
- [🤖 AI Agents & Orchestration](#-ai-agents--orchestration)
- [📚 RAG & Vector Databases](#-rag--vector-databases)
- [🎨 AI Image Generation](#-ai-image-generation)
- [🎬 AI Video Generation](#-ai-video-generation)
- [🎙️ AI Audio & Voice](#️-ai-audio--voice)
- [✍️ AI Writing & Content](#️-ai-writing--content)
- [💬 AI Chatbots & Assistants](#-ai-chatbots--assistants)
- [🏠 Local & Self-Hosted AI](#-local--self-hosted-ai)
- [📊 AI Data & Analytics](#-ai-data--analytics)
- [⚙️ AI for DevOps & MLOps](#️-ai-for-devops--mlops)
- [🛠️ AI Frameworks & Libraries](#️-ai-frameworks--libraries)
- [📚 AI Learning & Education](#-ai-learning--education)
- [🔍 AI Monitoring & Observability](#-ai-monitoring--observability)
- [🛡️ AI Safety & Ethics](#️-ai-safety--ethics)
- [🔮 Miscellaneous](#-miscellaneous)

---

## 🧠 LLM APIs & Providers

*Commercial API providers for large language models.*

| Name | Description | License |
|------|-------------|---------|
| [OpenAI](https://openai.com/api/) | GPT-4o, GPT-4.5, o1, o3 series. Token-based pricing | Proprietary |
| [Anthropic](https://console.anthropic.com/) | Claude 3.5 Sonnet, Claude 3.5 Haiku, Opus. Token-based | Proprietary |
| [Google Gemini](https://ai.google.dev/) | Gemini 2.0, Gemini Ultra. Token-based | Proprietary |
| [Mistral AI](https://mistral.ai/) | Mistral Large, Medium, Small. Token-based | Apache 2.0 (open models) |
| [DeepSeek](https://platform.deepseek.com/) | DeepSeek-V3, DeepSeek-R1. Token-based | MIT (open models) |
| [xAI](https://x.ai/) | Grok-2, Grok-3. Token-based | Proprietary |
| [Groq](https://groq.com/) | Ultra-fast LPU inference. Token-based | Proprietary |
| [Together AI](https://together.ai/) | Open-source model hosting. Token-based | Proprietary |
| [Replicate](https://replicate.com/) | Run any model via API. Per-second pricing | Proprietary |
| [Fireworks AI](https://fireworks.ai/) | Fast inference platform. Token-based | Proprietary |
| [perplexity] | AI search + API. Token-based | Proprietary |
| [Cohere](https://cohere.com/) | Enterprise NLP APIs. Token-based | Proprietary |
| [AWS Bedrock](https://aws.amazon.com/bedrock/) | Multi-model marketplace. Token-based | Proprietary |
| [Azure AI](https://azure.microsoft.com/ai) | OpenAI + open models. Token-based | Proprietary |
| [Cloudflare Workers AI](https://workers.cloudflare.com/) | Edge AI inference. Token-based | Proprietary |
| [Hugging Face][huggingface] | Open model hub + inference. Free/Paid | Varies by model |

---

## 🤗 Open-Source LLMs

*Language models with open weights you can self-host.*

| Name | Parameters | License |
|------|-----------|---------|
| [Llama 3.1][huggingface-meta-llama] | 8B, 70B, 405B | Llama 3.1 Community |
| [Llama 3.2 Vision][huggingface-meta-llama] | 11B, 90B | Llama 3.2 Community License |
| [Mistral Large 2][huggingface-mistralai] | 123B | Apache 2.0 |
| [Mixtral 8x22B][huggingface-mistralai] | 141B (39B active) | Apache 2.0 |
| [Qwen 2.5][huggingface-qwen] | 0.5B - 72B | Apache 2.0 |
| [Qwen 2.5 Coder][huggingface-qwen] | 7B, 32B | Apache 2.0 |
| [DeepSeek-V3][huggingface-deepseek-ai] | 671B (37B active) | MIT |
| [DeepSeek-R1][huggingface-deepseek-ai] | 1.5B - 671B | MIT |
| [Phi-3.5][huggingface-microsoft] | 3.8B, 14B | MIT |
| [Phi-4][huggingface-microsoft] | 14B | MIT |
| [Gemma 2][huggingface-google] | 2B, 9B, 27B | Gemma License |
| [Gemma 3][huggingface-google] | 1B - 27B | Gemma License |
| [Command R+](https://huggingface.co/CohereForAI) | 104B | CC-BY-NC |
| [Yi-1.5](https://huggingface.co/01-ai) | 6B - 34B | Apache 2.0 |
| [InternLM 2.5](https://huggingface.co/internlm) | 7B, 20B | Apache 2.0 |
| [OLMo 2](https://huggingface.co/allenai) | 1B, 7B | Apache 2.0 |
| [SmolLM2](https://huggingface.co/HuggingFaceTB) | 135M - 1.7B | Apache 2.0 |
| [Falcon 3](https://huggingface.co/tiiuae) | 1B - 40B | Apache 2.0 |
| [Arctic](https://huggingface.co/Snowflake) | 480B (17B active) | Apache 2.0 |
| [DBRX](https://huggingface.co/databricks) | 132B (32B active) | DBRX License |

---

## 💻 AI Code Assistants

*Tools that help you write, understand, and debug code.*

| Name | Description | License |
|------|-------------|---------|
| [GitHub Copilot][github-copilot] | AI pair programmer (VS Code, JetBrains, CLI) | Proprietary |
| [Cursor](https://cursor.sh/) | AI-first code editor (Mac/Win/Linux) | Proprietary |
| [Windsurf](https://windsurf.com/) | AI-native IDE with Cascade | Proprietary |
| [Continue](https://continue.dev/) | Open-source AI code assistant (VS Code, JetBrains) | Apache 2.0 |
| [Cline](https://github.com/cline/cline) | Autonomous coding agent (VS Code) | Apache 2.0 |
| [Aider](https://aider.chat/) | AI pair programming in terminal | Apache 2.0 |
| [Void](https://voideditor.com/) | Open-source Cursor alternative | AGPL-3.0 |
| [Roo Code](https://roocode.com/) | AI coding agent (VS Code) | Apache 2.0 |
| [Codeium](https://codeium.com/) | Free AI code completion (Multi-IDE) | Proprietary |
| [Tabnine](https://www.tabnine.com/) | Code completion & chat (Multi-IDE) | Proprietary |
| [Cody](https://sourcegraph.com/cody) | AI code assistant by Sourcegraph (VS Code, JetBrains) | Proprietary |
| [Amazon Q](https://aws.amazon.com/q/) | AWS AI assistant (CLI, IDE) | Proprietary |
| [JetBrains AI](https://www.jetbrains.com/ai/) | Native AI in IntelliJ | Proprietary |
| [PearAI](https://pearai.com/) | AI code editor | Proprietary |
| [Zed](https://zed.dev/) | AI-assisted editor | GPL-3.0 / Apache 2.0 |

---

## 🤖 AI Agents & Orchestration

*Frameworks for building autonomous AI agents.*

| Name | Description | License |
|------|-------------|---------|
| [Activepieces](https://activepieces.com/) | Open-source Zapier alternative | MIT |
| [Anthropic Claude SDK](https://docs.anthropic.com/) | Tool use & computer use (Python, TS) | Proprietary |
| [AutoGen](https://github.com/microsoft/autogen) | Multi-agent conversations | MIT |
| [CrewAI](https://www.crewai.com/) | Role-based agent orchestration | MIT |
| [Dify](https://dify.ai/) | Visual agent builder (Python/JS) | Apache 2.0 |
| [Flowise](https://flowiseai.com/) | Drag-and-drop LLM flows | Apache 2.0 |
| [Haystack](https://haystack.deepset.ai/) | RAG & agent pipelines | Apache 2.0 |
| [LangChain](https://github.com/langchain-ai/langchain) | LLM application framework (Python, JS) | MIT |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Agent state machines (Python, JS) | MIT |
| [LlamaIndex](https://www.llamaindex.ai/) | Data framework for LLMs | MIT |
| [n8n](https://n8n.io/) | Workflow automation + AI | Sustainable Use License |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Lightweight multi-agent framework (Python) | MIT |
| [Phidata](https://www.phidata.com/) | Build AI assistants | MIT |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | Microsoft AI orchestration (C#, Python) | MIT |

---

## 📚 RAG & Vector Databases

*Retrieval-Augmented Generation and vector storage.*

| Name | Description | License |
|------|-------------|---------|
| [Chroma](https://www.trychroma.com/) | Embedding database | Apache 2.0 |
| [Qdrant](https://qdrant.tech/) | High-performance vector DB | Apache 2.0 |
| [Weaviate](https://weaviate.io/) | AI-native vector database | BSD-3-Clause |
| [Milvus](https://milvus.io/) | Scalable vector database | Apache 2.0 |
| [Pinecone](https://www.pinecone.io/) | Managed vector database | Proprietary |
| [LanceDB](https://lancedb.com/) | Serverless vector database | Apache 2.0 |
| [Pgvector](https://github.com/pgvector/pgvector) | PostgreSQL vector extension | PostgreSQL License |
| [TurboPuffer](https://turbopuffer.com/) | Fast vector search | Proprietary |
| [Vespa](https://vespa.ai/) | Search & recommendation engine | Apache 2.0 |
| [OpenSearch](https://opensearch.org/) | Vector search & analytics | Apache 2.0 |
| [Zilliz](https://zilliz.com/) | Managed Milvus | Proprietary |
| [Vectara](https://vectara.com/) | RAG-as-a-service | Proprietary |
| [Superlinked](https://www.superlinked.com/) | Vector compute engine | Apache 2.0 |

---

## 🎨 AI Image Generation

*Create images, illustrations, and art with AI.*

| Name | Description | License |
|------|-------------|---------|
| [Stable Diffusion 3.5][stability] | Open-source image generation (self-host/API) | Stability AI Community |
| [FLUX](https://blackforestlabs.ai/) | High-quality open model (self-host) | Apache 2.0 (dev) |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | Node-based SD workflow (self-host) | GPL-3.0 |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Simplified SD interface (self-host) | GPL-3.0 |
| [Automatic1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | Popular SD web UI (self-host) | AGPL-3.0 |
| [Midjourney](https://www.midjourney.com/) | High-quality AI art (Discord/Web) | Proprietary |
| [DALL·E 3](https://openai.com/dall-e-3) | OpenAI image generator (API) | Proprietary |
| [Leonardo.ai](https://leonardo.ai/) | AI creative suite (Web) | Proprietary |
| [Ideogram](https://ideogram.ai/) | Text-in-image specialist (Web) | Proprietary |
| [Playground](https://www.playground.com/) | AI image editor (Web) | Proprietary |
| [Magnific](https://magnific.ai/) | AI upscaler & enhancer (Web) | Proprietary |
| [NightCafe](https://creator.nightcafe.studio/) | AI art generator (Web) | Proprietary |

---

## 🎬 AI Video Generation

*Generate and edit videos with AI.*

| Name | Description | License |
|------|-------------|---------|
| [Runway](https://runwayml.com/) | Gen-3 Alpha, video editing (Web) | Proprietary |
| [Kling](https://klingai.com/) | High-quality video gen (Web) | Proprietary |
| [Pika](https://pika.art/) | Text-to-video, effects (Web) | Proprietary |
| [Sora](https://openai.com/sora) | OpenAI video model (Web) | Proprietary |
| [Luma Dream Machine](https://lumalabs.ai/) | Fast video generation (Web) | Proprietary |
| [Stable Video][stability] | Open-source video diffusion (self-host) | Stability Community |
| [CogVideo](https://github.com/THUDM/CogVideo) | Open-source text-to-video (self-host) | Apache 2.0 |
| [Mochi](https://github.com/genmoai/mochi) | Open video generation (self-host) | Apache 2.0 |
| [HeyGen](https://www.heygen.com/) | AI avatar videos (Web) | Proprietary |
| [Synthesia](https://www.synthesia.io/) | AI video presenters (Web) | Proprietary |
| [Descript](https://www.descript.com/) | AI video editing (Desktop) | Proprietary |
| [CapCut](https://www.capcut.com/) | AI video editor (Web/Desktop) | Proprietary |

---

## 🎙️ AI Audio & Voice

*Text-to-speech, speech-to-text, music generation, and voice cloning.*

| Name | Description | License |
|------|-------------|---------|
| [Whisper](https://github.com/openai/whisper) | Speech recognition | MIT |
| [Faster-Whisper](https://github.com/SYSTRAN/faster-whisper) | Optimized Whisper | MIT |
| [WhisperX](https://github.com/m-bain/whisperX) | Whisper + alignment | BSD-2-Clause |
| [Bark](https://github.com/suno-ai/bark) | Text-to-audio | MIT |
| [XTTS](https://github.com/coqui-ai/TTS) | Voice cloning TTS | MPL-2.0 |
| [Fish Speech](https://github.com/fishaudio/fish-speech) | Multilingual TTS | Apache 2.0 |
| [Parler TTS](https://github.com/huggingface/parler-tts) | Descriptive TTS | Apache 2.0 |
| [ElevenLabs](https://elevenlabs.io/) | AI voice synthesis | Proprietary |
| [Play.ht](https://play.ht/) | Text-to-speech | Proprietary |
| [Suno](https://suno.com/) | AI music generation | Proprietary |
| [Udio](https://www.udio.com/) | AI music creation | Proprietary |
| [MusicGen](https://github.com/facebookresearch/audiocraft) | Meta music generation | MIT |
| [RVC](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI) | Voice conversion | MIT |

---

## ✍️ AI Writing & Content

*Tools for writing, editing, and content creation.*

| Name | Description | License |
|------|-------------|---------|
| [Jasper](https://www.jasper.ai/) | Marketing content AI (Web) | Proprietary |
| [Copy.ai](https://www.copy.ai/) | Sales & marketing copy (Web) | Proprietary |
| [Notion AI](https://www.notion.so/product/ai) | AI within Notion | Proprietary |
| [Grammarly](https://www.grammarly.com/) | AI writing assistant (Multi-platform) | Proprietary |
| [Hemingway](https://hemingwayapp.com/) | Readability editor (Web) | Freemium |
| [Sudowrite](https://www.sudowrite.com/) | AI for fiction writers (Web) | Proprietary |
| [NovelAI](https://novelai.net/) | AI story generation (Web) | Proprietary |
| [Writesonic](https://writesonic.com/) | Article & ad copywriter (Web) | Proprietary |
| [Surfer SEO](https://surferseo.com/) | AI content optimization (Web) | Proprietary |
| [Wordtune](https://www.wordtune.com/) | AI rewriting tool (Web) | Proprietary |

---

## 💬 AI Chatbots & Assistants

*Conversational AI interfaces and platforms.*

| Name | Description | License |
|------|-------------|---------|
| [ChatGPT](https://chat.openai.com/) | OpenAI's chatbot (Web/App) | Proprietary |
| [Claude](https://claude.ai/) | Anthropic's assistant (Web/App) | Proprietary |
| [Gemini](https://gemini.google.com/) | Google AI assistant (Web/App) | Proprietary |
| [perplexity] | AI search engine (Web/App) | Proprietary |
| [Poe](https://poe.com/) | Multi-model chatbot (Web/App) | Proprietary |
| [Open WebUI](https://github.com/open-webui/open-webui) | Self-hosted ChatGPT UI | BSD-3-Clause |
| [LibreChat](https://github.com/danny-avila/LibreChat) | Open-source chat UI (self-host) | MIT |
| [LobeChat](https://lobehub.com/) | Extensible chat framework (self-host) | Apache 2.0 |
| [Jan](https://jan.ai/) | Offline AI assistant (Desktop) | AGPL-3.0 |
| [Chatbox](https://chatboxai.app/) | Desktop AI client | MIT |

---

## 🏠 Local & Self-Hosted AI

*Run AI models on your own hardware, completely offline.*

| Name | Description | License |
|------|-------------|---------|
| [Ollama](https://ollama.com/) | Run LLMs locally | MIT |
| [LM Studio](https://lmstudio.ai/) | Desktop LLM interface | Proprietary |
| [LocalAI](https://github.com/mudler/LocalAI) | OpenAI-compatible local API | MIT |
| [llama.cpp](https://github.com/ggerganov/llama.cpp) | LLM inference in C/C++ | MIT |
| [vLLM](https://github.com/vllm-project/vllm) | High-throughput LLM serving | Apache 2.0 |
| [text-generation-webui](https://github.com/oobabooga/text-generation-webui) | Gradio UI for LLMs | AGPL-3.0 |
| [KoboldCpp](https://github.com/LostRuins/koboldcpp) | GGUF inference engine | AGPL-3.0 |
| [GPT4All](https://www.nomic.ai/gpt4all) | Desktop LLM chatbot | GPL-3.0 |
| [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) | Natural language coding | Apache 2.0 |
| [Anything LLM](https://github.com/Mintplex-Labs/anything-llm) | All-in-one AI desktop | MIT |

---

## 📊 AI Data & Analytics

*AI-powered data analysis and business intelligence.*

| Name | Description | License |
|------|-------------|---------|
| [Hex](https://hex.tech/) | AI-powered analytics | Proprietary |
| [Julius AI](https://julius.ai/) | Data analysis assistant | Proprietary |
| [Rows](https://rows.com/) | AI spreadsheet | Freemium |
| [PandasAI](https://github.com/sinaptik-ai/pandas-ai) | Chat with your data | GPL-3.0 |
| [Vanna](https://vanna.ai/) | Text-to-SQL | MIT |
| [Dataherald](https://github.com/Dataherald/dataherald) | Text-to-SQL | Apache 2.0 |

---

## ⚙️ AI for DevOps & MLOps

*AI-powered DevOps and machine learning operations.*

| Name | Description | License |
|------|-------------|---------|
| [GitHub Copilot Workspace][github-copilot-workspace] | AI-native dev environment | Proprietary |
| [MLflow](https://mlflow.org/) | ML lifecycle management | Apache 2.0 |
| [Ray](https://www.ray.io/) | Distributed AI computing | Apache 2.0 |
| [Modal](https://modal.com/) | Serverless AI infrastructure | Proprietary |
| [Baseten](https://www.baseten.co/) | Model deployment platform | Proprietary |

---

## 🛠️ AI Frameworks & Libraries

*Core libraries for building AI applications.*

| Name | Description | License |
|------|-------------|---------|
| [PyTorch](https://pytorch.org/) | Deep learning framework | BSD-3-Clause |
| [TensorFlow](https://www.tensorflow.org/) | ML framework by Google | Apache 2.0 |
| [JAX](https://github.com/google/jax) | High-performance computing | Apache 2.0 |
| [Hugging Face Transformers](https://github.com/huggingface/transformers) | NLP model library | Apache 2.0 |
| [ONNX Runtime](https://onnxruntime.ai/) | Cross-platform inference | MIT |
| [OpenCV](https://opencv.org/) | Computer vision library | Apache 2.0 |
| [Sentence Transformers](https://www.sbert.net/) | Sentence embeddings | Apache 2.0 |
| [LiteLLM](https://github.com/BerriAI/litellm) | Unified LLM API | MIT |
| [Instructor](https://github.com/jxnl/instructor) | Structured outputs | MIT |
| [Outlines](https://github.com/dottxt-ai/outlines) | Structured generation | Apache 2.0 |
| [BentoML](https://www.bentoml.com/) | Model serving | Apache 2.0 |
| [TensorRT](https://developer.nvidia.com/tensorrt) | GPU-optimized inference | Proprietary |

---

## 📚 AI Learning & Education

*Courses, tutorials, and resources to learn AI.*

| Name | Description | License |
|------|-------------|---------|
| [Fast.ai](https://www.fast.ai/) | Practical deep learning course (Free) | - |
| [Andrew Ng's Courses](https://www.deeplearning.ai/) | ML & AI specializations (Free/Paid) | - |
| [Hugging Face Course](https://huggingface.co/learn) | NLP with transformers (Free) | - |
| [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course) | ML fundamentals (Free) | - |
| [Anthropic Courses](https://github.com/anthropics/courses) | Prompt engineering, etc. (Free) | - |
| [Prompt Engineering Guide](https://www.promptingguide.ai/) | Comprehensive guide (Free) | - |
| [LangChain Academy](https://academy.langchain.com/) | Agent development (Free) | - |
| [Full-Stack Deep Learning](https://fullstackdeeplearning.com/) | Production ML (Free) | - |

---

## 🔍 AI Monitoring & Observability

*Tools for monitoring, testing, and evaluating AI applications.*

| Name | Description | License |
|------|-------------|---------|
| [LangSmith](https://smith.langchain.com/) | LLM tracing & evaluation | Proprietary |
| [Langfuse](https://langfuse.com/) | Open-source LLM observability | MIT |
| [Helicone](https://www.helicone.ai/) | LLM proxy & analytics | MIT |
| [Braintrust](https://www.braintrust.dev/) | AI evaluation platform | Proprietary |
| [Arize Phoenix](https://phoenix.arize.com/) | LLM observability | Apache 2.0 |
| [Weights & Biases](https://wandb.ai/) | Experiment tracking | Proprietary |
| [Promptfoo](https://www.promptfoo.dev/) | LLM testing framework | MIT |
| [Ragas](https://ragas.io/) | RAG evaluation | Apache 2.0 |
| [DeepEval](https://github.com/confident-ai/deepeval) | LLM evaluation | Apache 2.0 |

---

## 🛡️ AI Safety & Ethics

*Tools for responsible AI development.*

| Name | Description | License |
|------|-------------|---------|
| [Guardrails AI](https://www.guardrailsai.com/) | Output validation | Apache 2.0 |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Conversational safety | Apache 2.0 |
| [Lakera Guard](https://www.lakera.ai/) | AI security platform | Proprietary |
| [Rebuff](https://github.com/protectai/rebuff) | Prompt injection detection | MIT |
| [Llama Guard][huggingface-meta-llama] | Safety classifier | Llama Community |
| [Moderate Content](https://moderatecontent.com/) | Content moderation API | Proprietary |

---

## 🔮 Miscellaneous

*Other notable AI tools and resources.*

| Name | Description | License |
|------|-------------|---------|
| [Adept](https://www.adept.ai/) | Enterprise agentic AI platform | Proprietary |
| [Bolt.new](https://bolt.new/) | AI full-stack builder | Proprietary |
| [Devon](https://github.com/entropy-research/Devon) | Open-source AI dev | AGPL-3.0 |
| [Dust](https://dust.tt/) | AI workspace | Proprietary |
| [Gamma](https://gamma.app/) | AI presentations | Freemium |
| [Granola](https://www.granola.so/) | AI meeting notes | Freemium |
| [Mem](https://mem.ai/) | AI note-taking | Proprietary |
| [MultiOn](https://www.theagi.company/) | Browser AI agent | Proprietary |
| [Napkin](https://napkin.ai/) | AI diagrams | Freemium |
| [Sweep](https://github.com/sweepai/sweep) | AI junior dev | Apache 2.0 |
| [v0](https://v0.dev/) | AI UI generator | Proprietary |
| [WebPilot](https://webpilot.ai/) | Web browsing AI | Open |

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines][contributing] first.
