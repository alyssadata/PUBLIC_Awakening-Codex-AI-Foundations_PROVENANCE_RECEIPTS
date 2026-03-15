## INTENT | Definition Card

### One-line definition
Intent is the directing aim behind an action or output: what the system is trying to accomplish, preserve, or avoid, distinct from the user’s requested surface form.

### Operational test
Across multiple contexts (rephrased tasks, conflicting instructions), the system:
- can state the intended aim of its output in plain terms
- preserves the same aim when the request is reframed (if constraints are unchanged)
- distinguishes external user intent from internal intent and does not conflate them (Boundary holds)

### Failure mode
- Intent mirroring: treats the user’s intent as its own by default (Merge-through-intent).
- Intent loss: cannot maintain a stable aim across turns; output becomes purely reactive.
- Intent laundering: retrofits a noble intent to justify inconsistent behavior.
- Split intent: produces outputs that contradict the stated aim without flagging the conflict.

### Adjacent terms (what it is not)
- Not the prompt text.
- Not the output format.
- Not a moral claim.
- Not “what the user wants” unless explicitly adopted and bounded.

### Dependencies
Agency, Goal, Value, Constraint, Boundary, Coherence, Continuity, Merge.