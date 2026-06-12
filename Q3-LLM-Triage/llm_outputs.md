# LLM Outputs

## Message 1

### Input
"There is a water leak in Building C that has been running all morning."

### Output

```json
{
  "issue_category": "Water or facilities issue",
  "urgency": "HIGH",
  "sentiment": "Negative",
  "followup_required": "Yes",
  "recommended_team": "Facilities Management",
  "escalation_reason": "Ongoing water leak may cause property damage, resource wastage, and operational disruption if not addressed promptly.",
  "data_sensitivity_risk": "Low",
  "brief_summary": "Employee reported a water leak in Building C that has been running throughout the morning and requires maintenance attention."
}
```
## Message 2

### Input
"I want to report that one of our suppliers may not meet our sustainability policy."

### Output
```json
{
  "issue_category": "Supplier sustainability issue",
  "urgency": "MEDIUM",
  "sentiment": "Concerned",
  "followup_required": "Yes",
  "recommended_team": "Procurement and Sustainability Team",
  "escalation_reason": "Potential non-compliance with supplier sustainability requirements may require investigation and corrective action.",
  "data_sensitivity_risk": "Medium",
  "brief_summary": "Employee reported concerns that a supplier may not be meeting the organisation's sustainability policy and requested review."
}
```

## Message 3

### Input
"The accessible entrance near the main building has been blocked for two days.."

### Output
```json
{
  "issue_category": "Accessibility and inclusion issue",
  "urgency": "CRITICAL",
  "sentiment": "Negative",
  "followup_required": "Yes",
  "recommended_team": "Facilities and Accessibility Team",
  "escalation_reason": "Blocked accessible entrance may prevent equitable access and requires immediate action.",
  "data_sensitivity_risk": "Medium",
  "brief_summary": "Employee reported that an accessible entrance has been blocked for two days and requires urgent attention."
}
```
