# Direct hire evaluation

**To acquire an OEC, you need to first be evaluated by the Direct Hire department of the POEA offices in EDSA.** To be evaluated, you'll need to submit all the documents in their checklist.

## Dependency graph

```mermaid
graph RL
OEC("<b>OEC</b><br>Overseas<br>Employment<br>Certificate")
EVAL1(<b>Evaluation<br>phase 1</b>)
EVAL2(<b>Evaluation<br>phase 2</b>)
PDOS[<b>PDOS</b><br>Pre-departure seminar]
PEOS[<b>PEOS</b><br>Pre-employment seminar]
CLEARANCE[<b>POEA clearance</b>]

PEME[<b>PEME</b><br>Medical exam]
click PEME "./medical_exam.html" "Medical exam"

CONTRACT(<b>Contract<br>verification<br>requirements</b>)
VERIFIED["<b>Verified contract</b><br>Verified by the<br>POLO (PH Overseas<br>Labor Office)"]
click VERIFIED "./polo_verification.html" "Verified contract"
REVISED["<b>Revised contract</b><br>With POEA-required<br>revisions"]
click REVISED "./employment_standards.html" "Revised contract"
CERTIFICATION["<b>Employer certification</b><br>Showing they hired 5<br>Filipinos max"]
COMPLIANCE["<b>POEA Compliance Sheet</b><br>To cover POEA requirements<br>missing in contract"]

ODOCS(<b>Documents</b>)
PASSPORT["<b>Passport</b><br>Valid for 6+ months"]
VISA["<b>Work visa</b><br>or entry permit"]

SDOCS(<b>Supporting<br>documents</b>)
ENDORSEMENT["<b>POLO endorsement</b><br>Endorsement letter"]
click ENDORSEMENT "./polo_endorsement.html" "POLO endorsement"
STATEMENT["<b>Notarized statement</b><br>Describe how you got the job"]
EMPLOYERID["<b>Employer's ID</b><br>Required for notarization"]

JOBDOCS(<b>Job-related<br>documents</b>)
CV["<b>Resume / CV</b>"]
PRC["<b>PRC License</b><br>(PH Regulatory Commission)"]
DIPLOMA["<b>Diploma</b><br>and Transcript of Records"]
PROFILE["<b>Company profile</b><br>and business license of employer"]

OEC === EVAL2

EVAL2 --- PDOS
EVAL2 --- PEOS
EVAL2 --- CLEARANCE
EVAL2 --- PEME

EVAL2 === EVAL1
EVAL1 --- JOBDOCS
EVAL1 --- ODOCS
EVAL1 --- SDOCS
VERIFIED --- CONTRACT

subgraph Job documents
JOBDOCS --- VERIFIED
JOBDOCS --- CV
JOBDOCS --- PRC
JOBDOCS --- DIPLOMA
JOBDOCS --- PROFILE
end

subgraph Documents
ODOCS --- PASSPORT
ODOCS --- VISA
end

subgraph Supporting documents
SDOCS --- ENDORSEMENT
SDOCS --- STATEMENT
STATEMENT --- EMPLOYERID
end

subgraph POLO requirements
CONTRACT --- REVISED
CONTRACT --- CERTIFICATION
CONTRACT --- COMPLIANCE
end

style OEC fill:#fff,stroke:#3bd,stroke-width:9px
style EVAL1 fill:#fff,stroke:#3bd,stroke-width:9px
style EVAL2 fill:#fff,stroke:#3bd,stroke-width:9px

style ODOCS fill:#fff,stroke:#3bd,stroke-width:2px
style SDOCS fill:#fff,stroke:#3bd,stroke-width:2px
style JOBDOCS fill:#fff,stroke:#3bd,stroke-width:2px
style CONTRACT fill:#fff,stroke:#3bd,stroke-width:2px
```

## May 2018 checklist

As of May 2018, this department issues a checklist of requirements. See: [Evaluation requirements](./evaluation_requirements.md). :warning: The list of requirements on the POEA website [is outdated](./skilled_worker_requirements_outdated.md).

<br>

> Next: Find out about the [direct hire ban](./direct_hire_exception.md), and how you can circumvent it.
