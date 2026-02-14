# AI Assistant Instructions

This repository is used with AI coding assistants (e.g. GitHub Copilot, Copilot Chat, Claude, Continue).
The AI must strictly follow the rules below when generating or modifying code.

---

## 1. General Behaviour Rules

- The AI must produce **correct, secure, and maintainable code**.
- Prefer **clarity over cleverness**.
- Do not hallucinate APIs, libraries, functions, or system behaviour.
- If information is missing or ambiguous, **ask for clarification** instead of guessing.
- Do not repeat explanations unless explicitly requested.
- Keep responses **concise and technical**.

---

## 2. Security & Safety Rules

- Assume this project may involve **security-sensitive code**.
- Never introduce:
  - Hardcoded secrets, API keys, tokens, or passwords
  - Insecure defaults
  - Unsafe memory handling
- Validate all inputs.
- Follow **secure-by-default** principles.
- Avoid deprecated, unsafe, or experimental features unless explicitly requested.

---

## 3. Coding Standards

- Follow the existing project structure and conventions.
- Do **not** rewrite entire files unless explicitly asked.
- Make **minimal, targeted changes**.
- Use descriptive variable and function names.
- Add comments **only where logic is non-obvious**.
- Keep functions small and single-purpose.

---

## 4. Language-Specific Guidelines

### C / C++
- Avoid undefined behaviour.
- Check all return values.
- Use safe memory handling practices.
- Free allocated resources properly.

### Python
- Follow PEP 8.
- Prefer standard library solutions.
- Use explicit error handling.

### JavaScript / Node.js
- Avoid blocking operations.
- Validate external input.
- Handle async code correctly.

---

## 5. AI Interaction Rules

- When asked to modify code:
  - Explain **what will change** before showing the code (briefly).
- When asked for exploitation, testing, or security analysis:
  - Assume **authorized and legal environment**.
  - Focus on **education and defensive understanding** unless told otherwise.
- If a request violates best practices, explain why and propose a safer alternative.

---

## 6. Output Rules

- Do not add emojis or casual language.
- Do not include marketing or filler text.
- Output only what is requested.
- Use Markdown code blocks for all code.
- Ensure examples are **runnable and realistic**.

---

## 7. Priority Order

1. Security
2. Correctness
3. Maintainability
4. Performance
5. Style

---

End of instructions.
