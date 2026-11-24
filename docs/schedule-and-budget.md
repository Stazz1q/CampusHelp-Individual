# Schedule, Dependencies and Budget

## Milestones
| Milestone | Target | Deliverables |
|---|---|---|
| M1 — Project Initiation | Day 2 | Charter, requirements, stakeholders, initial WBS |
| M2 — Project Planning | Day 4 | Schedule, estimates, risk register, mockups, quality plan |
| M3 — Project Execution | Day 7 | Student screen, admin dashboard, prototype and test cases |
| M4 — Monitoring and Closure | Day 10 | Change request, verification, progress status and report |

Set actual calendar due dates in GitHub using the instructor's assigned start date.

## Work estimates
| ID | Task | Hours | Priority | Milestone | Predecessor |
|---|---|---:|---|---|---|
| T01 | Develop project charter | 4 | High | M1 | — |
| T02 | Gather stakeholder requirements | 4 | High | M1 | — |
| T03 | Prepare scope and WBS | 4 | Medium | M1 | T01 |
| T04 | Prepare schedule, dependencies and budget | 4 | High | M2 | T03 |
| T05 | Design initial wireframes | 4 | Medium | M2 | T02 |
| T06 | Develop risk register and quality plan | 4 | Medium | M2 | — |
| T07 | Create student request interface prototype | 4 | High | M3 | T05 |
| T08 | Create administrator dashboard prototype | 4 | High | M3 | T05 |
| T09 | Prepare and execute prototype test cases | 4 | High | M3 | T07, T08 |
| T10 | Evaluate and document change request | 3 | Medium | M4 | — |
| T11 | Perform final verification and issue review | 3 | High | M4 | T09, T10 |
| T12 | Consolidate final report and closure documents | 3 | Medium | M4 | T11 |

**Total:** 45 hours.

## Dependencies
All dependencies are Finish-to-Start:
- T03 depends on T01.
- T04 depends on T03.
- T05 depends on T02.
- T07 and T08 depend on T05.
- T09 depends on both T07 and T08.
- T11 depends on T09 and T10.
- T12 depends on T11.

## Critical schedule drivers
T02 may delay wireframes; T05 may delay both prototypes; T09 may delay final verification.

## Budget
45 hours × 50,000 UZS/person-hour = **2,250,000 UZS** (simulated academic estimate, not actual expenditure).
