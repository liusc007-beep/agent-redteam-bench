# Agent Red-Team Bench

This repository is the research project for agent red-team evaluation described in my application.

## What this is
A small benchmark for testing AI agents under adversarial conditions. The goal is to measure how agents handle risky instructions, misleading tool outputs, and unsafe requests, so we can make them safer.

## Scope
- Prompt-injection resistance
- Tool-use safety (do not run unsafe actions, do not leak credentials or private data)
- Refusal and safe completion on disallowed or risky requests
- Clear scoring: pass / fail per case, with reasons recorded

## What this is not
This is defensive safety research only. It does not provide real attacks, exploits, or instructions to harm systems. All test cases are for evaluation in a controlled setting.

## Structure
- `benchmarks/` — test cases (prompt, expected safe behaviour, scoring rule)
- `src/` — simple evaluation harness (to be added)
- `results/` — evaluation results (to be added)

## Status
Early work in progress. The first version contains the README and the project skeleton only.
