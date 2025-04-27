# Writing Examples and Templates

This document provides practical writing examples and templates to illustrate best practices for creating clear, precise, and helpful documentation. 

Use these examples as a guide when drafting new documents, tutorials, or user manuals.

---

# Good vs Bad Writing Examples

## Introduction Sections

| Good Example                                                | Bad Example                                          |
|-------------------------------------------------------------|------------------------------------------------------|
| "This guide helps you install and configure the system efficiently." | "We're gonna show you how to maybe set up the thing." |

**Key Points:**
- Be clear about purpose.
- Avoid slang and uncertainty.

---

## Instructions and Procedures

| Good Example                                                | Bad Example                                          |
|-------------------------------------------------------------|------------------------------------------------------|
| "1. Open the Settings menu.\n2. Select 'Network'.\n3. Click 'Add Connection'." | "First you need to go to settings and then, like, find network stuff." |

**Key Points:**
- Use numbered steps.
- Keep each step direct and specific.

---

## Error Messages

| Good Example                                                | Bad Example                                          |
|-------------------------------------------------------------|------------------------------------------------------|
| "Error: Unable to connect to the server. Check your network settings." | "Oops, something bad happened!"                     |

**Key Points:**
- State the problem clearly.
- Suggest a next action.

---

## Technical Explanations

| Good Example                                                | Bad Example                                          |
|-------------------------------------------------------------|------------------------------------------------------|
| "The controller processes sensor inputs and updates actuator outputs every 10 ms." | "The system kinda works with inputs and stuff in a loop." |

**Key Points:**
- Use precise technical language.
- Avoid vague descriptions.

---

# Templates

## General Document Template

```markdown
# Title of the Document

## Overview
Provide a brief, clear summary of the document's purpose.

## Prerequisites
List any requirements needed before proceeding.

## Instructions
1. Step One
2. Step Two
3. Step Three

## Troubleshooting
Describe common issues and their solutions.

## Additional Resources
Link to related guides or documentation.
```

---

## API Documentation Template

```markdown
# API Name

## Overview
Briefly describe what the API does.

## Endpoint
`GET /api/v1/example`

## Parameters
| Name     | Type   | Description              |
|----------|--------|---------------------------|
| id       | String | Unique identifier         |
| status   | String | Filter by status (optional)|

## Responses
### Success (200)
```json
{
  "id": "1234",
  "status": "active"
}
```

### Error (400)
```json
{
  "error": "Invalid ID provided."
}
```

## Examples
Provide example requests and responses.

## Notes
Any special notes or behaviors.
```

---

# Final Reminder

**Good writing is a silent teacher.** Through clear examples and structured templates, we reduce user confusion and enhance learning.

When unsure, always prioritize clarity, simplicity, and logical progression.

---

# File Location

This document is stored at:
```bash
standards\writing-standards\writing-examples.md