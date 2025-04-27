# Text Formatting Standards

This document outlines the formatting rules for writing technical documentation in our project. Proper formatting enhances readability, comprehension, and the professional appearance of our content.

Follow these standards consistently across all documents, code comments, UI texts, and user manuals.

---

# Headings

- Use clear, descriptive headings.
- Follow sentence case for all headings.
  - Correct: "Text formatting standards"
  - Incorrect: "Text Formatting Standards"
- Maintain a logical hierarchy:
  - `#` for main titles
  - `##` for sections
  - `###` for subsections

---

# Lists

- Use bullet points (`-`) for unordered items.
- Use numbers (`1.`, `2.`, `3.`) for ordered steps or procedures.
- Keep list items concise and parallel (similar grammatical structure).

**Example:**
```markdown
- Install the required packages.
- Configure the settings.
- Launch the application.
```

**Numbered Example:**
```markdown
1. Connect the device to power.
2. Turn on the system.
3. Run the initial diagnostics.
```

---

# Bold and Italic

- Use **bold** for:
  - Important concepts
  - UI elements (buttons, labels, menus)
- Use *italic* for:
  - Document names
  - Emphasis on specific terms or cautions

**Example:**
```markdown
Click **Submit** to complete the form.
Refer to the *Installation Guide* for details.
```

---

# Code Formatting

- Use backticks (\`) for inline code.
  - Example: `sudo apt update`
- Use triple backticks (\`\`\`) for code blocks.
- Specify the language for syntax highlighting when possible.

**Example:**
```markdown
```bash
sudo apt install nginx
```
```

---

# Blockquotes

- Use blockquotes (`>`) to highlight important notes, tips, or warnings.

**Example:**
```markdown
> **Note:** Restart the system after applying updates.
```

- Always bold the leading keyword (Note, Warning, Tip, etc.).

---

# Links

- Create meaningful links.
- Avoid generic text like "click here".

**Good Example:**
```markdown
For setup instructions, see the [installation guide](./installation-guide.md).
```

**Bad Example:**
```markdown
Click [here](./installation-guide.md) for setup.
```

---

# Tables

- Align pipes (`|`) and pad columns for clean appearance.
- Keep table content concise.

**Example:**
```markdown
| Term             | Definition                          |
|------------------|-------------------------------------|
| API              | Application Programming Interface  |
| HMI              | Human-Machine Interface             |
```

---

# Examples of Good vs Bad Formatting

| Aspect            | Good Example                                  | Bad Example                                  |
|-------------------|------------------------------------------------|---------------------------------------------|
| Headings          | ## Configure the Server                       | ## Configure The Server                    |
| Lists             | - Clear bullet points                         | *Mixed list styles*                        |
| Code              | `npm install`                                 | npm install                                |
| Links             | [User Guide](./user-guide.md)                 | Click [here](./user-guide.md)              |
| Tables            | Cleanly aligned pipes and columns             | Misaligned pipes causing messy display     |

---

# Final Reminder

**Formatting is invisible guidance.** Proper text formatting allows users to navigate, understand, and trust the documentation easily.

Be meticulous. Consistent formatting reflects our commitment to clarity, professionalism, and human-centered design.

---

# File Location

This document is stored at:
```bash
standards\writing-standards\text-formatting.md
