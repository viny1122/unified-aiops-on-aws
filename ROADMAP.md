# Unified AIOps on AWS — Roadmap

This repository documents a structured build log for creating a Unified AIOps framework on AWS.

Implementation is done in a single-account lab, with enterprise multi-account guidance included in each phase.

---

## Week 0 — Vision & Architecture
- Define Unified AIOps pillars
- Publish initial reference architecture (diagram-as-code)
- Establish repo structure and templates

## Week 1 — Observability Foundation
- Lambda + API Gateway workload
- CloudWatch metrics, logs, tracing
- Alarm-based signal generation

## Week 2 — Event-Driven Incident Routing
- EventBridge alarm routing
- Triage Lambda
- DynamoDB incident table
- S3 evidence store
- SNS notifications

## Week 3 — Correlation & Dedupe Logic
- Reduce alert noise
- Correlate multi-signal events into a single incident
- Track incident lifecycle

## Week 4 — Security Signal Integration
- GuardDuty findings
- Security Hub integration
- Unified incident normalization

## Week 5 — FinOps Intelligence
- CUR ingestion
- Cost anomaly detection
- Treat spend spikes as operational incidents

## Week 6 — Anomaly Detection (ML)
- Lightweight statistical anomaly detection
- Optional comparison with sklearn models

## Week 7 — LLM-Based Incident Intelligence
- Bedrock-powered summarization
- Recommended next steps
- Guardrails and governance considerations

## Week 8 — Final Architecture & Lessons Learned
- Unified reference architecture (final version)
- Cost breakdown
- Pitfalls and trade-offs
- Enterprise multi-account blueprint
