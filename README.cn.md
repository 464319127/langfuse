<img width="2400" alt="hero-b (1)" src="https://github.com/user-attachments/assets/5810ae13-15d6-4b60-afd2-927adc501861" />

<div align="center">
   <div>
      <h3>
         <a href="https://cloud.langfuse.com">
            <strong>Langfuse Cloud</strong>
         </a> · 
         <a href="https://langfuse.com/docs/deployment/self-host">
            <strong>自托管</strong>
         </a> · 
         <a href="https://langfuse.com/demo">
            <strong>演示</strong>
         </a>
      </h3>
   </div>

   <div>
      <a href="https://langfuse.com/docs"><strong>文档</strong></a> ·
      <a href="https://langfuse.com/issues"><strong>报告问题</strong></a> ·
      <a href="https://langfuse.com/ideas"><strong>功能请求</strong></a> ·
      <a href="https://langfuse.com/changelog"><strong>更新日志</strong></a> ·
      <a href="https://langfuse.com/roadmap"><strong>路线图</strong></a> ·
   </div>
   <br/>
   <div>
   </div>
</div>

<p align="center">
   <a href="https://github.com/langfuse/langfuse/blob/main/LICENSE">
   <img src="https://img.shields.io/badge/License-MIT-E11311.svg" alt="MIT License">
   </a>
   <a href="https://www.ycombinator.com/companies/langfuse"><img src="https://img.shields.io/badge/Y%20Combinator-W23-orange" alt="Y Combinator W23"></a>
   <a href="https://hub.docker.com/u/langfuse" target="_blank">
   <img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/langfuse/langfuse?labelColor=%20%23FDB062&logo=Docker&labelColor=%20%23528bff"></a>
   <a href="https://pypi.python.org/pypi/langfuse"><img src="https://img.shields.io/pypi/dm/langfuse?logo=python&logoColor=white&label=pypi%20langfuse&color=blue" alt="langfuse Python package on PyPi"></a>
   <a href="https://www.npmjs.com/package/langfuse"><img src="https://img.shields.io/npm/dm/langfuse?logo=npm&logoColor=white&label=npm%20langfuse&color=blue" alt="langfuse npm package"></a>
   <br/>
   <a href="https://discord.com/invite/7NXusRtqYU" target="_blank">
   <img src="https://img.shields.io/discord/1111061815649124414?logo=discord&labelColor=%20%235462eb&logoColor=%20%23f5f5f5&color=%20%235462eb"
      alt="chat on Discord"></a>
   <a href="https://twitter.com/intent/follow?screen_name=langfuse" target="_blank">
   <img src="https://img.shields.io/twitter/follow/langfuse?logo=X&color=%20%23f5f5f5"
      alt="follow on X(Twitter)"></a>
   <a href="https://www.linkedin.com/company/langfuse/" target="_blank">
   <img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff"
      alt="follow on LinkedIn"></a>
   <a href="https://github.com/langfuse/langfuse/graphs/commit-activity" target="_blank">
   <img alt="Commits last month" src="https://img.shields.io/github/commit-activity/m/langfuse/langfuse?labelColor=%20%2332b583&color=%20%2312b76a"></a>
   <a href="https://github.com/langfuse/langfuse/" target="_blank">
   <img alt="Issues closed" src="https://img.shields.io/github/issues-search?query=repo%3Alangfuse%2Flangfuse%20is%3Aclosed&label=issues%20closed&labelColor=%20%237d89b0&color=%20%235d6b98"></a>
   <a href="https://github.com/langfuse/langfuse/discussions/" target="_blank">
   <img alt="Discussion posts" src="https://img.shields.io/github/discussions/langfuse/langfuse?labelColor=%20%239b8afb&color=%20%237a5af8"></a>
</p>

<p align="center">
  <a href="./README.md"><img alt="README in English" src="https://img.shields.io/badge/English-d9d9d9"></a>
  <a href="./README.cn.md"><img alt="简体中文版自述文件" src="https://img.shields.io/badge/简体中文-d9d9d9"></a>
  <a href="./README.ja.md"><img alt="日本語のREADME" src="https://img.shields.io/badge/日本語-d9d9d9"></a>
  <a href="./README.kr.md"><img alt="README in Korean" src="https://img.shields.io/badge/한국어-d9d9d9"></a>
</p>

Langfuse 是一个 **开源 LLM 工程** 平台。它帮助团队协作 **开发、监控、评估** 和 **调试** AI 应用。Langfuse 可以在几分钟内完成 **自托管**，并且经过了 **实战检验**。自豪地基于 [ClickHouse 开源数据库](https://github.com/ClickHouse/ClickHouse) 构建。

> ### 🧑‍💻 我们正在招聘
>
> Langfuse 正在快速成长（过去 6 个月团队规模翻倍）—— 自 2026 年 1 月起我们已成为 ClickHouse 的一部分，目前正在欧盟范围内以混合办公方式招聘工程师。
> 我们招募热爱开源、追求卓越开发者体验的工程师。
> **[查看在招职位 →](https://langfuse.com/careers?utm_source=github&utm_medium=readme&utm_campaign=hiring&utm_content=langfuse)**


## ✨ 核心特性

<img width="2400" alt="features" src="https://github.com/user-attachments/assets/0fad3dee-f3ad-423c-9f0d-7ccd0f26cc2d" />

- [LLM 应用可观测性](https://langfuse.com/docs/tracing)：为你的应用添加埋点并开始将追踪数据（trace）发送到 Langfuse，从而跟踪 LLM 调用以及应用中的其他相关逻辑，如检索、嵌入或智能体（agent）操作。检查并调试复杂的日志和用户会话。试试交互式 [演示](https://langfuse.com/docs/demo) 来实际体验。

- [提示词管理](https://langfuse.com/docs/prompt-management/get-started) 帮助你集中管理、版本控制并协作迭代提示词。得益于服务端和客户端的强大缓存能力，你可以在不给应用增加延迟的情况下迭代提示词。

- [评估](https://langfuse.com/docs/evaluation/overview) 是 LLM 应用开发工作流的关键环节，Langfuse 能够适应你的需求。它支持 LLM 作为评审（LLM-as-a-judge）、代码评估器、用户反馈收集、人工标注，以及通过 API/SDK 实现的自定义评估流水线。

- [数据集](https://langfuse.com/docs/evaluation/dataset-runs/datasets) 为评估 LLM 应用提供测试集和基准。它们支持持续改进、部署前测试、结构化实验、灵活评估，并可与 LangChain、LlamaIndex 等框架无缝集成。

- [LLM Playground](https://langfuse.com/docs/playground) 是用于测试和迭代提示词及模型配置的工具，可缩短反馈循环、加速开发。当你在追踪数据中发现异常结果时，可以直接跳转到 Playground 进行迭代。

- [全面的 API](https://langfuse.com/docs/api)：Langfuse 常被用于驱动定制化的 LLMOps 工作流，同时通过 API 使用 Langfuse 提供的构建模块。提供 OpenAPI 规范、Postman 集合，以及 Python 和 JS/TS 的类型化 SDK。

## 📦 部署 Langfuse

<img width="2400" alt="deploy" src="https://github.com/user-attachments/assets/cf72e7f8-db7f-4e11-a2a1-ecfbe46f262c" />

### Langfuse Cloud

由 Langfuse 团队托管的部署方式，提供慷慨的免费额度，无需信用卡。

<div align="center">
    <a href="https://cloud.langfuse.com" target="_blank">
        <img alt="Static Badge" src="https://img.shields.io/badge/»%20Sign%20up%20for%20Langfuse%20Cloud-8A2BE2?&color=black">
    </a>
</div>

### 自托管 Langfuse

在你自己的基础设施上运行 Langfuse：

- [本地（docker compose）](https://langfuse.com/self-hosting/local)：使用 Docker Compose 在 5 分钟内在你自己的机器上运行 Langfuse。

  ```bash
  # 获取最新的 Langfuse 仓库副本
  git clone --depth=1 https://github.com/langfuse/langfuse.git
  cd langfuse

  # 运行 langfuse 的 docker compose
  docker compose up
  ```

- [虚拟机](https://langfuse.com/self-hosting/docker-compose)：使用 Docker Compose 在单台虚拟机上运行 Langfuse。
- [Kubernetes（Helm）](https://langfuse.com/self-hosting/kubernetes-helm)：使用 Helm 在 Kubernetes 集群上运行 Langfuse。这是首选的生产环境部署方式。
- Terraform 模板：[AWS](https://langfuse.com/self-hosting/aws)、[Azure](https://langfuse.com/self-hosting/azure)、[GCP](https://langfuse.com/self-hosting/gcp)

参阅 [自托管文档](https://langfuse.com/self-hosting) 了解更多关于架构和配置选项的信息。

## 🔌 集成

<img width="2400" alt="integrations" src="https://github.com/user-attachments/assets/b85c9a45-68f0-4f76-b545-0e8632abef9f" />

### 主要集成：

| 集成                                                                         | 支持                       | 描述                                                                                                                                             |
| ---------------------------------------------------------------------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| [SDK](https://langfuse.com/docs/sdk)                                         | Python, JS/TS              | 使用 SDK 手动埋点，获得最大灵活性。                                                                                                              |
| [OpenAI](https://langfuse.com/integrations/model-providers/openai-py)        | Python, JS/TS              | 通过直接替换 OpenAI SDK 实现自动埋点。                                                                                                           |
| [Langchain](https://langfuse.com/docs/integrations/langchain)                | Python, JS/TS              | 通过向 Langchain 应用传入回调处理器实现自动埋点。                                                                                                |
| [LlamaIndex](https://langfuse.com/docs/integrations/llama-index/get-started) | Python                     | 通过 LlamaIndex 回调系统实现自动埋点。                                                                                                           |
| [Haystack](https://langfuse.com/docs/integrations/haystack)                  | Python                     | 通过 Haystack 内容追踪系统实现自动埋点。                                                                                                         |
| [LiteLLM](https://langfuse.com/docs/integrations/litellm)                    | Python, JS/TS（仅代理）    | 将任何 LLM 用作 GPT 的直接替代。支持 Azure、OpenAI、Cohere、Anthropic、Ollama、VLLM、Sagemaker、HuggingFace、Replicate（100+ LLM）。             |
| [Vercel AI SDK](https://langfuse.com/docs/integrations/vercel-ai-sdk)        | JS/TS                      | TypeScript 工具包，帮助开发者使用 React、Next.js、Vue、Svelte、Node.js 构建 AI 应用。                                                            |
| [Mastra](https://langfuse.com/docs/integrations/mastra)                      | JS/TS                      | 用于构建 AI 智能体和多智能体系统的开源框架。                                                                                                     |
| [API](https://langfuse.com/docs/api)                                         |                            | 直接调用公共 API。提供 OpenAPI 规范。                                                                                                            |

### 与 Langfuse 集成的软件包：

| 名称                                                                    | 类型               | 描述                                                                                                                     |
| ----------------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| [Instructor](https://langfuse.com/docs/integrations/instructor)         | 库                 | 用于获取结构化 LLM 输出（JSON、Pydantic）的库                                                                            |
| [DSPy](https://langfuse.com/docs/integrations/dspy)                     | 库                 | 系统性优化语言模型提示词和权重的框架                                                                                     |
| [Mirascope](https://langfuse.com/docs/integrations/mirascope)           | 库                 | 用于构建 LLM 应用的 Python 工具包。                                                                                      |
| [Ollama](https://langfuse.com/docs/integrations/ollama)                 | 模型（本地）       | 在自己的机器上轻松运行开源 LLM。                                                                                         |
| [Amazon Bedrock](https://langfuse.com/docs/integrations/amazon-bedrock) | 模型               | 在 AWS 上运行基础模型和微调模型。                                                                                        |
| [AutoGen](https://langfuse.com/docs/integrations/autogen)               | 智能体框架         | 用于构建分布式智能体的开源 LLM 平台。                                                                                    |
| [Flowise](https://langfuse.com/docs/integrations/flowise)               | 聊天/智能体&nbsp;UI | 基于 JS/TS 的无代码构建器，用于定制化 LLM 流程。                                                                         |
| [Langflow](https://langfuse.com/docs/integrations/langflow)             | 聊天/智能体&nbsp;UI | 基于 Python 的 LangChain 用户界面，采用 react-flow 设计，提供轻松的流程实验与原型构建体验。                              |
| [Dify](https://langfuse.com/docs/integrations/dify)                     | 聊天/智能体&nbsp;UI | 带无代码构建器的开源 LLM 应用开发平台。                                                                                  |
| [OpenWebUI](https://langfuse.com/docs/integrations/openwebui)           | 聊天/智能体&nbsp;UI | 自托管的 LLM 聊天 Web UI，支持包括自托管和本地模型在内的多种 LLM 运行器。                                                |
| [Promptfoo](https://langfuse.com/docs/integrations/promptfoo)           | 工具               | 开源 LLM 测试平台。                                                                                                      |
| [LobeChat](https://langfuse.com/docs/integrations/lobechat)             | 聊天/智能体&nbsp;UI | 开源聊天机器人平台。                                                                                                     |
| [Vapi](https://langfuse.com/docs/integrations/vapi)                     | 平台               | 开源语音 AI 平台。                                                                                                       |
| [Inferable](https://langfuse.com/docs/integrations/other/inferable)     | 智能体             | 用于构建分布式智能体的开源 LLM 平台。                                                                                    |
| [Gradio](https://langfuse.com/docs/integrations/other/gradio)           | 聊天/智能体&nbsp;UI | 用于构建聊天 UI 等 Web 界面的开源 Python 库。                                                                            |
| [Goose](https://langfuse.com/docs/integrations/goose)                   | 智能体             | 用于构建分布式智能体的开源 LLM 平台。                                                                                    |
| [smolagents](https://langfuse.com/docs/integrations/smolagents)         | 智能体             | 开源 AI 智能体框架。                                                                                                     |
| [CrewAI](https://langfuse.com/docs/integrations/crewai)                 | 智能体             | 用于智能体协作和工具调用的多智能体框架。                                                                                 |

## 🚀 快速开始

为你的应用添加埋点并开始将追踪数据发送到 Langfuse，从而跟踪 LLM 调用以及应用中的其他相关逻辑，如检索、嵌入或智能体操作。检查并调试复杂的日志和用户会话。

### 1️⃣ 创建新项目

1.  [创建 Langfuse 账户](https://cloud.langfuse.com/auth/sign-up) 或 [自托管](https://langfuse.com/self-hosting)
2.  创建一个新项目
3.  在项目设置中创建新的 API 凭证

### 2️⃣ 记录你的第一次 LLM 调用

[`@observe()` 装饰器](https://langfuse.com/docs/sdk/python/decorators) 让追踪任何 Python LLM 应用变得非常简单。在本快速开始中，我们还使用了 Langfuse 的 [OpenAI 集成](https://langfuse.com/integrations/model-providers/openai-py) 来自动捕获所有模型参数。

> [!TIP]
> 不使用 OpenAI？请访问 [我们的文档](https://langfuse.com/docs/get-started#log-your-first-llm-call-to-langfuse) 了解如何记录其他模型和框架。

```bash
pip install langfuse openai
```

```bash filename=".env"
LANGFUSE_SECRET_KEY="sk-lf-..."
LANGFUSE_PUBLIC_KEY="pk-lf-..."
LANGFUSE_BASE_URL="https://cloud.langfuse.com" # 🇪🇺 欧盟区域
# LANGFUSE_BASE_URL="https://us.cloud.langfuse.com" # 🇺🇸 美国区域
```

```python /@observe()/ /from langfuse.openai import openai/ filename="main.py"
from langfuse import observe
from langfuse.openai import openai # OpenAI 集成

@observe()
def story():
    return openai.chat.completions.create(
        model="gpt-4o",
        messages=[{"role": "user", "content": "What is Langfuse?"}],
    ).choices[0].message.content

@observe()
def main():
    return story()

main()
```

### 3️⃣ 在 Langfuse 中查看追踪数据

在 Langfuse 中查看你的语言模型调用及其他应用逻辑。

<img width="1600" alt="example-trace-for-github" src="https://github.com/user-attachments/assets/8f6995b7-285f-441a-b52f-1331d13ceb45" />

_[Langfuse 中的公开示例追踪](https://cloud.langfuse.com/project/cloramnkj0002jz088vzn1ja4/traces/db22d0a442216b485abd83cc9df6d9ee)_

## 💭 支持

查找问题答案：

- 我们的 [文档](https://langfuse.com/docs) 是查找答案的最佳起点。它内容全面，我们投入了大量时间维护。你也可以通过 GitHub 对文档提出修改建议。
- [Langfuse FAQ](https://langfuse.com/faq) 解答了最常见的问题。
- 使用 "[Ask AI](https://langfuse.com/docs/ask-ai)" 即时获取问题答案。

支持渠道：

- **在 GitHub Discussions 的 [公开问答](https://github.com/orgs/langfuse/discussions/categories/support) 中提出任何问题。** 请尽量提供详细信息（如代码片段、截图、背景信息），帮助我们理解你的问题。
- 在 GitHub Discussions 中 [请求功能](https://github.com/orgs/langfuse/discussions/categories/ideas)。
- 在 GitHub Issues 中 [报告 Bug](https://github.com/langfuse/langfuse/issues)。
- 对于时效性较强的问题，请通过应用内聊天组件联系我们。

## 🤝 贡献

欢迎你的贡献！

- 在 GitHub Discussions 中为 [想法](https://github.com/orgs/langfuse/discussions/categories/ideas) 投票。
- 提出并评论 [Issues](https://github.com/langfuse/langfuse/issues)。
- 提交 PR —— 参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何搭建开发环境。

## 🥇 许可证

除 `ee` 文件夹外，本仓库采用 MIT 许可证。详情参阅 [LICENSE](LICENSE) 和 [文档](https://langfuse.com/docs/open-source)。

## 依赖

我们将此代码库部署在基于 Linux Alpine 镜像的 Docker 容器中（[来源](https://github.com/nodejs/docker-node)）。Dockerfile 位于 [web/Dockerfile](web/Dockerfile) 和 [worker/Dockerfile](worker/Dockerfile)。

## ⭐️ Star 历史

<a href="https://star-history.com/#langfuse/langfuse&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=langfuse/langfuse&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=langfuse/langfuse&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=langfuse/langfuse&type=Date" style="border-radius: 15px;" />
 </picture>
</a>

## ❤️ 使用 Langfuse 的开源项目

使用 Langfuse 的顶级开源 Python 项目，按 star 数排名（[来源](https://github.com/langfuse/langfuse-docs/blob/main/components-mdx/dependents)）：

| 仓库                                                                                                                                                                                                                                                                                                             |  Star 数 |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -----: |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/85702467?s=40&v=4" width="20" height="20" alt=""> &nbsp; [langflow-ai](https://github.com/langflow-ai) / [langflow](https://github.com/langflow-ai/langflow)                                                                             | 116251 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/158137808?s=40&v=4" width="20" height="20" alt=""> &nbsp; [open-webui](https://github.com/open-webui) / [open-webui](https://github.com/open-webui/open-webui)                                                                           | 109642 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/23818?s=40&v=4" width="20" height="20" alt=""> &nbsp; [abi](https://github.com/abi) / [screenshot-to-code](https://github.com/abi/screenshot-to-code)                                                                                    |  70877 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/131470832?s=40&v=4" width="20" height="20" alt=""> &nbsp; [lobehub](https://github.com/lobehub) / [lobe-chat](https://github.com/lobehub/lobe-chat)                                                                                      |  65454 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/69962740?s=40&v=4" width="20" height="20" alt=""> &nbsp; [infiniflow](https://github.com/infiniflow) / [ragflow](https://github.com/infiniflow/ragflow)                                                                                  |  64118 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/135057108?s=40&v=4" width="20" height="20" alt=""> &nbsp; [firecrawl](https://github.com/firecrawl) / [firecrawl](https://github.com/firecrawl/firecrawl)                                                                                |  56713 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/130722866?s=40&v=4" width="20" height="20" alt=""> &nbsp; [run-llama](https://github.com/run-llama) / [llama_index](https://github.com/run-llama/llama_index)                                                                            |  44203 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/128289781?s=40&v=4" width="20" height="20" alt=""> &nbsp; [FlowiseAI](https://github.com/FlowiseAI) / [Flowise](https://github.com/FlowiseAI/Flowise)                                                                                    |  43547 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/159330290?s=40&v=4" width="20" height="20" alt=""> &nbsp; [QuivrHQ](https://github.com/QuivrHQ) / [quivr](https://github.com/QuivrHQ/quivr)                                                                                              |  38415 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/6154722?s=40&v=4" width="20" height="20" alt=""> &nbsp; [microsoft](https://github.com/microsoft) / [ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners)                                                      |  38012 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/139558948?s=40&v=4" width="20" height="20" alt=""> &nbsp; [chatchat-space](https://github.com/chatchat-space) / [Langchain-Chatchat](https://github.com/chatchat-space/Langchain-Chatchat)                                               |  36071 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/31035808?s=40&v=4" width="20" height="20" alt=""> &nbsp; [mindsdb](https://github.com/mindsdb) / [mindsdb](https://github.com/mindsdb/mindsdb)                                                                                           |  35669 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/169401942?s=40&v=4" width="20" height="20" alt=""> &nbsp; [danny-avila](https://github.com/danny-avila) / [LibreChat](https://github.com/danny-avila/LibreChat)                                                                            |  33142 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/121462774?s=40&v=4" width="20" height="20" alt=""> &nbsp; [BerriAI](https://github.com/BerriAI) / [litellm](https://github.com/BerriAI/litellm)                                                                                          |  28726 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/157326433?s=40&v=4" width="20" height="20" alt=""> &nbsp; [onlook-dev](https://github.com/onlook-dev) / [onlook](https://github.com/onlook-dev/onlook)                                                                                   |  22447 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/487568?s=40&v=4" width="20" height="20" alt=""> &nbsp; [NixOS](https://github.com/NixOS) / [nixpkgs](https://github.com/NixOS/nixpkgs)                                                                                                   |  21748 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/170767358?s=40&v=4" width="20" height="20" alt=""> &nbsp; [kortix-ai](https://github.com/kortix-ai) / [suna](https://github.com/kortix-ai/suna)                                                                                          |  17976 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/76263028?s=40&v=4" width="20" height="20" alt=""> &nbsp; [anthropics](https://github.com/anthropics) / [courses](https://github.com/anthropics/courses)                                                                                  |  17057 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/149120496?s=40&v=4" width="20" height="20" alt=""> &nbsp; [mastra-ai](https://github.com/mastra-ai) / [mastra](https://github.com/mastra-ai/mastra)                                                                                      |  16484 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/134601687?s=40&v=4" width="20" height="20" alt=""> &nbsp; [langfuse](https://github.com/langfuse) / [langfuse](https://github.com/langfuse/langfuse)                                                                                     |  16054 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/7250217?s=40&v=4" width="20" height="20" alt=""> &nbsp; [Canner](https://github.com/Canner) / [WrenAI](https://github.com/Canner/WrenAI)                                                                                                 |  11868 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/137907881?s=40&v=4" width="20" height="20" alt=""> &nbsp; [promptfoo](https://github.com/promptfoo) / [promptfoo](https://github.com/promptfoo/promptfoo)                                                                                |   8350 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/193350244?s=40&v=4" width="20" height="20" alt=""> &nbsp; [The-Pocket](https://github.com/The-Pocket) / [PocketFlow](https://github.com/The-Pocket/PocketFlow)                                                                           |   8313 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/139012218?s=40&v=4" width="20" height="20" alt=""> &nbsp; [OpenPipe](https://github.com/OpenPipe) / [ART](https://github.com/OpenPipe/ART)                                                                                               |   7093 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/125468716?s=40&v=4" width="20" height="20" alt=""> &nbsp; [topoteretes](https://github.com/topoteretes) / [cognee](https://github.com/topoteretes/cognee)                                                                                |   7011 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/3299148?s=40&v=4" width="20" height="20" alt=""> &nbsp; [awslabs](https://github.com/awslabs) / [agent-squad](https://github.com/awslabs/agent-squad)                                                                                    |   6785 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/162546372?s=40&v=4" width="20" height="20" alt=""> &nbsp; [BasedHardware](https://github.com/BasedHardware) / [omi](https://github.com/BasedHardware/omi)                                                                                |   6231 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/118301880?s=40&v=4" width="20" height="20" alt=""> &nbsp; [hatchet-dev](https://github.com/hatchet-dev) / [hatchet](https://github.com/hatchet-dev/hatchet)                                                                              |   6019 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/88676955?s=40&v=4" width="20" height="20" alt=""> &nbsp; [zenml-io](https://github.com/zenml-io) / [zenml](https://github.com/zenml-io/zenml)                                                                                            |   4873 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/132635806?s=40&v=4" width="20" height="20" alt=""> &nbsp; [refly-ai](https://github.com/refly-ai) / [refly](https://github.com/refly-ai/refly)                                                                                           |   4654 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/47287758?s=40&v=4" width="20" height="20" alt=""> &nbsp; [coleam00](https://github.com/coleam00) / [ottomator-agents](https://github.com/coleam00/ottomator-agents)                                                                      |   4165 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/8251002?s=40&v=4" width="20" height="20" alt=""> &nbsp; [JoshuaC215](https://github.com/JoshuaC215) / [agent-service-toolkit](https://github.com/JoshuaC215/agent-service-toolkit)                                                       |   3557 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/185852128?s=40&v=4" width="20" height="20" alt=""> &nbsp; [colanode](https://github.com/colanode) / [colanode](https://github.com/colanode/colanode)                                                                                     |   3517 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/201282378?s=40&v=4" width="20" height="20" alt=""> &nbsp; [VoltAgent](https://github.com/VoltAgent) / [voltagent](https://github.com/VoltAgent/voltagent)                                                                                |   3210 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/188657705?s=40&v=4" width="20" height="20" alt=""> &nbsp; [bragai](https://github.com/bragai) / [bRAG-langchain](https://github.com/bragai/bRAG-langchain)                                                                               |   3010 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/11855343?s=40&v=4" width="20" height="20" alt=""> &nbsp; [pingcap](https://github.com/pingcap) / [autoflow](https://github.com/pingcap/autoflow)                                                                                         |   2651 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/135396723?s=40&v=4" width="20" height="20" alt=""> &nbsp; [sourcebot-dev](https://github.com/sourcebot-dev) / [sourcebot](https://github.com/sourcebot-dev/sourcebot)                                                                    |   2570 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/158137808?s=40&v=4" width="20" height="20" alt=""> &nbsp; [open-webui](https://github.com/open-webui) / [pipelines](https://github.com/open-webui/pipelines)                                                                             |   2055 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/179994263?s=40&v=4" width="20" height="20" alt=""> &nbsp; [YFGaia](https://github.com/YFGaia) / [dify-plus](https://github.com/YFGaia/dify-plus)                                                                                         |   1734 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/46323662?s=40&v=4" width="20" height="20" alt=""> &nbsp; [TheSpaghettiDetective](https://github.com/TheSpaghettiDetective) / [obico-server](https://github.com/TheSpaghettiDetective/obico-server)                                       |   1687 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/85268109?s=40&v=4" width="20" height="20" alt=""> &nbsp; [MLSysOps](https://github.com/MLSysOps) / [MLE-agent](https://github.com/MLSysOps/MLE-agent)                                                                                    |   1387 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/144196744?s=40&v=4" width="20" height="20" alt=""> &nbsp; [TIGER-AI-Lab](https://github.com/TIGER-AI-Lab) / [TheoremExplainAgent](https://github.com/TIGER-AI-Lab/TheoremExplainAgent)                                                   |   1385 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/2314423?s=40&v=4" width="20" height="20" alt=""> &nbsp; [trailofbits](https://github.com/trailofbits) / [buttercup](https://github.com/trailofbits/buttercup)                                                                            |   1223 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/62564480?s=40&v=4" width="20" height="20" alt=""> &nbsp; [wassim249](https://github.com/wassim249) / [fastapi-langgraph-agent-production-ready-template](https://github.com/wassim249/fastapi-langgraph-agent-production-ready-template) |   1200 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/18422723?s=40&v=4" width="20" height="20" alt=""> &nbsp; [alishobeiri](https://github.com/alishobeiri) / [thread](https://github.com/alishobeiri/thread)                                                                                 |   1098 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/2357342?s=40&v=4" width="20" height="20" alt=""> &nbsp; [dmayboroda](https://github.com/dmayboroda) / [minima](https://github.com/dmayboroda/minima)                                                                                     |   1010 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/65890619?s=40&v=4" width="20" height="20" alt=""> &nbsp; [zstar1003](https://github.com/zstar1003) / [ragflow-plus](https://github.com/zstar1003/ragflow-plus)                                                                           |    993 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/121352441?s=40&v=4" width="20" height="20" alt=""> &nbsp; [openops-cloud](https://github.com/openops-cloud) / [openops](https://github.com/openops-cloud/openops)                                                                        |    939 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/151867818?s=40&v=4" width="20" height="20" alt=""> &nbsp; [dynamiq-ai](https://github.com/dynamiq-ai) / [dynamiq](https://github.com/dynamiq-ai/dynamiq)                                                                                 |    927 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/74420131?s=40&v=4" width="20" height="20" alt=""> &nbsp; [xataio](https://github.com/xataio) / [agent](https://github.com/xataio/agent)                                                                                                  |    857 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/123981229?s=40&v=4" width="20" height="20" alt=""> &nbsp; [plastic-labs](https://github.com/plastic-labs) / [tutor-gpt](https://github.com/plastic-labs/tutor-gpt)                                                                       |    845 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/176438967?s=40&v=4" width="20" height="20" alt=""> &nbsp; [trendy-design](https://github.com/trendy-design) / [llmchat](https://github.com/trendy-design/llmchat)                                                                        |    829 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/2045570?s=40&v=4" width="20" height="20" alt=""> &nbsp; [hotovo](https://github.com/hotovo) / [aider-desk](https://github.com/hotovo/aider-desk)                                                                                         |    781 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/169500408?s=40&v=4" width="20" height="20" alt=""> &nbsp; [opslane](https://github.com/opslane) / [opslane](https://github.com/opslane/opslane)                                                                                          |    719 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/142796018?s=40&v=4" width="20" height="20" alt=""> &nbsp; [wrtnlabs](https://github.com/wrtnlabs) / [autoview](https://github.com/wrtnlabs/autoview)                                                                                     |    688 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/20493493?s=40&v=4" width="20" height="20" alt=""> &nbsp; [andysingal](https://github.com/andysingal) / [llm-course](https://github.com/andysingal/llm-course)                                                                            |    643 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/48585267?s=40&v=4" width="20" height="20" alt=""> &nbsp; [theopenconversationkit](https://github.com/theopenconversationkit) / [tock](https://github.com/theopenconversationkit/tock)                                                    |    587 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/178644984?s=40&v=4" width="20" height="20" alt=""> &nbsp; [sentient-engineering](https://github.com/sentient-engineering) / [agent-q](https://github.com/sentient-engineering/agent-q)                                                   |    487 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/58037050?s=40&v=4" width="20" height="20" alt=""> &nbsp; [NicholasGoh](https://github.com/NicholasGoh) / [fastapi-mcp-langgraph-template](https://github.com/NicholasGoh/fastapi-mcp-langgraph-template)                                 |    481 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/148684274?s=40&v=4" width="20" height="20" alt=""> &nbsp; [i-am-alice](https://github.com/i-am-alice) / [3rd-devs](https://github.com/i-am-alice/3rd-devs)                                                                               |    472 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/163431636?s=40&v=4" width="20" height="20" alt=""> &nbsp; [AIDotNet](https://github.com/AIDotNet) / [koala-ai](https://github.com/AIDotNet/koala-ai)                                                                                     |    470 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/132396805?s=40&v=4" width="20" height="20" alt=""> &nbsp; [phospho-app](https://github.com/phospho-app) / [text-analytics-legacy](https://github.com/phospho-app/text-analytics-legacy)                                                  |    439 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/170831637?s=40&v=4" width="20" height="20" alt=""> &nbsp; [inferablehq](https://github.com/inferablehq) / [inferable](https://github.com/inferablehq/inferable)                                                                          |    403 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/171800766?s=40&v=4" width="20" height="20" alt=""> &nbsp; [duoyang666](https://github.com/duoyang666) / [ai_novel](https://github.com/duoyang666/ai_novel)                                                                               |    397 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/209155962?s=40&v=4" width="20" height="20" alt=""> &nbsp; [strands-agents](https://github.com/strands-agents) / [samples](https://github.com/strands-agents/samples)                                                                     |    385 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/16997807?s=40&v=4" width="20" height="20" alt=""> &nbsp; [FranciscoMoretti](https://github.com/FranciscoMoretti) / [sparka](https://github.com/FranciscoMoretti/sparka)                                                                  |    380 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/66303003?s=40&v=4" width="20" height="20" alt=""> &nbsp; [RobotecAI](https://github.com/RobotecAI) / [rai](https://github.com/RobotecAI/rai)                                                                                             |    373 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/137044109?s=40&v=4" width="20" height="20" alt=""> &nbsp; [ElectricCodeGuy](https://github.com/ElectricCodeGuy) / [SupabaseAuthWithSSR](https://github.com/ElectricCodeGuy/SupabaseAuthWithSSR)                                          |    370 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/15125613?s=40&v=4" width="20" height="20" alt=""> &nbsp; [souzatharsis](https://github.com/souzatharsis) / [tamingLLMs](https://github.com/souzatharsis/tamingLLMs)                                                                      |    323 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/8931462?s=40&v=4" width="20" height="20" alt=""> &nbsp; [aws-samples](https://github.com/aws-samples) / [aws-ai-ml-workshop-kr](https://github.com/aws-samples/aws-ai-ml-workshop-kr)                                                    |    295 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/25676773?s=40&v=4" width="20" height="20" alt=""> &nbsp; [weizxfree](https://github.com/weizxfree) / [KnowFlow](https://github.com/weizxfree/KnowFlow)                                                                                   |    285 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/88676955?s=40&v=4" width="20" height="20" alt=""> &nbsp; [zenml-io](https://github.com/zenml-io) / [zenml-projects](https://github.com/zenml-io/zenml-projects)                                                                          |    276 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/136071305?s=40&v=4" width="20" height="20" alt=""> &nbsp; [wxai-space](https://github.com/wxai-space) / [LightAgent](https://github.com/wxai-space/LightAgent)                                                                           |    275 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/90278288?s=40&v=4" width="20" height="20" alt=""> &nbsp; [Ozamatash](https://github.com/Ozamatash) / [deep-research-mcp](https://github.com/Ozamatash/deep-research-mcp)                                                                 |    269 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/168552753?s=40&v=4" width="20" height="20" alt=""> &nbsp; [sql-agi](https://github.com/sql-agi) / [DB-GPT](https://github.com/sql-agi/DB-GPT)                                                                                            |    241 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/828269?s=40&v=4" width="20" height="20" alt=""> &nbsp; [guyernest](https://github.com/guyernest) / [advanced-rag](https://github.com/guyernest/advanced-rag)                                                                             |    238 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/175069511?s=40&v=4" width="20" height="20" alt=""> &nbsp; [bklieger-groq](https://github.com/bklieger-groq) / [mathtutor-on-groq](https://github.com/bklieger-groq/mathtutor-on-groq)                                                    |    233 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/123981229?s=40&v=4" width="20" height="20" alt=""> &nbsp; [plastic-labs](https://github.com/plastic-labs) / [honcho](https://github.com/plastic-labs/honcho)                                                                             |    224 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/118967077?s=40&v=4" width="20" height="20" alt=""> &nbsp; [OVINC-CN](https://github.com/OVINC-CN) / [OpenWebUI](https://github.com/OVINC-CN/OpenWebUI)                                                                                   |    202 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/31960995?s=40&v=4" width="20" height="20" alt=""> &nbsp; [zhutoutoutousan](https://github.com/zhutoutoutousan) / [worldquant-miner](https://github.com/zhutoutoutousan/worldquant-miner)                                                 |    202 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/29215115?s=40&v=4" width="20" height="20" alt=""> &nbsp; [iceener](https://github.com/iceener) / [ai](https://github.com/iceener/ai)                                                                                                     |    186 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/187584218?s=40&v=4" width="20" height="20" alt=""> &nbsp; [giselles-ai](https://github.com/giselles-ai) / [giselle](https://github.com/giselles-ai/giselle)                                                                              |    181 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/174666116?s=40&v=4" width="20" height="20" alt=""> &nbsp; [ai-shifu](https://github.com/ai-shifu) / [ai-shifu](https://github.com/ai-shifu/ai-shifu)                                                                                     |    181 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/8931462?s=40&v=4" width="20" height="20" alt=""> &nbsp; [aws-samples](https://github.com/aws-samples) / [sample-serverless-mcp-servers](https://github.com/aws-samples/sample-serverless-mcp-servers)                                    |    175 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/202488052?s=40&v=4" width="20" height="20" alt=""> &nbsp; [celerforge](https://github.com/celerforge) / [freenote](https://github.com/celerforge/freenote)                                                                               |    171 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/104478511?s=40&v=4" width="20" height="20" alt=""> &nbsp; [babelcloud](https://github.com/babelcloud) / [LLM-RGB](https://github.com/babelcloud/LLM-RGB)                                                                                 |    164 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/171735272?s=40&v=4" width="20" height="20" alt=""> &nbsp; [8090-inc](https://github.com/8090-inc) / [xrx-sample-apps](https://github.com/8090-inc/xrx-sample-apps)                                                                       |    163 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/51827949?s=40&v=4" width="20" height="20" alt=""> &nbsp; [deepset-ai](https://github.com/deepset-ai) / [haystack-core-integrations](https://github.com/deepset-ai/haystack-core-integrations)                                            |    163 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/1009716?s=40&v=4" width="20" height="20" alt=""> &nbsp; [codecentric](https://github.com/codecentric) / [c4-genai-suite](https://github.com/codecentric/c4-genai-suite)                                                                  |    152 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/196509932?s=40&v=4" width="20" height="20" alt=""> &nbsp; [XSpoonAi](https://github.com/XSpoonAi) / [spoon-core](https://github.com/XSpoonAi/spoon-core)                                                                                 |    150 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/139558948?s=40&v=4" width="20" height="20" alt=""> &nbsp; [chatchat-space](https://github.com/chatchat-space) / [LangGraph-Chatchat](https://github.com/chatchat-space/LangGraph-Chatchat)                                               |    144 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/134601687?s=40&v=4" width="20" height="20" alt=""> &nbsp; [langfuse](https://github.com/langfuse) / [langfuse-docs](https://github.com/langfuse/langfuse-docs)                                                                           |    139 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/44976328?s=40&v=4" width="20" height="20" alt=""> &nbsp; [piyushgarg-dev](https://github.com/piyushgarg-dev) / [genai-cohort](https://github.com/piyushgarg-dev/genai-cohort)                                                            |    135 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/105285801?s=40&v=4" width="20" height="20" alt=""> &nbsp; [i-dot-ai](https://github.com/i-dot-ai) / [redbox](https://github.com/i-dot-ai/redbox)                                                                                         |    132 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/90423581?s=40&v=4" width="20" height="20" alt=""> &nbsp; [bmd1905](https://github.com/bmd1905) / [ChatOpsLLM](https://github.com/bmd1905/ChatOpsLLM)                                                                                     |    127 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/202074444?s=40&v=4" width="20" height="20" alt=""> &nbsp; [Fintech-Dreamer](https://github.com/Fintech-Dreamer) / [FinSynth](https://github.com/Fintech-Dreamer/FinSynth)                                                                |    121 |
| <img class="avatar mr-2" src="https://avatars.githubusercontent.com/u/1566555?s=40&v=4" width="20" height="20" alt=""> &nbsp; [kenshiro-o](https://github.com/kenshiro-o) / [nagato-ai](https://github.com/kenshiro-o/nagato-ai)                                                                               |    119 |

## 🔒 安全与隐私

我们非常重视数据安全和隐私。更多信息请参阅我们的 [安全与隐私](https://langfuse.com/security) 页面。

### 遥测

默认情况下，Langfuse 会自动将自托管实例的基础使用统计数据上报到集中式服务器（PostHog）。

这有助于我们：

1. 了解 Langfuse 的使用方式，并改进最重要的功能。
2. 跟踪整体使用情况，用于内部和外部（如融资）报告。

遥测数据不包含原始追踪数据（traces）、提示词（prompts）、观测数据（observations）、评分（scores）或数据集内容。我们在 [遥测文档](https://langfuse.com/self-hosting/security/telemetry) 中记录了收集的确切字段、数据发送目的地以及实现参考。

对于 Langfuse OSS，你可以通过设置 `TELEMETRY_ENABLED=false` 来选择退出。

<!-- Scarf pixel — cookie-free, privacy-friendly analytics for README views (no cookies, no IP/PII stored). https://docs.scarf.sh/web-traffic/ -->
<img referrerpolicy="no-referrer-when-downgrade" src="https://static.scarf.sh/a.png?x-pxid=5f9b700f-ee94-4940-b005-e72def008ffa&page=README.md" />
