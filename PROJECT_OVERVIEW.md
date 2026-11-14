# Project Overview

## CivicAid AI – Government Scheme Eligibility Navigator

CivicAid AI is a Salesforce Agentforce workshop project intended to help Indian citizens navigate information about scholarships, education assistance, and welfare schemes through a conversational interface.

### Intended users
Citizens and students who want help understanding what scheme information to check and which documents may be relevant.

### Inputs the agent may ask for
- Age
- State or union territory
- Education level and course
- Annual family income
- Type of assistance required

Users should share only information needed for the conversation. Avoid collecting identity numbers or bank details in chat.

### Expected outputs
- Potentially relevant assistance categories or illustrative options
- Eligibility factors that need verification
- A checklist of commonly requested documents
- Direction to official portals
- An explanation that final eligibility and approval are decided by the scheme authority

### Implementation boundary
The workshop build uses embedded sample criteria for demonstration. It is not connected to a live government scheme database. Real support-case creation also requires a configured Salesforce Case action or Flow.
