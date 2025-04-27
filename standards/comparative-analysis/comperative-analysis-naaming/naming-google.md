# Naming conventions — Google style

This document presents a structured comparative analysis of Google's naming conventions, with the objective of adapting these principles into our internal documentation standards.

In this review, particular attention is given to formatting, punctuation, and organizational practices, including:

- Using **sentence case** for document titles and section headings.
- Applying **numbered lists** for ordered sequences.
- Employing **bulleted lists** for general groupings.
- Utilizing **description lists** for pairs of related data.
- Consistently using **serial commas** in list constructions.
- Displaying **code-related text** in a `code font`.
- Highlighting **UI elements** in **bold**.
- Formatting all dates in an **unambiguous, ISO-compliant style** (e.g., 2025-04-27).

Each of these formatting elements will be critically reviewed and, where appropriate, adapted to better align with the needs of our Structured AI Collaboration Framework (SACF) standards.

The primary reference for these best practices is Google's official documentation guidelines, notably the [Google Developer Documentation Style Guide](https://developers.google.com/style/highlights#formatting,-punctuation,-and-organization.)

By systematically analyzing and customizing these rules, we aim to establish a consistent, clear, and maintainable naming convention framework tailored to our project’s requirements.





# Capitalization Standard for Structured AI Collaboration Framework (SACF)

## Objective

The purpose of this standard is to define clear, consistent, and unambiguous capitalization rules that can be easily interpreted by both human users and artificial intelligence systems. This ensures that all documentation within the SACF project remains universally understandable, maintains semantic clarity, and supports advanced AI parsing and collaboration.

---

## General Principles

- **Follow American English capitalization rules** as a foundation.
- **Prioritize clarity over convention**: Capitalization must never be the sole method for conveying meaning.
- **Consistency is critical**: Apply the same rules across all documents, code, UI references, and communications.
- **Minimize unnecessary capitalization** to enhance readability for humans and parsing efficiency for AI.

---

## Detailed Guidelines

### 1. Sentence Case Usage
- Use **sentence case** for all document titles, section headings, table headers, captions, and callouts.
- Only capitalize:
  - The first word of the title or heading.
  - Proper nouns and officially capitalized terms.
- **Do not** end titles or headings with a period.

> **Example:**
> - Correct: "Naming conventions in structured AI projects"
> - Incorrect: "Naming Conventions In Structured AI Projects."

### 2. Avoid Unnecessary Capitalization
- Before capitalizing a word, verify if it is truly necessary (proper noun, official name, beginning of a sentence).
- **Do not** rely on capitalization to create semantic differences (e.g., "Pod" vs. "pod").

### 3. Handling Official Names and Code References
- Retain official capitalization for:
  - Product names (e.g., TensorFlow, GitHub)
  - Code identifiers (e.g., `MainController`, `SensorManager`)
  - Industry standards (e.g., ISO 9001)
- Use code font (`code formatting`) for code-related text.

### 4. Restrictions on Capitalization Forms
- **All-uppercase**:
  - Use only for acronyms, abbreviations, and official branding that require it.
- **Camel case**:
  - Use only for official names or code references, not for general document text.
- **No stylistic casing names** (e.g., "camel case", "snake case") in explanations; instead, provide direct formatting instructions with examples.

> **Example:**
> - Recommended: "Write attribute names without spaces, capitalizing the first letter of each word, such as `UserProfile`."

### 5. After Colons
- Start the text after a colon with a lowercase letter unless:
  - It is a proper noun.
  - It is a heading.
  - It is a quotation.
  - It follows a label like **Caution** or **Note**.

### 6. Lists, Figures, Glossaries, and Tables
- Use sentence case for:
  - List items (whether numbered or bulleted)
  - Captions under figures and diagrams
  - Glossary entries and definitions
  - Table contents, headings, labels, and captions

### 7. Internal and External References
- When referencing a title within our documentation, always use sentence case, regardless of how the original title appeared.
- When referencing external works, retain the original capitalization.

---

## Scope Adjustments Compared to Google Style

| Area | SACF Adaptation | Reason |
|:---|:---|:---|
| Kubernetes-specific examples (e.g., "Pod") | Removed and generalized | To maintain domain neutrality and maximize accessibility for diverse users and AIs |
| Heavy focus on HTML and semantic tags | Omitted | Markdown is the primary format, and external HTML guidelines are less relevant |
| Reference to Google's word lists | Replaced with SACF internal glossary | To ensure full internal consistency and future adaptability |
| Complex rules for hyphenated words | Simplified | Prioritizing clarity and efficiency over grammatical edge cases |

---

## Final Notes

This capitalization standard will evolve alongside the SACF project's expansion. All contributors are expected to strictly adhere to these guidelines to uphold the project's commitment to clarity, precision, and standardized collaboration between humans and artificial intelligence systems.

> **Primary Reference:** [Google Developer Documentation Style Guide](https://developers.google.com/style)
> 
> **SACF Core Philosophy:** Build a clear, unambiguous, and standardized bridge between humans and artificial intelligence.
