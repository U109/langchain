<div align="center">
  <a href="https://www.langchain.com/">
    <picture>
      <source media="(prefers-color-scheme: light)" srcset=".github/images/logo-dark.svg">
      <source media="(prefers-color-scheme: dark)" srcset=".github/images/logo-light.svg">
      <img alt="LangChain Logo" src=".github/images/logo-dark.svg" width="80%">
    </picture>
  </a>
</div>

<div align="center">
  <h3>The platform for reliable agents.</h3>
</div>

<div align="center">
  <a href="https://opensource.org/licenses/MIT" target="_blank"><img src="https://img.shields.io/pypi/l/langchain" alt="PyPI - License"></a>
  <a href="https://pypistats.org/packages/langchain" target="_blank"><img src="https://img.shields.io/pepy/dt/langchain" alt="PyPI - Downloads"></a>
  <a href="https://pypi.org/project/langchain/#history" target="_blank"><img src="https://img.shields.io/pypi/v/langchain?label=%20" alt="Version"></a>
  <a href="https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/langchain-ai/langchain" target="_blank"><img src="https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode" alt="Open in Dev Containers"></a>
  <a href="https://codespaces.new/langchain-ai/langchain" target="_blank"><img src="https://github.com/codespaces/badge.svg" alt="Open in Github Codespace" title="Open in Github Codespace" width="150" height="20"></a>
  <a href="https://codspeed.io/langchain-ai/langchain" target="_blank"><img src="https://img.shields.io/endpoint?url=https://codspeed.io/badge.json" alt="CodSpeed Badge"></a>
  <a href="https://twitter.com/langchainai" target="_blank"><img src="https://img.shields.io/twitter/url/https/twitter.com/langchainai.svg?style=social&label=Follow%20%40LangChainAI" alt="Twitter / X"></a>
</div>

LangChain is a framework for building agents and LLM-powered applications. It helps you chain together interoperable components and third-party integrations to simplify AI application development – all while future-proofing decisions as the underlying technology evolves.

```bash
pip install langchain
```

If you're looking for more advanced customization or agent orchestration, check out [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview), our framework for building controllable agent workflows.

---

**Documentation**:

- [docs.langchain.com](https://docs.langchain.com/oss/python/langchain/overview) – Comprehensive documentation, including conceptual overviews and guides
- [reference.langchain.com/python](https://reference.langchain.com/python) – API reference docs for LangChain packages

**Discussions**: Visit the [LangChain Forum](https://forum.langchain.com) to connect with the community and share all of your technical questions, ideas, and feedback.

> [!NOTE]
> Looking for the JS/TS library? Check out [LangChain.js](https://github.com/langchain-ai/langchainjs).

## Why use LangChain?

LangChain helps developers build applications powered by LLMs through a standard interface for models, embeddings, vector stores, and more.

Use LangChain for:

- **Real-time data augmentation**. Easily connect LLMs to diverse data sources and external/internal systems, drawing from LangChain's vast library of integrations with model providers, tools, vector stores, retrievers, and more.
- **Model interoperability**. Swap models in and out as your engineering team experiments to find the best choice for your application's needs. As the industry frontier evolves, adapt quickly – LangChain's abstractions keep you moving without losing momentum.
- **Rapid prototyping**. Quickly build and iterate on LLM applications with LangChain's modular, component-based architecture. Test different approaches and workflows without rebuilding from scratch, accelerating your development cycle.
- **Production-ready features**. Deploy reliable applications with built-in support for monitoring, evaluation, and debugging through integrations like LangSmith. Scale with confidence using battle-tested patterns and best practices.
- **Vibrant community and ecosystem**. Leverage a rich ecosystem of integrations, templates, and community-contributed components. Benefit from continuous improvements and stay up-to-date with the latest AI developments through an active open-source community.
- **Flexible abstraction layers**. Work at the level of abstraction that suits your needs - from high-level chains for quick starts to low-level components for fine-grained control. LangChain grows with your application's complexity.

## LangChain ecosystem

While the LangChain framework can be used standalone, it also integrates seamlessly with any LangChain product, giving developers a full suite of tools when building LLM applications.

To improve your LLM application development, pair LangChain with:

- [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview) – Build agents that can reliably handle complex tasks with LangGraph, our low-level agent orchestration framework. LangGraph offers customizable architecture, long-term memory, and human-in-the-loop workflows – and is trusted in production by companies like LinkedIn, Uber, Klarna, and GitLab.
- [Integrations](https://docs.langchain.com/oss/python/integrations/providers/overview) – List of LangChain integrations, including chat & embedding models, tools & toolkits, and more
- [LangSmith](https://www.langchain.com/langsmith) – Helpful for agent evals and observability. Debug poor-performing LLM app runs, evaluate agent trajectories, gain visibility in production, and improve performance over time.
- [LangSmith Deployment](https://docs.langchain.com/langsmith/deployments) – Deploy and scale agents effortlessly with a purpose-built deployment platform for long-running, stateful workflows. Discover, reuse, configure, and share agents across teams – and iterate quickly with visual prototyping in [LangSmith Studio](https://docs.langchain.com/langsmith/studio).
- [Deep Agents](https://github.com/langchain-ai/deepagents) *(new!)* – Build agents that can plan, use subagents, and leverage file systems for complex tasks

## Additional resources

- [Learn](https://docs.langchain.com/oss/python/learn): Use cases, conceptual overviews, and more.
- [API Reference](https://reference.langchain.com/python): Detailed reference on
navigating base packages and integrations for LangChain.
- [LangChain Forum](https://forum.langchain.com): Connect with the community and share all of your technical questions, ideas, and feedback.
- [Chat LangChain](https://chat.langchain.com): Ask questions & chat with our documentation.
- [API Reference](https://reference.langchain.com/python) – Detailed reference on navigating base packages and integrations for LangChain.
- [Contributing Guide](https://docs.langchain.com/oss/python/contributing/overview) – Learn how to contribute to LangChain projects and find good first issues.
- [Code of Conduct](https://github.com/langchain-ai/langchain/blob/master/.github/CODE_OF_CONDUCT.md) – Our community guidelines and standards for participation.
---
LangChain 是一个用于构建由大语言模型（LLM）驱动的应用的框架。它帮助你将可互操作的组件与第三方集成按“链”的方式组合起来，从而简化 AI 应用开发；同时随着底层技术不断演进，保持你的架构决策具有前瞻性与可演进性。

```bash
pip install langchain
```

- 文档：想进一步了解 LangChain，请查看[官方文档](https://docs.langchain.com/oss/python/langchain/overview)。
- 如果你在寻找更强的自定义能力或 Agent 编排，请查看 [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview)，它是一个用于构建可控 Agent 工作流的框架。
- 说明：如果你在寻找 JS/TS 版本，请查看 [LangChain.js](https://github.com/langchain-ai/langchainjs)。

## 为什么使用 LangChain？

LangChain 通过为模型、向量嵌入、向量存储等提供标准化接口，帮助开发者更高效地构建 LLM 应用。

你可以将 LangChain 用于：

- 实时数据增强：轻松将 LLM 连接到多样的数据源与外部/内部系统，依托 LangChain 丰富的生态集成（模型提供商、工具、向量库、检索器等）。
- 模型可互换性：在工程探索过程中可以快捷地替换不同模型，寻找最适合业务的选择。随着行业前沿快速演进，LangChain 的抽象层能帮助你快速适配，而不丢失开发势能。

## LangChain 生态

LangChain 框架可以单独使用，也可以与 LangChain 生态中的其他产品无缝集成，帮助你在构建 LLM 应用时获得完整的一套工具链。

常见的组合方式：

- LangSmith：用于 Agent 评测与可观测性。调试低性能的应用运行、评估 Agent 轨迹、提升生产可见性，并持续改进性能。
- LangGraph：底层 Agent 编排框架，适合构建能可靠处理复杂任务的 Agent（可定制架构、长期记忆、人类在环等），已在 LinkedIn、Uber、Klarna、GitLab 等生产环境中使用。
- LangGraph Platform：面向长时运行、有状态工作流的托管与部署平台。可在团队内发现、复用、配置与共享 Agent，并在 LangGraph Studio 中进行可视化原型迭代。

## 其他资源

- [Learn](https://docs.langchain.com/oss/python/learn)：用例、概念综述等。
- [API 参考](https://reference.langchain.com/python)：导航基础包与生态集成的详细参考。
- [LangChain 论坛](https://forum.langchain.com)：与社区交流技术问题、想法与反馈。
- [Chat LangChain](https://chat.langchain.com)：直接与文档对话，提出问题。

---

# 仓库目录结构概览（Repository Structure Overview）

本仓库采用 Python 多包（monorepo）布局，核心代码与生态集成按照功能拆分为多个独立可发布的子包，源代码主要位于 libs 目录下。下面对主要目录进行说明：

- 根目录（/）
  - AGENTS.md、MIGRATE.md、SECURITY.md、LICENSE、CITATION.cff 等：项目层面的文档与协议。
  - pyproject.toml、uv.lock：monorepo 级别的构建与依赖管理配置。
  - README.md：项目总览（本文件）。

- libs/（子包总目录）
  - cli/
    - 功能：LangChain 命令行工具（langchain-cli）。用于初始化项目、生成模板、开发辅助等。
    - 关键内容：
      - langchain_cli/cli.py：CLI 入口与命令定义。
      - integration_template、package_template、project_template：脚手架模板。
      - namespaces、utils：命名空间与通用工具。
      - scripts/generate_migrations.py：脚本工具。
      - tests/：CLI 的单元/集成测试。
  - core/
    - 功能：langchain_core 包，提供 LangChain 的底层通用抽象与原语。
    - 重要模块（langchain_core/ 下）：
      - agents.py：Agent 协议与核心类型。
      - caches.py：缓存抽象与实现。
      - chat_history.py、chat_loaders.py、chat_sessions.py：聊天会话与历史的抽象。
      - documents/、document_loaders/：文档数据结构与加载器。
      - embeddings/：嵌入（向量化）接口与类型。
      - example_selectors/：Few-shot 样例选择工具。
      - indexing/：索引构建与更新相关原语。
      - language_models/：语言模型与聊天模型的标准接口。
      - messages/：消息与消息类型定义。
      - output_parsers/、outputs/：模型输出的数据类型与解析。
      - prompts/：Prompt 模板与管理。
      - runnables/：可组合的可运行单元（流水线/链）的核心原语。
      - tools/：工具与工具调用协议（与 Agent 交互）。
      - tracers/：追踪与可观测性相关接口。
      - utils/：通用工具函数。
      - vectorstores/：向量数据库与检索抽象。
      - tests/：核心包的基准、单元与集成测试。
  - langchain/
    - 功能：高层 API 与“经典”接口的兼容层。目录下的 langchain_classic/ 保留了历史中的高层模块划分，便于从旧版迁移。
    - langchain_classic/ 主要子模块：
      - agents、chains、llms、prompts、retrievers、runnables、tools 等：经典的 Agent/Chain 架构与高层封装。
      - document_loaders、document_transformers、vectorstores、embeddings 等：面向数据加载/处理与检索的高级封装。
      - callbacks、memory、schema、utils 等：配套的回调、记忆、模式定义与工具集。
      - tests/ 与 scripts/：测试与开发脚本。
  - langchain_v1/
    - 功能：v1 风格 API 的兼容包（迁移过渡用途），包含 agents、chat_models、embeddings、messages、rate_limiters、tools 等子模块及测试。
  - partners/
    - 功能：与生态合作伙伴的官方集成包，按厂商/服务划分为独立可选依赖。
    - 示例子包：anthropic、chroma、deepseek、exa、fireworks、groq、huggingface、mistralai、nomic、ollama、openai、perplexity、prompty、qdrant、xai 等。
    - 结构特征：每个集成包通常包含 langchain_<provider>/ 源码、tests/ 测试、scripts/ 脚本、独立的 pyproject.toml 与 LICENSE/README。
  - standard-tests/
    - 功能：统一的标准化测试套件，用于约束/验证各集成包的行为一致性与兼容性。
  - text-splitters/
    - 功能：文本切分器的独立子包（langchain_text_splitters），封装常用的文本切分算法与策略，供检索/摘要/分块处理使用。

- 其他常见文件/目录（位于各子包内）
  - pyproject.toml、uv.lock：每个子包的独立构建与依赖定义。
  - Makefile：常用开发命令。
  - tests/：单元与集成测试，通常分为 unit_tests/ 与 integration_tests/。
  - scripts/：开发或发布相关脚本。

> 提示：本仓库采用按职责拆分的多包结构。通用抽象在 libs/core 中；面向“经典用法”的高层封装在 libs/langchain；针对旧版本迁移的兼容层在 libs/langchain_v1；第三方生态集成在 libs/partners；特定能力（如文本切分）抽出为独立子包，便于复用与版本管理。
=======
