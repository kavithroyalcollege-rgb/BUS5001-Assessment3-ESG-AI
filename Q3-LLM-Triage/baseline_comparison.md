# Baseline Comparison

## Rule-Based Baseline

The following simple keyword rules were used as a baseline classifier:

| Rule | Classification |
|--------|--------|
| Contains "leak" or "water" | Water or facilities issue (HIGH) |
| Contains "supplier" | Supplier sustainability issue (MEDIUM) |
| Contains "accessible" or "blocked" | Accessibility and inclusion issue (HIGH) |

## Comparison Results

| Message | LLM Classification | Baseline Classification | Observation |
|----------|----------|----------|----------|
| Water leak in Building C | Water or facilities issue (HIGH) | Water or facilities issue (HIGH) | Consistent |
| Supplier sustainability concern | Supplier sustainability issue (MEDIUM) | Supplier sustainability issue (MEDIUM) | Consistent |
| Accessible entrance blocked | Accessibility and inclusion issue (CRITICAL) | Accessibility and inclusion issue (HIGH) | LLM recognised higher escalation risk |

## Discussion

The LLM and rule-based baseline produced consistent classifications for all three test cases. However, the LLM generated richer outputs including sentiment, escalation reasons, data sensitivity assessments and recommended teams. The largest difference occurred in the accessibility scenario, where the LLM classified the issue as CRITICAL due to the potential impact on accessibility and inclusion, whereas the baseline system classified it as HIGH based solely on keyword matching.

Overall, the LLM provided more contextual understanding and produced outputs that are more useful for operational triage and escalation.
The experiment demonstrates that LLMs can provide richer contextual analysis than simple keyword-based systems, making them suitable for ESG operational triage where escalation reasoning and team recommendations are important.
