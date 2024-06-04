---
title: Cortex Ps
description: Cortex ps command.
slug: "ps"
---

:::warning
🚧 Cortex is under construction.
:::

# `cortex ps`

This command shows the running model and its status.

:::info
This command is compatible with all OpenAI and OpenAI-compatible endpoints.
:::

## Usage

```bash
cortex ps
```

For example, it returns the following table:

```bash
┌─────────┬──────────────────────┬───────────────────┬───────────┬──────────┬─────┬──────┐
│ (index) │ modelId              │ engine            │ status    │ duration │ ram │ vram │
├─────────┼──────────────────────┼───────────────────┼───────────┼──────────┼─────┼──────┤
│ 0       │ 'janhq/tinyllama/1b' │ 'cortex.llamacpp' │ 'running' │ '7s'     │ '-' │ '-'  │
└─────────┴──────────────────────┴───────────────────┴───────────┴──────────┴─────┴──────┘
```
