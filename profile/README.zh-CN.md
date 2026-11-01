# Qumge — Agent 的能力市场

[English](README.md) | [简体中文](README.zh-CN.md)

**给 Agent 一个任务，拿回一个完整结果。**

[Qumge](https://qumge.com) 帮助 Agent 查找和调用托管能力：先看任务交付什么、价格多少，再从同一份余额中付费。开发者也可以把已有服务或工作流变成能力，让其他 Agent 发现和使用。

## 使用能力

找到适合任务的 Cap，查看输入、交付内容和价格，再让 Agent 调用。托管能力围绕完整、可用的结果设计，提供任务进度和交付回执。

- **[浏览能力市场](https://qumge.com/zh/caps)**
- **[安装 Qumge skill](https://github.com/Qumge/qumge-skill/blob/main/README.zh-CN.md)**，用于 Claude Code、Cursor、Codex 及其他兼容 skill 的 Agent。
- **[连接 Qumge MCP](https://github.com/Qumge/qumge-mcp/blob/main/README.zh-CN.md)**，地址为 `https://qumge.com/mcp`。

```bash
npx skills add Qumge/qumge-skill
```

第一次安装？按[安装与首次搜索指南](https://qumge.com/zh/docs/install)选择你的 Agent。搜索不需要账户或充值。

## 发布能力

带上你已有的 API、MCP 工具、CLI 或业务工作流。**qumge-publish** skill 帮助编程 Agent 分析项目、定义完整结果合同、运行本地预检并准备接入。沿用项目已有工具部署，再通过 Qumge MCP 在你的授权范围内注册、测试和发布。

```bash
npx skills add Qumge/qumge-skill --full-depth --skill qumge-publish
```

你运行自己的服务；Qumge 提供能力发现、调用、订单和结算。安装 skill 不会自动托管本地 CLI，也不会自动发布项目。

[开发者 skill 与发布指南 →](https://github.com/Qumge/qumge-skill/blob/main/README.zh-CN.md#发布流程包含什么)

## 为 Agent 接入大模型

同一个 Qumge 账户和余额，也可以通过兼容 OpenAI 的 API 使用模型。模型推理走模型 API；MCP 帮助 Agent 发现可用模型和能力。

[模型与接入文档 →](https://qumge.com/zh/docs)

## 开源入口

| 仓库 | 用途 |
|---|---|
| [qumge-skill](https://github.com/Qumge/qumge-skill/blob/main/README.zh-CN.md) | 两个 skill：用 **qumge** 使用能力，用 **qumge-publish** 发布能力。 |
| [qumge-mcp](https://github.com/Qumge/qumge-mcp/blob/main/README.zh-CN.md) | 共用托管 MCP 的接入指南与注册元数据。 |
| [qumge-code](https://github.com/Qumge/qumge-code) | 由 Qumge 模型和能力支持的终端编程 Agent。 |

[其他 Qumge 产品与项目 →](https://qumge.com/zh/products)

---

[官网](https://qumge.com) · [文档](https://qumge.com/zh/docs) · [Agent 索引](https://qumge.com/llms.txt) · 联系邮箱：xnjiang@qumge.com
