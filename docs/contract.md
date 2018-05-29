# Contract requirements

You need a verified contract from POLO.

## Process

> TODO: I'm still inquiring about this.

```mermaid
sequenceDiagram
  participant POEA
  participant Employee
  participant Employer
  participant POLO

  Employee-->Employer: Negotiate on revisions
  Employer->>POLO: Mail contract for verification
  Note over POLO: Verify contract
  POLO->>Employer: Mail verified contract back
  Employer->>Employee: Mail contract back to PH
  Employee->>POEA: Submit for evaluation
```

<br>

> Next: Negotiate on revisions by ensuring your work contract follows [POEA employment standards](employment_standards.md).
