# Edge Cases in Capitalization — SACF Standards

This section highlights specific edge cases in capitalization that require careful attention to maintain clarity, consistency, and semantic precision across SACF documentation.

---

## 1. Hyphenated compound words at the beginning of headings or sentences

- **Correct:**  
  "Real-time systems require precise timing."  
  _Reason:_ Only the first element \"Real\" is capitalized unless a proper noun follows.

- **Incorrect:**  
  "Real-Time Systems Require Precise Timing."  
  _Reason:_ Unnecessary title case; violates sentence case rules.

---

## 2. Proper nouns within compound terms

- **Correct:**  
  "Open-source software like Hadoop improves scalability."  
  _Reason:_ \"Hadoop\" is a proper noun and must retain capitalization.

- **Incorrect:**  
  "Open-source Software Like hadoop Improves Scalability."  
  _Reason:_ Misuse of capitalization within a sentence.

---

## 3. Capitalization after colons

- **Correct:**  
  "Important modules include: processor, controller, and buffer."  
  _Reason:_ First word after colon in lowercase unless a proper noun.

- **Incorrect:**  
  "Important modules include: Processor, Controller, and Buffer."  
  _Reason:_ Unnecessary capitalization after the colon.

---

## 4. Lists containing code elements

- **Correct:**  
  - Implement the `DataCollector` module.  
  - Configure the `SensorManager`.  
  - Launch the `MainController`.

  _Reason:_ Code elements are properly enclosed in code formatting.

- **Incorrect:**  
  - Implement the DataCollector module.  
  - Configure the SensorManager.  
  - Launch the MainController.

  _Reason:_ Code elements not highlighted; hard for both human and AI parsing.

---

## 5. Abbreviations and acronyms

- **Correct:**  
  "The system complies with ISO 9001 standards."  
  _Reason:_ Acronyms like \"ISO\" must remain in all caps.

- **Incorrect:**  
  "The system complies with Iso 9001 standards."  
  _Reason:_ Incorrect acronym capitalization.

---

## 6. Headings with colons

- **Correct:**  
  "System modules: overview and initialization"  
  _Reason:_ After a colon in a heading, continue in sentence case.

- **Incorrect:**  
  "System Modules: Overview And Initialization"  
  _Reason:_ Incorrect use of title case after a colon.

---

# Final Note

Edge cases must be handled consistently to ensure that documents are both human-readable and AI-parsable without semantic loss. Every exception must serve the core SACF philosophy: maintaining a clear, unambiguous, and standardized bridge between humans and artificial intelligence.
