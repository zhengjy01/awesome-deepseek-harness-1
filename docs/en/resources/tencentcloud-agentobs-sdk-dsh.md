---
title: "tencentcloud-agentobs-sdk-dsh"
description: "tencentcloud-agentobs-sdk-dsh 是一个 DeepSeek Harness (DSH) 可观测插件，直接将 GenAI trace 数据上报到腾讯云日志服务 (CLS)。  它观察 DSH 原生的 session、agent loop、LLM stream 和 tool 生命周期，将其转换为 腾讯云AI Agent可观测规范的 5 层 span 层级模型（entry → agent → step → chat → tool），并通过 tencentcloud-cls-sdk-js 直接上报到 CLS，无需额外部署 OTLP 收集器或 sidecar。"
keywords: "tencentcloud-agentobs-sdk-dsh, vision, plugin, coding, multi-agent, deepseek harness, dsh"
---
# tencentcloud-agentobs-sdk-dsh

> ⭐ **13** · ✅ active · plugin

| | | | |
|---|---|---|---|
| Type | plugin | Category | Vision & multimodal |
| Stars | ⭐ 13 | Status | ✅ active |
| Author | [TencentCloud](https://github.com/TencentCloud) | Updated | — |

## One-liner

> tencentcloud-agentobs-sdk-dsh 是一个 DeepSeek Harness (DSH) 可观测插件，直接将 GenAI trace 数据上报到腾讯云日志服务 (CLS)。  它观察 DSH 原生的 session、agent loop、LLM stream 和 tool 生命周期，将其转换为 腾讯云AI Agent可观测规范的 5 层 span 层级模型（entry → agent → step → chat → tool），并通过 tencentcloud-cls-sdk-js 直接上报到 CLS，无需额外部署 OTLP 收集器或 sidecar。

## About

tencentcloud-agentobs-sdk-dsh 是一个 DeepSeek Harness (DSH) 可观测插件，直接将 GenAI trace 数据上报到腾讯云日志服务 (CLS)。  它观察 DSH 原生的 session、agent loop、LLM stream 和 tool 生命周期，将其转换为 腾讯云AI Agent可观测规范的 5 层 span 层级模型（entry → agent → step → chat → tool），并通过 tencentcloud-cls-sdk-js 直接上报到 CLS，无需额外部署 OTLP 收集器或 sidecar。

## 🔗 Links

- [GitHub Repository](https://github.com/TencentCloud/tencentcloud-agentobs-sdk-dsh)
- [Full README](https://github.com/TencentCloud/tencentcloud-agentobs-sdk-dsh#readme)
- [Back to the Plugins list](../plugins.md)
