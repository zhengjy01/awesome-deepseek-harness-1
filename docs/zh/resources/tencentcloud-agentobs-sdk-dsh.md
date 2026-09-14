---
title: "tencentcloud-agentobs-sdk-dsh"
description: "tencentcloud-agentobs-sdk-dsh 是一个 DeepSeek Harness (DSH) 可观测插件，直接将 GenAI trace 数据上报到腾讯云日志服务 (CLS)。  它观察 DSH 原生的 session、agent loop、LLM stream 和 tool 生命周期，将其转换为 腾讯云AI Agent可观测规范的 5 层 span 层级模型（entry → agent → step → chat → tool），并通过 tencentcloud-cls-sdk-js 直接上报到 CLS，无需额外部署 OTLP 收集器或 sidecar。"
keywords: "tencentcloud-agentobs-sdk-dsh, vision, plugin, coding, multi-agent, deepseek harness, dsh"
---
# tencentcloud-agentobs-sdk-dsh

> ⭐ **13** · ✅ 活跃 · 插件

| | | | |
|---|---|---|---|
| 类型 | 插件 | 分类 | 视觉与多模态 |
| 星数 | ⭐ 13 | 状态 | ✅ 活跃 |
| 作者 | [TencentCloud](https://github.com/TencentCloud) | 更新时间 | — |

## 一句话介绍

> tencentcloud-agentobs-sdk-dsh 是一个 DeepSeek Harness (DSH) 可观测插件，直接将 GenAI trace 数据上报到腾讯云日志服务 (CLS)。  它观察 DSH 原生的 session、agent loop、LLM stream 和 tool 生命周期，将其转换为 腾讯云AI Agent可观测规范的 5 层 span 层级模型（entry → agent → step → chat → tool），并通过 tencentcloud-cls-sdk-js 直接上报到 CLS，无需额外部署 OTLP 收集器或 sidecar。

## 详细介绍

tencentcloud-agentobs-sdk-dsh 是一个 DeepSeek Harness (DSH) 可观测插件，直接将 GenAI trace 数据上报到腾讯云日志服务 (CLS)。  它观察 DSH 原生的 session、agent loop、LLM stream 和 tool 生命周期，将其转换为 腾讯云AI Agent可观测规范的 5 层 span 层级模型（entry → agent → step → chat → tool），并通过 tencentcloud-cls-sdk-js 直接上报到 CLS，无需额外部署 OTLP 收集器或 sidecar。

## 🔗 链接

- [GitHub 仓库](https://github.com/TencentCloud/tencentcloud-agentobs-sdk-dsh)
- [完整 README](https://github.com/TencentCloud/tencentcloud-agentobs-sdk-dsh#readme)
- [返回tencentcloud-agentobs-sdk-dsh所在分类](../plugins.md)
