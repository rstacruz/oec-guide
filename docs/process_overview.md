# _OEC guidebook_ Process overview

There are 3 main phases involved in getting an Overseas Employment Certificate.

|     | Phase                                                                                                                                                | Locations                                   |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| 1.  | **[POLO contract verification]** <br> Your work contract needs to be verified by the Philippine Overseas Labor Office (POLO) closest to your employer. | POLO offices, overseas (via mail)           |
| 2.  | **[POEA evaluation phase 1]** <br> Your documents will be evaluated by the POEA's direct hire department.                                              | Direct Hire department (POEA offices, EDSA) |
| 3.  | **[POEA evaluation phase 2]** <br> You will need to attend 2 seminars, and get a medical exam.                                                         | CFO; DOH-accredited health facilities       |

[POLO contract verification]: ./contract.md
[POEA evaluation phase 1]: ./direct_hire_evaluation.md
[POEA evaluation phase 2]: ./evaluation_phase_2.md

## Sequence

```mermaid
sequenceDiagram
  participant POLO as POLO
  participant Employee
  participant POEA as POEA

    Employee->>+POLO: Send contract (via employer)
    Note right of POLO: Verify contract
    POLO->>-Employee: Send contract (via employer)
    POLO->>Employee: Send endorsement letter

    Note over Employee: Collect more requirements
    Employee->>+POEA: Send docs for evaluation
    Note left of POEA: Evaluation phase 1
    POEA->>-Employee: Approve phase 1

    Note over Employee: Do seminars
    Note over Employee: Medical exam
    Employee->>+POEA: Send new docs for evaluation
    Note left of POEA: Evaluation phase 2
    POEA->>-Employee: Final approval
```

<br>

> Next: [What documents are required?](./requirements_overview.md)
