# Naming Conventions and General Standards

This document defines the general naming conventions and writing standards to be used throughout all documentation, code samples, internal files, and communication for our project.

Consistency in naming improves clarity, reduces misunderstandings, and reflects the professionalism of our human-to-AI bridge philosophy.

---

# General Naming Principles

- **Be Clear:** Choose names that immediately reveal their purpose.
- **Be Consistent:** Follow the same structure across all documents and systems.
- **Be Concise:** Avoid unnecessary words without losing meaning.
- **Be Specific:** Name things precisely to avoid ambiguity.

---

# Naming Standards

| Item Type                  | Convention Example                    | Notes                                           |
|-----------------------------|----------------------------------------|-------------------------------------------------|
| File Names                  | `writing-style-guide.md`               | Use lowercase, hyphens to separate words.       |
| Folder Names                | `standards`, `examples`, `templates`   | Lowercase, single-word if possible.             |
| Markdown Headings           | `#`, `##`, `###` with sentence case    | Only first word and proper nouns capitalized.   |
| Variable Names (Code)       | `sensorStatus`, `userID`               | camelCase for variables.                       |
| Constant Names (Code)       | `MAX_RETRIES`, `DEFAULT_TIMEOUT`       | UPPER_SNAKE_CASE for constants.                |
| Document Titles (First Line)| `Naming Conventions and General Standards` | Title case allowed for first line only.        |
| Section Titles              | `General Naming Principles`           | Sentence case preferred for all headings inside.|

---

# File and Folder Structure Standards

| File                         | Path                                          |
|-------------------------------|-----------------------------------------------|
| Writing Style Guide           | `/docs/standards/writing-style-guide.md`      |
| Word List                     | `/docs/standards/word-list.md`                |
| Voice and Tone                | `/docs/standards/voice-and-tone.md`           |
| Text Formatting Standards     | `/docs/standards/text-formatting.md`          |
| Writing Examples and Templates| `/docs/standards/writing-examples.md`         |

> **Note:** Maintain all naming in English for maximum accessibility and international readability.

---

# Naming in Text and Labels

- **Button Names:** Use imperative verbs.
  - Examples: **Submit**, **Cancel**, **Restart**

- **Labels:** Be descriptive but brief.
  - Examples: **Device Name**, **Connection Status**

- **Error Codes:** Use a logical structure.
  - Example: `ERR_CONNECTION_TIMEOUT`, `ERR_INVALID_INPUT`

---

# Examples of Good vs Bad Naming

| Context                | Good Example                        | Bad Example                   |
|------------------------|-------------------------------------|-------------------------------|
| File Name              | `user-authentication-guide.md`      | `UserGuideFinal2.md`          |
| Heading                | `## Install the Package`            | `## INSTALL PACKAGE`          |
| Variable               | `serverResponseTime`                | `srvRspTme`                   |
| Constant               | `MAX_CONNECTION_RETRIES`            | `MaxConRet`                   |

---

# Final Reminder

**Naming is not trivial.** It defines first impressions, eases navigation, and promotes understanding. 
Choose names carefully and apply these standards consistently.

---

# File Location

This document is stored at:
```bash
standards\naming-standards\naming-conventions-general-standards.md