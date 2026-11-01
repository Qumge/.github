# Qumge — Capability Store for Agents

[English](README.md) | [简体中文](README.zh-CN.md)

**Give your agent a task. Get a complete result.**

[Qumge](https://qumge.com) helps agents find and call hosted capabilities: choose what a task delivers, check its price, and pay from one balance. Developers can turn an existing service or workflow into a capability others can discover and use.

## Use a capability

Find a Cap for your task, inspect its inputs, deliverables and price, then let your agent call it. Managed capabilities are built around a complete, usable result, with job progress and a delivery receipt.

- **[Explore the Capability Store](https://qumge.com/en/caps)**
- **[Install the Qumge skill](https://github.com/Qumge/qumge-skill)** for Claude Code, Cursor, Codex and other skill-compatible agents.
- **[Connect Qumge MCP](https://github.com/Qumge/qumge-mcp)** at `https://qumge.com/mcp`.

```bash
npx skills add Qumge/qumge-skill
```

New to skills? Follow the [installation and first-search guide](https://qumge.com/en/docs/install) for your agent. Searching needs no account or top-up.

## Publish a capability

Bring an existing API, MCP tool, CLI or business workflow. The **qumge-publish** skill helps your coding agent inspect the project, define a complete-result contract, run local preflight, and prepare the integration. Use your existing deployment tools, then register, test and publish through Qumge MCP within your authorization.

```bash
npx skills add Qumge/qumge-skill --full-depth --skill qumge-publish
```

You run the service; Qumge provides discovery, invocation, orders and settlement. Installing the skill does not automatically host a local CLI or publish your project.

[Developer skill and publishing guide →](https://github.com/Qumge/qumge-skill/tree/main/skills/qumge-publish)

## Model access for your agent

Use the same Qumge account and balance to access models through an OpenAI-compatible API. Model inference uses the model API; MCP helps your agent discover available models and capabilities.

[Models and integration documentation →](https://qumge.com/en/docs)

## Open-source entry points

| Repository | Purpose |
|---|---|
| [qumge-skill](https://github.com/Qumge/qumge-skill) | Two skills: use capabilities with **qumge**, or publish them with **qumge-publish**. |
| [qumge-mcp](https://github.com/Qumge/qumge-mcp) | Connection guides and registry metadata for the shared hosted MCP. |
| [qumge-code](https://github.com/Qumge/qumge-code) | A terminal coding agent powered by Qumge models and capabilities. |

[Other Qumge products and projects →](https://qumge.com/en/products)

---

[Website](https://qumge.com) · [Documentation](https://qumge.com/en/docs) · [Agent index](https://qumge.com/llms.txt) · Contact: xnjiang@qumge.com
