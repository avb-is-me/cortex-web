---
title: Cortex Run
description: Cortex run command
slug: "run"
---

:::warning
🚧 Cortex is under construction.
:::

# `cortex run`

This command facilitates the initiation of an interactive chat shell with a specified machine learning model.

:::info
This command is compatible with all OpenAI and OpenAI-compatible endpoints.
:::

## Usage

```bash
cortex run MODEL_ID
```

### Options

```
  -t, --thread <thread_id>  Thread Id. If not provided, will create new thread
  -h, --help                display help for command
```

## Command Chain

`cortex run` command is a convenience wrapper that automatically executes a sequence of commands to simplify user interactions:

1. [`cortex start`](/docs/cli/models/start): This command starts the specified model, making it active and ready for interactions.
2. [`cortex chat`](/docs/cli/chat): Following model activation, this command opens an interactive chat shell where users can directly communicate with the model.