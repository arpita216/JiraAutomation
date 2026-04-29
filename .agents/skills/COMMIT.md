# Commit Skill

Follow these instructions whenever asked to create a commit or push changes.

## Workflow

### 1. Branch Creation
Create a new branch with the following naming convention:
`arpita/{jira-ticket-id}/{short-title-about-feature-or-bug}`

### 2. Commit Message
Create a commit using standard guidelines with the following format:

**Title:**
`{commit-type}({Jira-ticket-id}):{commit-title}`

**Description:**
The description must include "Requirement" and "Changes" sections.

---

## Example

**Branch:**
`arpita/PROJ-456/fix-api-timeout`

**Commit Message:**
```text
fix(PROJ-456): resolve API timeout issue in production

Requirement:
Users are experiencing 504 errors when fetching large datasets.

Changes:
- Increased timeout duration in API client configuration.
- Added retry logic for transient failures.
- Optimized database query for faster response times.
```
