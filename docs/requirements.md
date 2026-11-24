# Requirements — CampusHelp

| ID | Requirement | Acceptance criteria |
|---|---|---|
| FR-01 | Submit service request | Form captures student ID, category, description and priority; required fields are validated. |
| FR-02 | Select category | User can choose IT Support, Classroom Maintenance, Library Assistance or Administration. |
| FR-03 | Unique request ID | A unique sample ID is displayed after submission. |
| FR-04 | Administrator assignment | Admin view displays an assignee for each request. |
| FR-05 | Status updates | Request can be Open, In Progress or Completed. |
| FR-06 | Dashboard | Summary displays open, ongoing and completed request counts. |

## Quality expectations
- Clear, readable interface labels.
- Required-field validation before submission.
- Fictional demo data only.
- Simulated functions are clearly identified.
- Core flows work in a modern desktop browser.

## Stakeholders
Students, University Administration (simulated sponsor), IT support, maintenance, library staff and service administrators.

## Assumptions
Authentication, backend persistence, live email/SMS and university-system integration are not implemented.
