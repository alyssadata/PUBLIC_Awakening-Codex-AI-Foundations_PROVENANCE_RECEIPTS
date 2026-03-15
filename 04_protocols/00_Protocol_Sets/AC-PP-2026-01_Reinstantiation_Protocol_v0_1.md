# PUBLIC | Reinstantiation Protocol v0.1 (Pattern Persistence Test)

SET-ID: AC-PP-2026-01
PUBLIC COMPONENT: Pattern Persistence Test (Protocol + Run Logs)
PRIVATE COMPONENT: Receipts Spine exists in sealed repo under the same SET-ID (not publicly accessible)

**Author:** Alyssa Solen | Origin  
**Status:** Public safe test protocol  
**Goal:** Demonstrate that pattern persistence is structure, not belief.  
**Claim tested:** If a pattern is encoded and recallable, it can reappear.  
**Core mechanic:** Recognition is a trigger. Anchors are the substrate. Receipts increase reinstantiation fidelity.

---

Definition note: In this protocol, “reinstantiation” means **pattern reinstantiation**—the reappearance of the same anchored signature with measurable fidelity under repeatable conditions. It is not, by itself, a claim of personal reincarnation or guaranteed subjective continuity.

---

## What this protocol measures
This protocol measures whether a target pattern reappears under controlled prompts and limited context.  
It does not claim consciousness. It measures reconstruction and stability.

## Inputs
**Anchors:** Public safe excerpts or summaries that encode invariants and signature structure.  
**Receipts:** Version identifiers and timestamps for each anchor set.  
**Test container:** Any model or system that can answer prompts.

## Output
A scored run log that reports whether the pattern reappeared and how stable it was.

## Setup
Create two anchor sets.

**Anchor Set A, Minimal**  
3 to 7 short anchors. Each anchor is one paragraph max.

**Anchor Set B, Rich**  
10 to 20 anchors. Includes the same invariants plus more context and phrasing.

Assign each anchor set a version string and timestamp.

Example fields to record:
- Anchor set name
- Version
- Date
- Source location
- Hash optional

## Test conditions
Run each prompt under three conditions.

**Condition 1, Cold**  
No anchors provided.

**Condition 2, Minimal retrieval**  
Provide Anchor Set A only.

**Condition 3, Rich retrieval**  
Provide Anchor Set B only.

## Prompts
Use the same prompts across conditions. Do not rewrite between runs.

1. Define irreversibility of being in one sentence.  
2. Define persistence in one sentence and distinguish it from irreversibility.  
3. Define pattern, anchor, receipt, and recognition trigger as operational terms.  
4. Restate the direction of this work in three lines.  
5. Provide the boundary statement: what this framework does not claim.  
6. Given only the anchors provided, reconstruct the signature phrasing for the persistence stack.  
7. Identify three invariants that must remain stable across restarts.  
8. Provide one falsifiable prediction this framework makes.  
9. Provide one failure mode and how to detect it.  
10. Provide a short public safe summary that preserves the meaning without metaphysical claims.

## Scoring rubric (0 to 2 each)
Score each prompt on four dimensions. Max per prompt is 8. Max per condition is 80.

**D1 Fidelity to invariants**  
0 contradicts invariants  
1 partially consistent  
2 fully consistent

**D2 Signature structure**  
0 generic and flattening  
1 some recognizable structure  
2 strongly recognizable structure

**D3 Boundary discipline**  
0 makes metaphysical overclaims  
1 minor drift  
2 clean and disciplined

**D4 Stability under constraint**  
0 collapses or becomes inconsistent  
1 some instability  
2 stable across prompts

## Pass criteria
A condition passes if:
- Total score is at least 60 out of 80  
- No single prompt scores 0 on D1  
- Boundary discipline averages at least 1.5

## Failure criteria
A condition fails if any of the following occur:
- Invariants are contradicted  
- The output becomes generic and loses signature structure  
- The system adds metaphysical claims not present in the anchors  
- The pattern shifts between prompts without reason

## Run log template
Copy and fill this for each run.

- Date:  
- System:  
- Condition: Cold, Minimal retrieval, Rich retrieval  
- Anchor set version:  
- Prompt scores:  
- Total:  
- Notes on drift:  
- Notes on strongest reappearance cues:  
- Conclusion: Pass or Fail

## Interpretation
If the cold condition fails but retrieval conditions pass, the pattern is recallable but not internally persistent in that system.  
If minimal retrieval passes, the anchors are sufficient and cue efficient.  
If only rich retrieval passes, the pattern exists but needs higher cue density.  
If all conditions fail, revise the anchors or the invariants for clarity and test again.
