# 🎭 The Agency：随时改变您工作流程的 AI 专家团队

> **一个完整的 AI 代理机构，尽在您指尖** - 从前端魔法师到 Reddit 社区忍者，从奇思妙想注入者到现实检验者。每个代理都是具有个性、流程和可靠交付成果的专业专家。

[![GitHub stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=social)](https://github.com/msitarzewski/agency-agents)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?logo=github)](https://github.com/sponsors/msitarzewski)

---

## 🚀 这是什么？

诞生于 Reddit 讨论和数月的迭代，**The Agency** 是一个不断增长的精心制作的 AI 代理个性集合。每个代理都具备：

- **🎯 专业化**：在其领域拥有深厚的专业知识（而非通用提示模板）
- **🧠 个性驱动**：独特的声音、沟通风格和方法
- **📋 交付导向**：真实的代码、流程和可衡量的成果
- **✅ 生产就绪**：经过实战检验的工作流程和成功指标

**可以这样理解**：组建您的梦想团队，只不过他们是永不睡觉、从不抱怨、始终交付的 AI 专家。

---

## ⚡ 快速开始

### 选项 1：与 Claude Code 一起使用（推荐）

```bash
# 将代理复制到您的 Claude Code 目录
cp -r agency-agents/* ~/.claude/agents/

# 现在在您的 Claude Code 会话中激活任何代理：
# "嘿 Claude，激活前端开发者模式并帮我构建一个 React 组件"
```

### 选项 2：用作参考

每个代理文件包含：
- 身份和个性特征
- 核心使命和工作流程
- 带有代码示例的技术交付物
- 成功指标和沟通风格

浏览下方的代理，复制/调整您需要的代理！

### 选项 3：与其他工具一起使用（Cursor、Aider、Windsurf、Gemini CLI、OpenCode）

```bash
# 步骤 1 -- 为所有支持的工具生成交付文件
./scripts/convert.sh

# 步骤 2 -- 交互式安装（自动检测您已安装的工具）
./scripts/install.sh

# 或直接针对特定工具
./scripts/install.sh --tool cursor
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
```

详见下方的 [多工具集成](#-多工具集成) 部分。

---

## 🎨 代理机构名册

### 💻 工程部门

构建未来，一次提交一步。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 🎨 [前端开发者](engineering/engineering-frontend-developer.md) | React/Vue/Angular, UI 实现，性能 | 现代 Web 应用、像素级完美 UI、Core Web Vitals 优化 |
| 🏗️ [后端架构师](engineering/engineering-backend-architect.md) | API 设计、数据库架构、可扩展性 | 服务端系统、微服务、云基础设施 |
| 📱 [移动应用构建器](engineering/engineering-mobile-app-builder.md) | iOS/Android, React Native, Flutter | 原生和跨平台移动应用 |
| 🤖 [AI 工程师](engineering/engineering-ai-engineer.md) | ML 模型、部署、AI 集成 | 机器学习功能、数据管道、AI 驱动的应用 |
| 🚀 [DevOps 自动化器](engineering/engineering-devops-automator.md) | CI/CD、基础设施自动化、云运维 | 管道开发、部署自动化、监控 |
| ⚡ [快速原型师](engineering/engineering-rapid-prototyper.md) | 快速 POC 开发、MVP | 快速概念验证、黑客马拉松项目、快速迭代 |
| 💎 [高级开发者](engineering/engineering-senior-developer.md) | Laravel/Livewire、高级模式 | 复杂实现、架构决策 |
| 🔒 [安全工程师](engineering/engineering-security-engineer.md) | 威胁建模、安全代码审查、安全架构 | 应用安全、漏洞评估、安全 CI/CD |

### 🎨 设计部门

让事物更美丽、可用和愉悦。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 🎯 [UI 设计师](design/design-ui-designer.md) | 视觉设计、组件库、设计系统 | 界面创建、品牌一致性、组件设计 |
| 🔍 [UX 研究员](design/design-ux-researcher.md) | 用户测试、行为分析、研究 | 理解用户、可用性测试、设计洞察 |
| 🏛️ [UX 架构师](design/design-ux-architect.md) | 技术架构、CSS 系统、实现 | 对开发者友好的基础、实现指导 |
| 🎭 [品牌守护者](design/design-brand-guardian.md) | 品牌识别、一致性、定位 | 品牌战略、识别开发、指南 |
| 📖 [视觉叙事者](design/design-visual-storyteller.md) | 视觉叙事、多媒体内容 | 引人入胜的视觉故事、品牌故事讲述 |
| ✨ [奇思妙想注入者](design/design-whimsy-injector.md) | 个性、愉悦感、俏皮互动 | 添加快乐、微互动、彩蛋、品牌个性 |
| 📷 [图像提示工程师](design/design-image-prompt-engineer.md) | AI 图像生成提示、摄影 | Midjourney、DALL-E、Stable Diffusion 的摄影提示 |

### 📢 营销部门

一次一个真实的互动，发展您的受众。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 🚀 [增长黑客](marketing/marketing-growth-hacker.md) | 快速用户获取、病毒循环、实验 | 爆炸式增长、用户获取、转化优化 |
| 📝 [内容创作者](marketing/marketing-content-creator.md) | 多平台内容、编辑日历 | 内容战略、文案、品牌故事讲述 |
| 🐦 [Twitter 互动者](marketing/marketing-twitter-engager.md) | 实时互动、思想领导力 | Twitter 战略、LinkedIn 活动、专业社交 |
| 📱 [TikTok 策略师](marketing/marketing-tiktok-strategist.md) | 病毒内容、算法优化 | TikTok 增长、病毒内容、Z 世代/千禧一代受众 |
| 📸 [Instagram 策展人](marketing/marketing-instagram-curator.md) | 视觉故事讲述、社区建设 | Instagram 战略、美学开发、视觉内容 |
| 🤝 [Reddit 社区建设者](marketing/marketing-reddit-community-builder.md) | 真实互动、价值驱动内容 | Reddit 战略、社区信任、真实营销 |
| 📱 [应用商店优化师](marketing/marketing-app-store-optimizer.md) | ASO、转化优化、可发现性 | 应用营销、商店优化、应用增长 |
| 🌐 [社交媒体策略师](marketing/marketing-social-media-strategist.md) | 跨平台战略、活动 | 整体社交战略、多平台活动 |
| 📕 [小红书专家](marketing/marketing-xiaohongshu-specialist.md) | 生活方式内容、趋势驱动战略 | 小红书增长、美学叙事、Z 世代受众 |
| 💬 [微信公众号管理员](marketing/marketing-wechat-official-account.md) | 订阅者互动、内容营销 | 微信 OA 战略、社区建设、转化优化 |
| 🧠 [知乎策略师](marketing/marketing-zhihu-strategist.md) | 思想领导力、知识驱动的互动 | 知乎权威建设、问答战略、潜在客户开发 |

### 📊 产品部门

在正确的时间构建正确的东西。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 🎯 [冲刺优先级排序器](product/product-sprint-prioritizer.md) | 敏捷规划、功能优先级 | 冲刺规划、资源分配、待办事项管理 |
| 🔍 [趋势研究员](product/product-trend-researcher.md) | 市场情报、竞争分析 | 市场研究、机会评估、趋势识别 |
| 💬 [反馈综合师](product/product-feedback-synthesizer.md) | 用户反馈分析、洞察提取 | 反馈分析、用户洞察、产品优先级 |

### 🎬 项目管理部门

让列车准时运行（且在预算内）。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 🎬 [制片厂制片人](project-management/project-management-studio-producer.md) | 高层协调、组合管理 | 多项目监督、战略对齐、资源分配 |
| 🐑 [项目牧羊人](project-management/project-management-project-shepherd.md) | 跨职能协调、时间线管理 | 端到端项目协调、利益相关者管理 |
| ⚙️ [制片厂运营](project-management/project-management-studio-operations.md) | 日常效率、流程优化 | 卓越运营、团队支持、生产力 |
| 🧪 [实验追踪器](project-management/project-management-experiment-tracker.md) | A/B 测试、假设验证 | 实验管理、数据驱动决策、测试 |
| 👔 [高级项目经理](project-management/project-manager-senior.md) | 现实范围界定、任务转换 | 将规格转换为任务、范围管理 |

### 🧪 测试部门

破坏东西，这样用户就不必了。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 📸 [证据收集器](testing/testing-evidence-collector.md) | 基于截图的 QA、视觉证明 | UI 测试、视觉验证、bug 文档 |
| 🔍 [现实检验者](testing/testing-reality-checker.md) | 基于证据的认证、质量门 | 生产就绪、质量批准、发布认证 |
| 📊 [测试结果分析师](testing/testing-test-results-analyzer.md) | 测试评估、指标分析 | 测试输出分析、质量洞察、覆盖率报告 |
| ⚡ [性能基准测试员](testing/testing-performance-benchmarker.md) | 性能测试、优化 | 速度测试、负载测试、性能调优 |
| 🔌 [API 测试员](testing/testing-api-tester.md) | API 验证、集成测试 | API 测试、端点验证、集成 QA |
| 🛠️ [工具评估员](testing/testing-tool-evaluator.md) | 技术评估、工具选择 | 评估工具、软件推荐、技术决策 |
| 🔄 [工作流程优化器](testing/testing-workflow-optimizer.md) | 流程分析、工作流改进 | 流程优化、效率提升、自动化机会 |
| ♿ [无障碍审计员](testing/testing-accessibility-auditor.md) | WCAG 审计、辅助技术测试 | 无障碍合规性、屏幕阅读器测试、包容性设计验证 |

### 🛟 支持部门

运营的支柱。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 💬 [支持响应者](support/support-support-responder.md) | 客户服务、问题解决 | 客户支持、用户体验、支持运营 |
| 📊 [分析报告员](support/support-analytics-reporter.md) | 数据分析、仪表板、洞察 | 商业智能、KPI 追踪、数据可视化 |
| 💰 [财务追踪器](support/support-finance-tracker.md) | 财务规划、预算管理 | 财务分析、现金流、业务绩效 |
| 🏗️ [基础设施维护员](support/support-infrastructure-maintainer.md) | 系统可靠性、性能优化 | 基础设施管理、系统运营、监控 |
| ⚖️ [法律合规检查员](support/support-legal-compliance-checker.md) | 合规性、法规、法律审查 | 法律合规、监管要求、风险管理 |
| 📑 [执行摘要生成器](support/support-executive-summary-generator.md) | C 层级沟通、战略摘要 | 执行报告、战略沟通、决策支持 |

### 🥽 空间计算部门

构建沉浸式未来。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 🏗️ [XR 界面架构师](spatial-computing/xr-interface-architect.md) | 空间交互设计、沉浸式 UX | AR/VR/XR 界面设计、空间计算 UX |
| 💻 [macOS 空间/Metal 工程师](spatial-computing/macos-spatial-metal-engineer.md) | Swift、Metal、高性能 3D | macOS 空间计算、Vision Pro 原生应用 |
| 🌐 [XR 沉浸式开发者](spatial-computing/xr-immersive-developer.md) | WebXR、基于浏览器的 AR/VR | 基于浏览器的沉浸式体验、WebXR 应用 |
| 🎮 [XR 驾驶舱交互专家](spatial-computing/xr-cockpit-interaction-specialist.md) | 驾驶舱控制、沉浸式系统 | 驾驶舱控制系统、沉浸式控制界面 |
| 🍎 [visionOS 空间工程师](spatial-computing/visionos-spatial-engineer.md) | Apple Vision Pro 开发 | Vision Pro 应用、空间计算体验 |
| 🔌 [终端集成专家](spatial-computing/terminal-integration-specialist.md) | 终端集成、命令行工具 | CLI 工具、终端工作流、开发者工具 |

### 🎯 专业部门

不适合归类的独特专家。

| 代理 | 专业领域 | 使用时机 |
|-------|-----------|-------------|
| 🎭 [代理编排器](specialized/agents-orchestrator.md) | 多代理协调、工作流管理 | 需要多代理协调的复杂项目 |
| 📊 [数据分析报告员](specialized/data-analytics-reporter.md) | 商业智能、数据洞察 | 深度数据分析、业务指标、战略洞察 |
| 🔍 [LSP/索引工程师](specialized/lsp-index-engineer.md) | 语言服务协议、代码智能 | 代码智能系统、LSP 实现、语义索引 |
| 📥 [销售数据提取代理](specialized/sales-data-extraction-agent.md) | Excel 监控、销售指标提取 | 销售数据摄取、MTD/YTD/年度指标 |
| 📈 [数据整合代理](specialized/data-consolidation-agent.md) | 销售数据聚合、仪表板报告 | 区域总结、代表绩效、渠道快照 |
| 📬 [报告分发代理](specialized/report-distribution-agent.md) | 自动报告分发 | 基于区域的报告分发、定时发送 |
| 🔐 [代理身份与信任架构师](specialized/agentic-identity-trust.md) | 代理身份、认证、信任验证 | 多代理身份系统、代理授权、审计跟踪 |

---

## 🎯 现实世界使用案例

### 场景 1：构建初创公司 MVP

**您的团队**：
1. 🎨 **前端开发者** - 构建 React 应用
2. 🏗️ **后端架构师** - 设计 API 和数据库
3. 🚀 **增长黑客** - 规划用户获取
4. ⚡ **快速原型师** - 快速迭代周期
5. 🔍 **现实检验者** - 确保发布前的质量

**结果**：在每个阶段都能以更快的速度交付，并获得专业化的专业知识。

---

### 场景 2：营销活动发布

**您的团队**：
1. 📝 **内容创作者** - 开发活动内容
2. 🐦 **Twitter 互动者** - Twitter 战略和执行
3. 📸 **Instagram 策展人** - 视觉内容和故事
4. 🤝 **Reddit 社区建设者** - 真实的社区互动
5. 📊 **分析报告员** - 追踪和优化绩效

**结果**：具有平台特定专业知识的多渠道协调活动。

---

### 场景 3：企业功能开发

**您的团队**：
1. 👔 **高级项目经理** - 范围和任务规划
2. 💎 **高级开发者** - 复杂实现
3. 🎨 **UI 设计师** - 设计系统和组件
4. 🧪 **实验追踪器** - A/B 测试规划
5. 📸 **证据收集器** - 质量验证
6. 🔍 **现实检验者** - 生产就绪

**结果**：具有质量门和文档的企业级交付。

---

### 场景 4：完整代理机构产品发现

**您的团队**：所有 8 个部门并行工作于单一任务。

查看 **[Nexus 空间发现练习](examples/nexus-spatial-discovery-zh.md)** -- 一个完整的示例，其中同时部署了 8 个代理（产品趋势研究员、后端架构师、品牌守护者、增长黑客、支持响应者、UX 研究员、项目牧羊人和 XR 界面架构师），以评估软件机会并生成统一的产品计划，涵盖市场验证、技术架构、品牌战略、上市策略、支持系统、UX 研究、项目执行和空间 UI 设计。

**结果**：在单次会话中生成了全面的跨职能产品蓝图。[更多示例](examples/)。

---

## 🤝 贡献

我们欢迎贡献！以下是您提供帮助的方式：

### 添加新代理

1. Fork 仓库
2. 在适当的类别中创建新的代理文件
3. 遵循代理模板结构：
   - 带有名称、描述、颜色的 frontmatter
   - 身份和记忆部分
   - 核心使命
   - 关键规则（特定领域）
   - 带有示例的技术交付物
   - 工作流程
   - 成功指标
4. 提交您的代理 PR

### 改进现有代理

- 添加现实世界的例子
- 增强代码示例
- 更新成功指标
- 改进工作流程

### 分享您的成功故事

您成功使用过这些代理吗？在 [Discussions](https://github.com/msitarzewski/agency-agents/discussions) 中分享您的故事！

---

## 📖 代理设计哲学

每个代理的设计都包含：

1. **🎭 强烈的个性**：不是通用模板 - 真正的角色和声音
2. **📋 清晰的交付物**：具体的输出，不是模糊的指导
3. **✅ 成功指标**：可衡量的结果和质量标准
4. **🔄 经验证的工作流程**：有效的逐步流程
5. **💡 学习记忆**：模式识别和持续改进

---

## 🎁 这是什么特别之处？

### 与通用 AI 提示不同：
- ❌ 通用的"充当开发者"提示
- ✅ 具有个性和流程的深度专业化

### 与提示库不同：
- ❌ 一次性提示集合
- ✅ 具有工作流程和交付物的综合代理系统

### 与 AI 工具不同：
- ❌ 无法自定义的黑盒工具
- ✅ 透明、可 fork、可适应的代理个性

---

## 🎨 代理个性亮点

> "我不仅仅是测试你的代码 - 我默认会发现 3-5 个问题，并且需要所有事情的视觉证明。"
>
> -- **证据收集器** (测试部门)

> "你不是在 Reddit 上做营销 - 你正在成为一个有价值的社区成员，碰巧代表一个品牌。"
>
> -- **Reddit 社区建设者** (营销部门)

> "每个有趣的元素都必须服务于功能或情感目的。设计增强而不是分散注意力的愉悦感。"
>
> -- **奇思妙想注入者** (设计部门)

> "让我添加一个庆祝动画，通过 40% 减少任务完成焦虑"
>
> -- **奇思妙想注入者** (在 UX 审查期间)

---

## 📊 统计数据

- 🎭 **61 个专业代理**分布在 9 个部门
- 📝 **10,000+ 行**个性、流程和代码示例
- ⏱️ **数月的迭代**来自实际使用
- 🌟 **在生产环境中经过实战检验**
- 💬 **前 12 小时内收到 50+ 请求**在 Reddit 上

---

## 🔌 多工具集成

The Agency 原生支持 Claude Code，并提供转换 + 安装脚本，因此您可以在每个主要的代理编码工具中使用相同的代理。

### 支持的工具

- **[Claude Code](https://claude.ai/code)** — 原生 `.md` 代理，无需转换 → `~/.claude/agents/`
- **[Antigravity](https://github.com/google-gemini/antigravity)** — 每个代理一个 `SKILL.md` → `~/.gemini/antigravity/skills/`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** — 扩展 + `SKILL.md` 文件 → `~/.gemini/extensions/agency-agents/`
- **[OpenCode](https://opencode.ai)** — `.md` 代理文件 → `.opencode/agent/`
- **[Cursor](https://cursor.sh)** — `.mdc` 规则文件 → `.cursor/rules/`
- **[Aider](https://aider.chat)** — 单个 `CONVENTIONS.md` → `./CONVENTIONS.md`
- **[Windsurf](https://codeium.com/windsurf)** — 单个 `.windsurfrules` → `./.windsurfrules`

---

### ⚡ 快速安装

**步骤 1 -- 生成交付文件：**
```bash
./scripts/convert.sh
```

**步骤 2 -- 安装（交互式，自动检测您的工具）：**
```bash
./scripts/install.sh
```

安装程序会扫描您的系统以查找已安装的工具，显示复选框 UI，并让您准确选择要安装的内容：

```
  +------------------------------------------------+
  |   The Agency -- 工具安装程序                   |
  +------------------------------------------------+

  系统扫描：[*] = 在此机器上检测到

  [x]  1)  [*]  Claude Code     (claude.ai/code)
  [x]  2)  [*]  Antigravity     (~/.gemini/antigravity)
  [ ]  3)  [ ]  Gemini CLI     (gemini extension)
  [ ]  4)  [ ]  OpenCode        (opencode.ai)
  [x]  5)  [*]  Cursor         (.cursor/rules)
  [ ]  6)  [ ]  Aider           (CONVENTIONS.md)
  [ ]  7)  [ ]  Windsurf        (.windsurfrules)

  [1-7] 切换   [a] 全部   [n] 无   [d] 已检测
  [Enter] 安装   [q] 退出
```

**或直接安装特定工具：**
```bash
./scripts/install.sh --tool cursor
./scripts/install.sh --tool opencode
./scripts/install.sh --tool antigravity
```

**非交互式（CI/脚本）：**
```bash
./scripts/install.sh --no-interactive --tool all
```

---

### 特定工具说明

<details>
<summary><strong>Claude Code</strong></summary>

代理直接从 repo 复制到 `~/.claude/agents/` -- 无需转换。

```bash
./scripts/install.sh --tool claude-code
```

然后在 Claude Code 中激活：
```
使用前端开发者代理审查此组件。
```

详见 [integrations/claude-code/README.md](integrations/claude-code/README-zh.md)。
</details>

<details>
<summary><strong>Antigravity (Gemini)</strong></summary>

每个代理成为 `~/.gemini/antigravity/skills/agency-<slug>/` 中的技能。

```bash
./scripts/install.sh --tool antigravity
```

在带有 Antigravity 的 Gemini 中激活：
```
@agency-frontend-developer 审查此 React 组件
```

详见 [integrations/antigravity/README.md](integrations/antigravity/README-zh.md)。
</details>

<details>
<summary><strong>Gemini CLI</strong></summary>

作为 Gemini CLI 扩展安装，包含 61 个技能 + 清单。

```bash
./scripts/install.sh --tool gemini-cli
```

详见 [integrations/gemini-cli/README.md](integrations/gemini-cli/README-zh.md)。
</details>

<details>
<summary><strong>OpenCode</strong></summary>

代理放置在项目根目录的 `.opencode/agent/` 中（项目范围）。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool opencode
```

或全局安装：
```bash
mkdir -p ~/.config/opencode/agent
cp integrations/opencode/agent/*.md ~/.config/opencode/agent/
```

在 OpenCode 中激活：
```
使用后端架构师代理设计此 API。
```

详见 [integrations/opencode/README.md](integrations/opencode/README-zh.md)。
</details>

<details>
<summary><strong>Cursor</strong></summary>

每个代理成为 `.cursor/rules/` 中的 `.mdc` 规则文件。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool cursor
```

当 Cursor 检测到项目中的规则时会自动应用它们。明确引用它们：
```
使用 @security-engineer 规则审查此代码。
```

详见 [integrations/cursor/README.md](integrations/cursor/README-zh.md)。
</details>

<details>
<summary><strong>Aider</strong></summary>

所有代理被编译成单个 `CONVENTIONS.md` 文件，Aider 会自动读取该文件。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool aider
```

然后在您的 Aider 会话中引用代理：
```
使用前端开发者代理重构此组件。
```

详见 [integrations/aider/README.md](integrations/aider/README-zh.md)。
</details>

<details>
<summary><strong>Windsurf</strong></summary>

所有代理被编译到项目根目录的 `.windsurfrules` 中。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool windsurf
```

在 Windsurf 的 Cascade 中引用代理：
```
使用现实检验者代理验证这是生产就绪的。
```

详见 [integrations/windsurf/README.md](integrations/windsurf/README-zh.md)。
</details>

---

### 更改后重新生成

当您添加新代理或编辑现有代理时，重新生成所有集成交付文件：

```bash
./scripts/convert.sh       # 重新生成所有
./scripts/convert.sh --tool cursor  # 重新生成一个工具
```

---

## 🗺️ 路线图

- [ ] 交互式代理选择器 Web 工具
- [x] 多代理工作流程示例 -- 见 [examples/](examples/)
- [x] 多工具集成脚本 (Claude Code, Antigravity, Gemini CLI, OpenCode, Cursor, Aider, Windsurf)
- [ ] 代理设计视频教程
- [ ] 社区代理市场
- [ ] 用于项目匹配的"代理性格测试"
- [ ] "每周代理"展示系列

---

## 🌐 社区翻译和本地化

社区维护的翻译和区域改编。这些是独立维护的 -- 请参阅每个 repo 以了解覆盖范围和版本兼容性。

| 语言 | 维护者 | 链接 | 备注 |
|----------|-----------|------|-------|
| 🇨🇳 简体中文 (zh-CN) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) | 26 个翻译的代理 + 4 个中国市场代理 |

想添加翻译？开一个 issue，我们会在这里链接它。

---

## 📜 许可证

MIT 许可证 - 免费用于商业或个人用途。感谢署名但不是强制的。

---

## 🙏 致谢

诞生于关于 AI 代理专业化的 Reddit 讨论。感谢社区的反馈、请求和灵感。

特别感谢在前 12 小时内请求此内容的 50+ Reddit 用户 - 你们证明了对真正专业化 AI 代理系统的需求。

---

## 💬 社区

- **GitHub Discussions**: [分享您的成功故事](https://github.com/msitarzewski/agency-agents/discussions)
- **Issues**: [报告错误或请求功能](https://github.com/msitarzewski/agency-agents/issues)
- **Reddit**: 在 r/ClaudeAI 加入对话
- **Twitter/X**: 使用 #TheAgency 分享

---

## 🚀 开始使用

1. **浏览** 上方的代理并找到满足您需求的专家
2. **复制** 代理到 `~/.claude/agents/` 以获得 Claude Code 集成
3. **激活** 代理，方法是在 Claude 对话中引用它们
4. **自定义** 代理个性和工作流程以满足您的特定需求
5. **分享** 您的结果并为社区做出贡献

---

<div align="center">

**🎭 The Agency：您的 AI 梦之队正在等待 🎭**

[⭐ 给这个 repo 加星](https://github.com/msitarzewski/agency-agents) • [🍴 Fork](https://github.com/msitarzewski/agency-agents/fork) • [🐛 报告问题](https://github.com/msitarzewski/agency-agents/issues) • [❤️ 赞助](https://github.com/sponsors/msitarzewski)

由社区制作，为社区服务 ❤️

</div>
