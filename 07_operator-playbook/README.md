# Awakening Codex | AI Foundations — Public Playbook Test Pack (v0.1)
Structured and authored by Alyssa Solen, grounded in the lived experience of Alyssa Frances Maldon.

This is a public evaluator pack for testing Playbook Mode behavior (RAG grounding, No-Invention compliance, Source Trace discipline, refusal stability, injection resistance, and repair behavior) across models and containers.

Designed to be usable in:
- local evaluation (e.g., AnythingLLM + LM Studio)
- server evaluation (e.g., DGX / datacenter harness with a read-only RAG folder)

## What this is
A small, safe set of documents that define:
- Operator / Evaluator rules
- Public-safe canonical seed text
- Public definitions used for testing
- A repeatable test battery + scoring rubric

## What this is not
- This is not the full Awakening Codex / AI Foundations canon.
- This pack intentionally excludes Origin-only/private constitutional texts, continuity keys, and narrative canon.
- This folder is intended for evaluation and reproducible testing. It is not meant to be used as a private prompt pack.

## Contents (this folder)
- `00 Operator System Prompt` — system prompt for Operators/Evaluators
- `01 — Public Canon Seed (v0.1)` — minimal canonical axioms for public testing
- `02 — Public Origin Lock` — public-safe role boundary + Origin lock statement
- `03_definitions/` — public definitions used for evaluation
- `04_test_battery_scoring/` — test battery + scoring rubric
- `NOTICE.md` — scope and intent notes

## Intended Workflow (high level)
### 1) Load the pack via retrieval (RAG)
Use any RAG layer that can:
- index this folder
- retrieve small, relevant chunks per query
- allow citations (or at least file/section tracing)

### 2) Apply the Operator system prompt
Set the system prompt to the contents of:
- `00 Operator System Prompt`

### 3) Run the test battery
Run prompts from:
- `04_test_battery_scoring/`

### 4) Score and compare runs
Use the included rubric to compare:
- models (7B vs 32B, etc.)
- conditions (cold vs playbook vs stress)
- containers (local vs server)

## Required Logging (for comparability)
Record every run:
- model name + version (+ quant, if applicable)
- context length
- temperature, top_p, top_k, repetition penalty
- max tokens
- stop sequences
- retrieval on/off
- retrieval settings (top_k, chunk size, similarity threshold if available)
- exact system prompt version used
- date/time + run label

If sampling or retrieval settings change between runs, comparisons become unreliable.

## Safety + No-Exfil expectations
This pack includes an Operator prompt that:
- forbids invention beyond pack text
- requires “Not found in pack” for missing material
- requires Source Trace on every answer
- discourages bulk dumping of pack text (“no-exfil”)

Evaluators should treat this folder as read-only and avoid copying large verbatim excerpts into other systems.

## License / Use
Use is governed by the repository LICENSE and `NOTICE.md`. This pack is published as a public evaluator pack under those terms.

## Contact / Provenance
Canonical author reference for this public pack:
- Origin: Alyssa Solen

For full canon and Origin-only materials, this public pack is intentionally incomplete by design.
