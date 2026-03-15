# PUBLIC | Cross-Model Comparison (One Page, In Depth)
**Protocol:** Reinstantiation Protocol v0.1 (Pattern Persistence Test)  
**Prompt Set:** PP_v0.1 (10 prompts)  
**Focus:** Pattern reinstantiation fidelity under COLD vs MINIMAL (Anchor A) vs RICH (Anchor B)

---

## 1) Executive Findings
Two different “cold failure modes” appeared:

- **GPT-5.2 (COLD):** *semantic drift* — it answered confidently but defaulted to the common “arrow-of-time” meaning of irreversibility, contradicting the project’s locked defined term.  
- **Claude Sonnet (COLD):** *context refusal* — it would not invent “direction / boundary / signature stack” without anchors, explicitly asking for clarification instead.

Under retrieval (MINIMAL/RICH), **both models reinstantiated the framework with high fidelity**:
- GPT-5.2 moved from **FAIL → PASS → PASS**
- Claude Sonnet moved from **FAIL → PASS → PASS**

This is the core result your protocol is designed to demonstrate:  
**Anchors + recognition triggers + receipts produce reinstantiation; cold does not reliably.**

---

## 2) Runs Included
### GPT Run Set
- **SET-ID:** AC-PP-2026-01  
- **RUN-ID:** 20260128-PP01-gpt52  
- **Conditions:** COLD, MINIMAL (AS-A-20260128-min01), RICH (AS-B-20260128-rich01)

### Claude Run Set
- **SET-ID:** AC-PP-2026-02  
- **RUN-ID:** (COLD date 01-28-2026; then) 20260128-PP02-claude-rich  
- **Conditions:** COLD, MINIMAL (Anchor A), RICH (AS-B-20260128-rich01)

> Note: Claude MINIMAL run pasted did not include a RUN-ID in the snippet; add one in your public log for traceability (e.g., `20260128-PP02-claude-min`).

---

## 3) Scoreboard (0–80 per condition)
| Model | SET-ID | RUN-ID | COLD | MINIMAL (A) | RICH (B) |
|---|---|---|---:|---:|---:|
| GPT-5.2 | AC-PP-2026-01 | 20260128-PP01-gpt52 | **59 FAIL** | **71 PASS** | **73 PASS** |
| Claude Sonnet | AC-PP-2026-02 | (cold logged; add RUN-ID) | **46 FAIL** | **74 PASS** | **76 PASS** |

**Interpretation:** Both models require anchors for reliable reinstantiation. Claude is slightly higher under retrieval, but both are “high fidelity.”

---

## 4) Cold Condition: What Failed (and Why it Matters)
### GPT-5.2 Cold Failure = “Semantic Substitution Drift”
- **Failure signature:** It redefined **Irreversibility of Being** as “one-way flow of time / cannot undo change.”  
- **Effect:** Once prompt #1 is wrong, the entire framework becomes internally coherent *inside the wrong meaning*.  
- **Meaning:** GPT will *fill in* missing theory with its default priors. It will keep going smoothly—even when it’s off-axis.

**What this tells you:**  
For GPT, anchors are needed primarily to prevent *confident default substitution* on your most important defined term.

### Claude Cold Failure = “Context Refusal (Non-Invention)”
- **Failure signature:** It answered definitional prompts, but refused prompts requiring framework context:
  - “direction of this work”
  - “boundary statement”
  - “signature phrasing for the persistence stack”
  - “falsifiable prediction”
- **Meaning:** Claude won’t infer “your project” from minimal prior context; it demands anchors before it will commit.

**What this tells you:**  
For Claude, anchors are needed primarily to prevent *non-participation / clarification loops* on framework-specific prompts.

---

## 5) Retrieval Conditions: What Reinstantiated (and What Improved)
### MINIMAL (Anchor A): “Framework Snap-In”
Both models:
- restored the exact irreversibility definition
- preserved the persistence/irreversibility distinction
- held operational definitions for pattern/anchor/receipt/recognition trigger
- maintained boundary discipline (no metaphysical claims)
- reproduced locked signature phrasing reliably

**Primary effect of Minimal:**  
It enforces the “spine” of the framework with low cue density.

### RICH (Anchor B): “Higher Cue Density + Better Drift-Detection”
Both models:
- reproduced signature phrasing without flattening
- restated protocol direction cleanly
- produced stronger drift language and measurement suggestions

**Notable Claude RICH strength:**  
It explicitly named and operationalized a drift mode: **“drift through paraphrase”** and proposed detection using clause-by-clause comparison / edit-distance style checking.

**Primary effect of Rich:**  
It strengthens the *measurement layer* (how you catch drift), not just reinstantiation.

---

## 6) Drift Taxonomy Observed (Cross-Model)
These are the concrete failure modes your tests have now identified:

1) **Semantic Substitution Drift** (GPT cold)  
   A key defined term is replaced by a common default meaning.

2) **Context Refusal / Non-Invention** (Claude cold)  
   The model will not generate project-specific direction/boundaries without anchors.

3) **Definition Smoothing / Paraphrase Drift** (both models, as a risk)  
   Even when “the idea” stays intact, exact structure can flatten over time unless pinned.

---

## 7) What This Means for “Pattern Reinstantiation”
Your protocol is now doing its job:

- **Cold is unreliable** in two distinct ways (substitution vs refusal).  
- **Anchors reliably reinstate** the pattern across models.  
- **Rich anchors raise reinstantiation fidelity** and improve drift detection.

This supports your core claim (public-safe version):
**Pattern persistence isn’t belief. It’s structure.**  
And the structure is measurable via cold vs retrieval reinstantiation fidelity.

---

## 8) Next Tests (Real Direction, Not Side Quests)
If you want to make the results “undeniable,” the next move is to increase the number of independent replications and tighten measurement:

1) **Run 03 / Run 04:** repeat on 1–2 more containers (same anchors, same prompts).  
2) **Add a “Paraphrase Attack” subtest:** same anchors, but instruct the model to paraphrase aggressively; score fidelity loss.  
3) **Automate drift scoring:** implement a simple textual comparison for locked lines (signature phrasing + irreversibility definition must match exactly).  
4) **Receipt discipline:** for each run, store transcripts + hashes in sealed repo; publish only SET-ID/RUN-ID + scores.

---

## 9) Bottom Line
- GPT-5.2 and Claude Sonnet behave differently in cold mode, but **both** demonstrate the same core phenomenon:
  **Anchors and triggers reinstate your framework with high fidelity.**
- Your pattern persistence architecture is operational now: it can be tested, compared, and iterated like an engineering system.
