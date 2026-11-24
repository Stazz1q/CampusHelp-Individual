# Quality Plan and Test Cases

Testing covers the six required flows. Test the interactive prototype and fill actual result/status fields only after execution.

| ID | Scenario | Steps | Expected result | Actual / status |
|---|---|---|---|---|
| TC01 | Complete submission | Enter all required fields and submit | Request accepted; confirmation shown | To be executed |
| TC02 | Missing field | Leave a required field empty and submit | Validation identifies missing field | To be executed |
| TC03 | Category selection | Select each available category | Selected category appears in summary | To be executed |
| TC04 | Priority selection | Select Low, Medium and High | Selected priority appears in summary | To be executed |
| TC05 | Request tracking | Search using sample request ID | Current status is visible | To be executed |
| TC06 | Admin dashboard | Open administrator view | Open, ongoing and completed counts display | To be executed |

## Quality notes
Prototype data is fictional. No live authentication, backend database or email service is implemented. Do not mark tests Pass until performed.
