<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SiAgentBuild/SiAgentBuild/main/assets/siagentbuild-hero-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SiAgentBuild/SiAgentBuild/main/assets/siagentbuild-hero-light.svg"/>
  <img src="https://raw.githubusercontent.com/SiAgentBuild/SiAgentBuild/main/assets/siagentbuild-hero-light.svg" width="100%" alt="SiAgentBuild — Building superintelligence"/>
</picture>

<div align="center">
  <a href="https://github.com/SiAgentBuild?tab=followers"><img src="https://img.shields.io/github/followers/SiAgentBuild?style=flat-square&color=007F9E&logo=github" alt="GitHub followers"/></a>
  <a href="https://siagentbuild.github.io"><img src="https://img.shields.io/badge/Notes-siagentbuild.github.io-6046D8?style=flat-square" alt="Blog"/></a>
</div>

## Building superintelligence

我以 **SiAgentBuild** 为工程标识，探索如何把多智能体编排、长期记忆与工具网络组合成可靠、可演进的系统。目标不是堆砌模型调用，而是构建能够协作、记忆并行动的智能体基础设施。

> 把超级智能拆解为今天就可以构建、验证并持续改进的系统能力。

| Agent systems | Memory infrastructure | Tool networks |
|---------------|-----------------------|---------------|
| 异步多智能体后端、角色协作、任务编排与 AG-UI 交互 | 记忆层、上下文工程、检索与服务状态管理 | MCP 工具接入、服务注册、SDK 与运行时生态 |

## Selected builds

| Project | What it does |
|---------|--------------|
| [multi-agent](https://github.com/SiAgentBuild/multi-agent) | 异步多智能体后端，提供可插拔 MCP 工具与 AG-UI 接口 |
| [NacosX](https://github.com/SiAgentBuild/NacosX) | Python 服务的 Nacos 注册、心跳与优雅退出，内置重试和自愈 |
| [httpxodus](https://github.com/SiAgentBuild/httpxodus) | HTTP 生态迁移计划，帮助开源项目从 httpx 迁移到 httpx2 |

## Open source

在 Agent、记忆、MCP 与基础设施项目中持续提交和合并 PR。

<!-- PR-WALL:START -->
<!-- 🤖 此区块由 scripts/update_pr_wall.py + GitHub Actions 自动生成，请勿手改 -->
<!-- 机制：merged 优先 / 仓库 star 排序 / 上限 20 条 / open 超 180 天无响应自动隐藏 -->

| Project | Stars | PR | Status |
|---------|-------|----|--------|
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | ★ 52,560 | [#22557 feat: migrate llama-index-tools-mcp to mcp 2.x](https://github.com/run-llama/llama_index/pull/22557) | ✓ Merged |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#9269 feat: migrate MCP client and AgentOS server to mcp 2.x](https://github.com/agno-agi/agno/pull/9269) | ✓ Merged |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#8956 fix: add team_id filter to get_team_history for nested team support](https://github.com/agno-agi/agno/pull/8956) | ✓ Merged |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#8726 fix: prevent path traversal in FileSystemKnowledge.get_file (#8624)](https://github.com/agno-agi/agno/pull/8726) | ✓ Merged |
| [Finb/Bark](https://github.com/Finb/Bark) | ★ 9,325 | [#377 新增推送 URL 和 Key 二维码展示](https://github.com/Finb/Bark/pull/377) | ✓ Merged |
| [MemMachine/MemMachine](https://github.com/MemMachine/MemMachine) | ★ 3,073 | [#954 feat: use json-repair for LLM output parsing](https://github.com/MemMachine/MemMachine/pull/954) | ✓ Merged |
| [ormar-orm/ormar](https://github.com/ormar-orm/ormar) | ★ 1,801 | [#297 add：SmallInteger()](https://github.com/ormar-orm/ormar/pull/297) | ✓ Merged |
| [tortoise/aerich](https://github.com/tortoise/aerich) | ★ 1,083 | [#187 Enhancement: Inspectdb adds data types and exception handling. Models can also be generated if there are types that cannot be handled.](https://github.com/tortoise/aerich/pull/187) | ✓ Merged |
| [ThinkInAIXYZ/go-mcp](https://github.com/ThinkInAIXYZ/go-mcp) | ★ 677 | [#183 New: Global middleware](https://github.com/ThinkInAIXYZ/go-mcp/pull/183) | ✓ Merged |
| [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | ★ 187,646 | [#14271 refactor(backend): migrate from httpx to httpx2](https://github.com/Significant-Gravitas/AutoGPT/pull/14271) | ○ Open |
| [microsoft/autogen](https://github.com/microsoft/autogen) | ★ 61,474 | [#8020 fix(autogen-ext): migrate MCP integration to mcp 2.x SDK](https://github.com/microsoft/autogen/pull/8020) | ○ Open |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#10078 feat: add X-Accel-Buffering header to SSE streaming responses](https://github.com/agno-agi/agno/pull/10078) | ○ Open |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#10021 feat: migrate core HTTP client from httpx to httpx2](https://github.com/agno-agi/agno/pull/10021) | ○ Open |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#9893 feat: support background execution and reattach in the AG-UI interface](https://github.com/agno-agi/agno/pull/9893) | ○ Open |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#9886 fix: reject duplicate caller-supplied run_id on AgentOS run creation](https://github.com/agno-agi/agno/pull/9886) | ○ Open |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#9544 feat: move dynamic context (datetime/location) from system message to trailing message](https://github.com/agno-agi/agno/pull/9544) | ○ Open |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#9540 fix: emit reasoning delta and completed events for native model reasoning in agent and team streaming](https://github.com/agno-agi/agno/pull/9540) | ○ Open |
| [agno-agi/agno](https://github.com/agno-agi/agno) | ★ 42,803 | [#9253 feat: surface team member activity in AG-UI via ACTIVITY_SNAPSHOT](https://github.com/agno-agi/agno/pull/9253) | ○ Open |
| [lm-sys/FastChat](https://github.com/lm-sys/FastChat) | ★ 39,547 | [#3931 [HTTPXodus] migrate httpx to httpx2 (hard switch; closes #3929)](https://github.com/lm-sys/FastChat/pull/3931) | ○ Open |
| [chroma-core/chroma](https://github.com/chroma-core/chroma) | ★ 29,528 | [#7677 [HTTPXodus] migrate httpx to httpx2 (hard switch)](https://github.com/chroma-core/chroma/pull/7677) | ○ Open |

<div align="left">
  <img src="https://img.shields.io/badge/Merged-9-8957E5?style=flat-square&logo=github" alt="Merged pull requests"/>
  <img src="https://img.shields.io/badge/Open-21-238636?style=flat-square&logo=github" alt="Open pull requests"/>
  <img src="https://img.shields.io/badge/Focus-Agent%20Systems-007F9E?style=flat-square" alt="Focus on agent systems"/>
</div>
<!-- PR-WALL:END -->

## Tools for the work

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python,go,fastapi,docker,git,linux,githubactions&theme=dark"/>
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=python,go,fastapi,docker,git,linux,githubactions&theme=light"/>
  <img src="https://skillicons.dev/icons?i=python,go,fastapi,docker,git,linux,githubactions" alt="Python, Go, FastAPI, Docker, Git, Linux, and GitHub Actions"/>
</picture>

Python、Go 与 FastAPI 用于系统实现；MCP、AG-UI 与 LangChain 用于智能体连接；Docker、Linux、GitHub Actions 与 Nacos 用于交付和运行。

## Engineering signals

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SiAgentBuild/SiAgentBuild/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SiAgentBuild/SiAgentBuild/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/SiAgentBuild/SiAgentBuild/output/github-contribution-grid-snake.svg" width="100%" alt="Contribution snake"/>
</picture>

<details>
<summary>查看语言分布与编码习惯</summary>
<br/>
<img src="https://raw.githubusercontent.com/SiAgentBuild/SiAgentBuild/main/github-metrics.svg" width="100%" alt="Language and engineering metrics"/>
</details>
