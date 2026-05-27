# Piotr Pietruszewski — IDDA Research

Independent researcher and creator of **IDDA — Intelligent Deterministic Decision Architecture**.

I work on deterministic decision layers for noisy, uncertain, high-volume data environments.

The core idea:

> Raw data is not the same as operational meaning.  
> A decision layer should admit what is meaningful, suppress what is noise, and preserve an auditable decision trail.

---

## IDDA / Deterministic Decision Architecture

IDDA is an architecture for deterministic, auditable, and stable decision-making under noisy inputs.

It is focused on:

- admissibility before execution,
- deterministic decision logic,
- noise suppression,
- class-level auditability,
- profile-based interpretation,
- stable operational behavior under repeated noisy events.

IDDA is not positioned as a black-box AI model.

It is a deterministic decision architecture designed to sit before execution, storage, alerting, or downstream analytics.

---

## Public Demos

### IDDA Interactive Lab

Interactive public-safe demo of IDDA-style decision behavior.

https://piotrpietruszewski-research.github.io/idda-interactive-lab/

### IDDA Boundary Console

Interactive public-safe boundary / admissibility console.

https://piotrpietruszewski-research.github.io/idda-boundary-console/

---

## Public PoC Reports

### IDDA Log Governor — Public PoC Report

Public-safe report for deterministic reduction of noisy telemetry streams into compact, auditable decision classes.

Public report:

https://piotrpietruszewski-research.github.io/idda_log_governor_report_public/

Public artifact repository:

https://github.com/piotrpietruszewski-research/idda_log_governor_report_public

Public PoC highlights:

- 50,000,000 log lines processed in a local throughput benchmark,
- approximately 62–70k lines/s observed local throughput,
- 7,500,000 live Docker industrial telemetry events,
- 90.00% suppression in the Docker live run,
- reduction into 3 decision classes,
- API profile comparison: 19 classes vs 5 classes,
- class-level audit instead of full per-line storage.

---

## Papers / Architecture Notes

### Swiss Cheese Theory Revisited

Correlation-aware admissibility and active execution governance in layered architectures.

This work revisits the classical Swiss Cheese Model from the perspective of correlation-aware admissibility, pre-escalation regulation, and deterministic execution governance.

Related concepts:

- correlation-aware admissibility,
- active regulation,
- anti-cascade governance,
- trajectory preservation,
- bounded recovery,
- telemetry-supported auditability.

---

## Current Research Direction

My current focus is on moving IDDA from theory into public-safe PoC artifacts:

- telemetry reduction,
- log governance,
- decision-class audit,
- deterministic observability support,
- industrial telemetry interpretation,
- profile-based decision granularity.

The goal is not to replace observability platforms.

The goal is to create a deterministic decision layer that can reduce noisy streams into compact, auditable, decision-ready signals before heavier storage, alerting, or analytics.

---

## Public-Safe Boundary

Public repositories intentionally exclude:

- source code for protected PoC logic,
- raw logs,
- JSONL audit files,
- internal event patterns,
- class IDs,
- Docker runners,
- implementation-specific profile logic,
- production thresholds and tuning.

Public materials show the architecture, behavior, and PoC results without exposing private implementation details.

---

## Important Note

All public PoC results are local synthetic research results.

They are not production guarantees.

A real deployment would require ingestion design, buffering, source tagging, monitoring, retention rules, access control, failover, integration work, and production validation.

---

## Contact / PoC Discussion

I am open to discussing small, bounded, offline PoC cases where IDDA-style deterministic decision reporting may be useful.

A suitable first PoC does not require production integration.

Typical starting point:

- sanitized log export,
- telemetry sample,
- CSV / JSON operational data,
- bounded offline dataset,
- clear PoC scope,
- HTML decision-quality report as the output.

The goal of a first PoC is not to promise production outcomes.

The goal is to check whether noisy operational data can be reduced into compact, auditable, decision-ready signals while preserving a clear explanation trail.

For research, PoC discussion, or collaboration:

**Piotr Pietruszewski**  
GitHub: https://github.com/piotrpietruszewski-research  
Email: [piotr@piotrpietruszewski.com](mailto:piotr@piotrpietruszewski.com)
