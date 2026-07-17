# AgentQuote

AgentQuote is a pre-run advisor for AI coding agents.

It helps developers decide whether a task should use Codex, Claude, an open model, a local workflow, or a staged route before spending time, tokens, and review effort.

Live demo: https://leah1314.github.io/agentquote/

## What it does

- Reads the task type, project context, ambiguity, privacy risk, and review capacity.
- Recommends a practical agent setup instead of defaulting to the lowest-cost model.
- Compares single-agent and staged-agent routes across outcome fit, token value, review effort, and reliability.
- Explains why a route fits, what to watch for, and when to switch.
- Shows the decision signals that would become real telemetry in a production version.

## Why it matters

Developers often choose an agent after the work has already started. AgentQuote moves that decision earlier, before workflow lock-in, context exposure, or quality tradeoffs become expensive.

## Current prototype

This is a static front-end prototype. A production version would connect to repository metadata, model pricing, run history, evaluation results, and post-run review feedback.
