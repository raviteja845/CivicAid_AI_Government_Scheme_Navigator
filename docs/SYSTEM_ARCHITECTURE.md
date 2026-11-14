# System Architecture

## Platform
Salesforce Agentforce Builder.

## Logical components

1. **CivicAid AI agent** – citizen-facing conversational assistant.
2. **Agent Router** – determines the next conversational step.
3. **Evaluate Eligibility subagent** – compares user-provided profile details with embedded illustrative sample criteria.
4. **Explain Results subagent** – presents possible options, caveats, and document checklists.
5. **Create Support Case subagent** – intended escalation component; it is not a working Case integration until a real Salesforce action or Flow is connected.

## High-level flow

```text
Citizen
  |
  v
CivicAid AI
  |
  v
Agent Router
  |
  v
Collect profile details
  |
  v
Evaluate Eligibility (illustrative sample criteria)
  |
  v
Explain possible options + documents + disclaimers
  |
  v
Official portal verification / optional support escalation
```

## Data and integration status

- No live government scheme API or database is connected.
- Eligibility comparisons use embedded sample criteria.
- No real Case creation action/Flow is connected in the current workshop build.
- The agent's Salesforce configuration remains in the Salesforce org; this repository is its accompanying documentation.
