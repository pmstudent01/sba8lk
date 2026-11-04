# custedu-qa-template
template used to seed new repos for the v12 QA path

## Student Challenge - Scenario 2

This branch contains the completed student challenge work for the SafeStar Service QA Workspace.

### What was implemented

- **Scenario 2 - Student Challenge** workflow tests in the `SafeStar Service Testing` collection
- Tests cover the full error-handling flow:
  - Existing driver starts vehicle and triggers SafeStar
  - An unexpected error occurs during vehicle safety scan
  - Diagnostic report is triggered, retrieved, and sent to SafeStar
- JWT authentication configured across all Scenario 2 requests
- Post-response test scripts validating status codes, response structure, and business logic (e.g. `safetyScore` range, VIN validation)
