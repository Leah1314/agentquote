# AgentQuote

AgentQuote helps developers choose the right AI agent route before a task starts.

Instead of optimizing only for the lowest token cost, AgentQuote compares routes by expected quality, developer effort, reliability, privacy, speed, and token efficiency. The goal is to help teams decide when to use Codex, Claude, open models, local models, or a routed agent combination.

Live demo: https://leah1314.github.io/agentquote/

## What it does

- Profiles a developer task by context size, ambiguity, required skills, and review risk.
- Recommends the best agent route for the task, not just the lowest-cost option.
- Compares single-agent and routed-agent strategies across quality, effort, reliability, and token value.
- Explains why the route fits, where it may fail, and when to switch to another route.
- Shows lightweight benchmark evidence from similar task patterns.

## Why it matters

Developers often choose an agent after work has already started. AgentQuote moves that decision earlier, before token spend, workflow lock-in, or quality tradeoffs become expensive.

## Current prototype

This version is a static front-end prototype with simulated scoring and benchmark data. A production version would connect to real task history, model pricing, repository metadata, and post-run feedback to continuously improve recommendations.
