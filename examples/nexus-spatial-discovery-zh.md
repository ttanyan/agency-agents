# Nexus Spatial：完整代理机构发现练习

> **练习类型：** 多代理产品发现
> **日期：** 2026 年 3 月 5 日
> **部署代理：** 8 个（并行）
> **持续时间：** 约 10 分钟挂钟时间
> **目的：** 展示从机会识别到全面规划的完整代理编排

---

## 目录

1. [机会](#1-机会)
2. [市场验证](#2-市场验证)
3. [技术架构](#3-技术架构)
4. [品牌战略](#4-品牌战略)
5. [上市与增长](#5-上市与增长)
6. [客户支持蓝图](#6-客户支持蓝图)
7. [UX 研究与设计方向](#7-ux-研究与设计方向)
8. [项目执行计划](#8-项目执行计划)
9. [空间界面架构](#9-空间界面架构)
10. [跨代理综合](#10-跨代理综合)

---

## 1. 机会

### 如何发现的

通过多个来源的 Web 研究，识别出三个汇聚的趋势：

- **AI 基础设施/编排** 是增长最快的软件类别（2026 年 AI 编排市场价值约 135 亿美元，年增长率 22%+）
- **空间计算**（Vision Pro、WebXR）正在成熟，但缺乏杀手级企业应用
- 每个现有的 AI 工作流工具（LangSmith、n8n、Flowise、CrewAI）都是**扁平 2D 仪表板**

### 概念：Nexus Spatial

空间计算中的 AI 代理指挥中心 -- 一个 VisionOS + WebXR 应用程序，提供沉浸式 3D 指挥中心，用于编排、监控和与 AI 代理交互。用户将代理管道可视化为 3D 节点图，在空间面板中监控实时输出，在 3D 空间中通过拖放构建工作流，并在共享空间环境中协作。

### 为什么这个代理机构独特定位

代理机构拥有深厚的空间计算专业知识（XR 开发者、VisionOS 工程师、Metal 专家、界面架构师）以及完整的工程、设计、营销和运营栈 -- 这种组合对于需要空间计算掌握和企业软件严谨性的产品来说非常罕见。

### 来源

- [Profitable SaaS Ideas 2026 (273K+ Reviews)](https://bigideasdb.com/profitable-saas-micro-saas-ideas-2026)
- [2026 SaaS and AI Revolution: 20 Top Trends](https://fungies.io/the-2026-saas-and-ai-revolution-20-top-trends/)
- [Top 21 Underserved Markets 2026](https://mktclarity.com/blogs/news/list-underserved-niches)
- [Fastest Growing Products 2026- G2](https://www.g2.com/best-software-companies/fastest-growing)
- [PwC 2026 AI Business Predictions](https://www.pwc.com/us/en/tech-effect/ai-analytics/ai-predictions.html)

---

## 2. 市场验证

**代理：** 产品趋势研究员

###  verdict：有条件通过 -- 先 2D，后空间

### 市场规模

| 细分市场 | 2026 年价值 | 增长率 |
|---------|-----------|--------|
| AI 编排工具 | 135 亿美元 | 22.3% CAGR |
| 自主 AI 代理 | 85 亿美元 | 45.8% CAGR 到 2030 年 503 亿美元 |
| 扩展现实 | 106.4 亿美元 | 40.95% CAGR |
| 空间计算（广义） | 1700-2200 亿美元 | 根据定义不同 |

### 竞争格局

**AI 代理编排（全部 2D）：**

| 工具 | 优势 | UX 差距 |
|------|----------|--------|
| LangChain/LangSmith | 基于图的编排，39 美元/用户/月 | 扁平仪表板；复杂图在规模下不可读 |
| CrewAI | 10 万 + 开发者，快速执行 | CLI 优先，最小可视化工具 |
| Microsoft Agent Framework | 企业集成 | 嵌入 Azure 门户，无独立 UI |
| n8n | 可视化工作流构建器，20-50 美元/月 | 2D 画布难以处理代理关系 |
| Flowise | 拖放 AI 流 | 仅限于线性流，无多代理监控 |

**"任务控制"产品（新兴，全部 2D）：**
- cmd-deck：AI 编码代理的看板板
- Supervity Agent Command Center：企业可观测性
- OpenClaw Command Center：代理舰队管理
- Mission Control AI：合成工作者管理
- Mission Control HQ：基于小队的协调

**差距：** 产品要么是空间但非 AI 聚焦，要么是 AI 聚焦但扁平 2D。没有产品位于交叉点。

### Vision Pro 现实检验

- 安装基数：全球约 100 万台（销量较发布时下降 95%）
- 苹果已转向轻量级 AR 眼镜
- 仅存在约 3,000 个 VisionOS 特定应用
- **含义：** 不要以 VisionOS 为先导。以 Web 为先导，添加 WebXR，最后才是原生 VisionOS。

### WebXR 作为分发解锁

- Safari 在 2025 年末采用 WebXR Device API
- 2026 年 WebXR 采用率增长 40%
- WebGPU 在浏览器中提供接近原生的渲染
- Android XR 支持 WebXR 和 OpenXR 标准

### 目标角色和定价

| 层级 | 价格 | 目标 |
|------|-------|--------|
| Explorer | 免费 | 开发者、独立构建者（3 个代理，WebXR 查看器） |
| Pro | 99 美元/用户/月 | 小团队（25 个代理，协作） |
| Team | 249 美元/用户/月 | 中型市场 AI 团队（无限代理，分析） |
| Enterprise | 定制（2 千 -1 万美元/月） | 大型企业（SSO、RBAC、本地部署、SLA） |

### 推荐的分阶段策略

1. **第 1-6 个月：** 使用 Three.js 2.5D 功能构建高级 2D Web 仪表板。目标：50 个付费团队，6 万美元 MRR。
2. **第 6-12 个月：** 添加可选 WebXR 空间模式（基于浏览器）。目标：200 个团队，30 万美元 MRR。
3. **第 12-18 个月：** 仅当空间需求得到验证时才开发原生 VisionOS 应用。目标：500 个团队，100 万 + 美元 MRR。

### 关键风险

| 风险 | 严重程度 |
|------|----------|
| Vision Pro 安装基数过小 | 高 |
| "寻找问题的空间解决方案" -- 3D 真的比 2D 好 10 倍吗？ | 高 |
| "任务控制"定位拥挤（已有 5+ 产品） | 中等 |
| 企业空间计算采用仍早期 | 中等 |
| AI 框架间的集成复杂性 | 中等 |

### 来源

- [MarketsandMarkets - AI Orchestration Market](https://www.marketsandmarkets.com/Market-Reports/ai-orchestration-market-148121911.html)
- [Deloitte - AI Agent Orchestration Predictions 2026](https://www.deloitte.com/us/en/insights/industry/technology/technology-media-and-telecom-predictions/2026/ai-agent-orchestration.html)
- [Mordor Intelligence - Extended Reality Market](https://www.mordorintelligence.com/industry-reports/extended-reality-xr-market)
- [Fintool- Vision Pro Production Halted](https://fintool.com/news/apple-vision-pro-production-halt)
- [MadXR - WebXR Browser-Based Experiences 2026](https://www.madxr.io/webxr-browser-immersive-experiences-2026.html)

---

## 3. 技术架构

**代理：** 后端架构师

### 系统概述

一个 8 服务架构，具有清晰的所有权边界，专为水平扩展和提供商无关的 AI 集成而设计。

```
+------------------------------------------------------------------+
|                     客户端层                                       |
|  VisionOS 原生 (Swift/RealityKit)  |  WebXR (React Three Fiber)   |
+------------------------------------------------------------------+
                              |
+-----------------------------v------------------------------------+
|                      API 网关 (Kong / AWS API GW)                 |
|  速率限制 | JWT 验证 | WebSocket 升级 | TLS                       |
+------------------------------------------------------------------+
                              |
+------------------------------------------------------------------+
|                      服务层                                       |
|  Auth | Workspace | Workflow | Orchestration (Rust) |             |
|  Collaboration (Yjs CRDT) | Streaming (WS) | Plugin | Billing    |
+------------------------------------------------------------------+
                              |
+------------------------------------------------------------------+
|                      数据层                                       |
|  PostgreSQL 16 | Redis 7 Cluster | S3 | ClickHouse | NATS        |
+------------------------------------------------------------------+
                              |
+------------------------------------------------------------------+
|                    AI 提供商层                                     |
|  OpenAI | Anthropic | Google | Local Models | Custom Plugins      |
+------------------------------------------------------------------+
```

### 技术栈

| 组件 | 技术 | 理由 |
|-----------|------------|-----------|
| 编排引擎 | **Rust** | 亚毫秒调度、零 GC 暂停、内存安全用于代理沙箱 |
| API 服务 | TypeScript / NestJS | CRUD 密集型服务的开发者速度 |
| VisionOS 客户端 | Swift 6, SwiftUI, RealityKit | 一流的带有 Liquid Glass 的空间计算 |
| WebXR 客户端 | TypeScript, React Three Fiber | 带有 React 组件模型的生产级 WebXR |
| 消息代理 | NATS JetStream | 轻量级、精确一次交付、比 Kafka 简单 |
| 协作 | Yjs (CRDT) + WebRTC | 无冲突的并发 3D 图编辑 |
| 主数据库 | PostgreSQL 16 | JSONB 用于灵活配置，Row-Level Security 用于租户隔离 |

### 核心数据模型

14 个表涵盖：
- **身份和访问：** users, workspaces, team_memberships, api_keys
- **工作流：** workflows, workflow_versions, nodes, edges
- **执行：** executions, execution_steps, step_output_chunks
- **协作：** collaboration_sessions, session_participants
- **凭据：** provider_credentials (AES-256-GCM 加密)
- **计费：** subscriptions, usage_records
- **审计：** audit_log (仅追加)

### 节点类型注册表

```
内置节点类型：
  ai_agent          -- 调用 AI 提供商与提示
  prompt_template   -- 用变量渲染模板
  conditional       -- 基于表达式路由
  transform         -- 沙箱代码片段 (JS/Python)
  input / output   -- 工作流入口/出口点
  human_review     -- 暂停等待人工批准
  loop              -- 重复子图
  parallel_split    -- 扇出到分支
  parallel_join     -- 等待分支
  webhook_trigger   -- 外部 HTTP 触发器
  delay             -- 定时暂停
```

### WebSocket 通道

通过 WSS 实时流式传输：
- 每通道序列号用于排序
- 间隙检测和重播请求
- 当超过 1000 个事件落后时的快照恢复
- 客户端节流用于低功耗设备

### 安全架构

| 层 | 机制 |
|-------|-----------|
| 用户认证 | OAuth 2.0 (GitHub, Google, Apple) + email/password + 可选 TOTP MFA |
| API Keys | SHA-256 哈希，范围限定，可选过期 |
| 服务间 | mTLS via service mesh |
| WebSocket 认证 | 一次性票据，30 秒过期 |
| 凭据存储 | 信封加密 (AES-256-GCM + AWS KMS) |
| 代码沙箱 | gVisor/Firecracker microVMs (无网络，256MB RAM, 30s CPU) |
| 租户隔离 | PostgreSQL Row-Level Security + S3 IAM policies + NATS subject scoping |

### 扩展目标

| 指标 | 第 1 年 | 第 2 年 |
|--------|--------|--------|
| 并发代理执行 | 5,000 | 50,000 |
| WebSocket 连接 | 10,000 | 100,000 |
| P95 API 延迟 | < 150ms | < 100ms |
| P95 WS 事件延迟 | < 80ms | < 50ms |

### MVP 阶段

1. **第 1-6 周：** 2D Web 编辑器，顺序执行，OpenAI + Anthropic 适配器
2. **第 7-12 周：** WebXR 3D 模式，并行执行，手势追踪，RBAC
3. **第 13-20 周：** 多用户协作，VisionOS 原生，计费
4. **第 21-30 周：** 企业 SSO，插件 SDK，SOC 2，扩展加固

---

（由于文件长度限制，上面展示了前 3 个章节的翻译。完整文件包含以下章节：

## 4. 品牌战略
**代理：** 品牌守护者
- 定位声明和类别创建
- 命名验证和商标检查
- 品牌个性和颜色系统
- 设计令牌和 logo 概念

## 5. 上市与增长
**代理：** 增长黑客
- 北极星指标定义
- 定价策略和分层
- 三阶段 GTM 计划
- 增长循环和开源策略
- 收入目标和预算

## 6. 客户支持蓝图
**代理：** 支持响应者
- 支持层级结构
- 优先级定义
- AI 驱动的产品内支持
- 自适应入职流程
- 团队建设和社区策略

## 7. UX 研究与设计方向
**代理：** UX 研究员
- 用户角色和关键发现
- 设计原则
- 导航范式和竞争 UX 总结
- 无障碍要求和研究计划

## 8. 项目执行计划
**代理：** 项目牧羊人
- 35 周时间表和关键里程碑
- 前 6 个冲刺（65 个票）
- 团队分配和 top 5 风险
- 预算细分

## 9. 空间界面架构
**代理：** XR 界面架构师
- 命令剧院布局
- 三层深度系统
- 3D 节点图和 LOD 系统
- 交互模型和协作存在
- 过渡编排和舒适措施

## 10. 跨代理综合
- 所有 8 个代理的一致观点
- 需要解决的关键张力
- 此练习展示的内容

---

**注意：** 这是完整多代理产品发现练习的摘要翻译。如需查看完整的详细输出（包括完整的 SQL schema、设计令牌、代码示例等），请参考原始英文版本或联系维护者获取完整翻译。

### 关键要点

这个发现文档由 8 个并行运行的专业代理生成，每个代理都为共同目标带来深厚的领域专业知识。代理独立地达成一致的结论，同时揭示特定领域的洞察，这些洞察是任何单一通才难以产生的：

- **产品趋势研究员**发现了令人清醒的 Vision Pro 销售数据，重新构建了整个战略
- **后端架构师**设计了没有营销导向团队会考虑的 Rust 编排引擎
- **品牌守护者**创建了一个类别（"SpatialAIOps"），而不是在现有类别中竞争
- **UX 研究员**识别出空间计算为参数任务创造摩擦 -- 这是一个反直觉的发现
- **XR 界面架构师**设计了"数据流向你"的拓扑，映射到自然的空间认知
- **项目牧羊人**识别了可能破坏整个时间表的三个关键瓶颈角色
- **增长黑客**设计了特定于空间计算内在可分享性的病毒循环
- **支持响应者**将产品自己的 AI 能力转化为支持差异化

结果是一个全面的、跨职能的产品计划，可以作为实际开发的基础 -- 由 AI 代理机构在单次会话中协同工作生成。
