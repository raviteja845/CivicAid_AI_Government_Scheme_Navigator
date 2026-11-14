# Implementation Limitations and Next Steps

## Current limitations

1. **Illustrative criteria only:** the current workshop agent uses embedded sample criteria. It is not connected to an authoritative, regularly updated scheme catalogue.
2. **No live application integration:** the agent cannot submit scholarship or welfare applications.
3. **Case creation not connected:** a real Salesforce Case action or Flow must be configured, tested, and connected before the agent can create Cases.
4. **No exported metadata in this repository:** the Salesforce org contains the Agentforce configuration. This repository currently contains documentation, not a deployable metadata export.

## Recommended next steps

- Build a verified scheme catalogue with source URLs, last-verified dates, eligibility rules, and ownership.
- Add a retrieval or data integration layer that uses authoritative sources.
- Configure and test a Salesforce Case creation Flow/action, including input validation and confirmation handling.
- Add tests for missing information, conflicting inputs, edge cases, and unsupported scheme questions.
- Review privacy, security, accessibility, and accuracy before any real-world deployment.
