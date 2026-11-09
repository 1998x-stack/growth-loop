# Metrics & Experiments — Growth Loop

Use this when creating a testable action, scorecard or learning review. Avoid quantifying inherently qualitative constructs without reliable measurement.

## Experiment contract

**Hypothesis:** If I change [one controllable variable], then [observable difference] should emerge because [mechanism].

**Scope:** One feasible task or deliverable with a named real-world beneficiary.

**Baseline:** Compare with a similar previous task, test set, artifact or observed behavior. If missing: note "no baseline" and first establish one.

**Signal:** one primary outcome and one guardrail; examples: independent completion + acceptable error rate; latency + answer relevance; time saved + unchanged quality.

**Feedback:** identify an evaluator or criterion independent from self-reassurance.

**Review:** when to compare predicted and observed, usually 7–14 days or natural task cycle.

**Stop:** constraints like severe fatigue, loss of time for obligations, negative user outcomes, or goal invalidation.

## Evidence ledger

| Date | Decision / task | Baseline | Prediction | Actual | Source | Confounders | Next decision |
|---|---|---|---|---|---|---|---|
| YYYY-MM-DD | ... | ... | ... | ... | peer/test/log | ... | continue/adjust/stop/explore |

Do not fill unknown numbers or present estimated time savings as measured values.

## Three lenses

### Capability: 0 → 1
- Evidence: first independent completion, fewer hints, meets written rubric.
- Guardrail: "was it truly independent, and was the task comparable?"

### Efficiency: 1 → N
- Evidence: same task class and quality at lower time/cost/rework.
- Guardrail: task became easier? different tools? team help? sacrificed quality?

### Selection: better problems
- Evidence: explicitly declined low-impact work; selected a project with larger justified expected value; tested a competing direction cheaply.
- Guardrail: measure outcomes over time; do not equate novelty or popularity with value.

## PDSA adaptation

1. **Plan**: state test, metric, hypothesis, time and stop signal.
2. **Do**: perform, record deviations.
3. **Study**: compare prediction, baseline and observed evidence. Preserve uncertainty.
4. **Act**: continue, adjust, stop or explore another problem.

## Common failure modes

- **Goodhart:** metric becomes the goal, quality falls as number improves.
- **Selection bias:** only the best attempts are recorded.
- **Survivorship bias:** success story mistaken for general rule.
- **Confounders:** different task, different teammate or changing environment.
- **Hawthorne-like reactivity:** short-term attention alters measured behavior.
- **Overfitting:** endless optimization to one contrived test rather than real user need.

For deeper context, see [evidence-base.md](evidence-base.md). These terms are cautionary guides, not proof that they occurred in the user's case.
