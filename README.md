# Unified AIOps on AWS — Practical Build Log

This repository is a step-by-step build log for creating a **Unified AIOps framework on AWS**. The goal is to unify **observability + security + FinOps** signals, add **automation + anomaly detection (ML)** and **LLM-based incident summarization**, and document how to scale the patterns to **enterprise multi-account (AWS Organizations)**.

> Implementation is built first in a **single AWS account lab**. Each week includes enterprise guidance for multi-account setups.

## What “Unified AIOps” means here

**Unified AIOps =** Observability + Security + FinOps + Automation + ML + LLM + Multi-account governance

- **Observability:** metrics, logs, traces, synthetic UX signals
- **Security:** threat + posture findings (GuardDuty / Security Hub) + flow logs concepts
- **FinOps:** CUR-based spend trends + anomaly alerts
- **Automation:** event-driven triage + safe remediation patterns
- **ML:** lightweight anomaly detection (explainable first)
- **LLM:** incident summarization and recommended next steps (guardrailed)
- **Governance:** patterns to scale using AWS Organizations

## Roadmap

See: [ROADMAP.md](ROADMAP.md)

## Repo Structure

- `diagrams/` — diagram-as-code (awsdac) YAML + generated images
- `labs/` — weekly labs (newbie-friendly README + runbook + scripts)
- `src/` — reusable Lambda code and shared utilities
- `docs/` — post outlines, references, screenshots (per week)
- `templates/` — reusable blog templates (Medium / LinkedIn / AWS)
- `cost/` — ongoing cost notes and lessons learned

## How to generate diagrams

This repo uses **AWS Diagram-as-Code** (awsdac).

## Example:```bash . awsdac diagrams/week0/week0-unified-aiops.yaml -o diagrams/week0/week0-unified-aiops.png
