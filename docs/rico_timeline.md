# Rico's timeline

| When   | What                                               | Phase |
| ----   | ----                                               | ----  |
| May 9  | Got my Australian visa approved                    | -     |
| May 16 | Inquire at POEA Mandaluyong                        | -     |
| May 28 | Inquire at POEA Mandaluyong, again                 | -     |
| May 29 | Inquire at POLO Canberra                           | -     |
| May 30 | Request **Company certification** from my employer | A     |
| May 31 | Request **Contract amendment** from my employer    | A     |

## Diagram

```mermaid
sequenceDiagram
participant Employer
participant Me
participant POLO as POLO, Australia
participant POEA as POEA, Mandaluyong

Me->>POEA: (05/16) Inquire
Me->>POEA: (05/28) Inquire again
Me->>+POLO: (05/29) Inquire (email)
Me->>+Employer: (05/30) Request for Company certification
Me->>POLO: (05/30) Follow-up questions
Me->>+Employer: (05/31) Request for Contract amendment
Me->>POLO: (05/31) Follow-up questions
POLO-->-Me: (06/01) Got all answers

Note over Employer,POEA: -

Employer-->-Me: (?) Got document
Employer-->-Me: (?) Got document

Me->>+Employer: (?) Request Employer ID
deactivate Employer
Me->>+POLO: Request for evaluation
deactivate POLO
```
