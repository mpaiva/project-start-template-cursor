# Source Directory Instructions

This directory is reserved for your project's source code. Please follow these guidelines:

## 1. Structure & Organization

- Organize code into **feature-based modules** or by responsibility (e.g., `api/`, `models/`, `services/`, etc.).
- **Never allow a file to exceed 500 lines**. If a file grows too large, refactor it into smaller modules.
- Use **clear, consistent naming conventions** as described in the main `README.md` and `docs/planning/architecture.md`.

## 2. Coding Standards

- **Primary language:** Python (PEP8 compliant, formatted with `black`).
- Use **type hints** throughout.
- Use **`pydantic`** for data validation.
- For APIs, use **FastAPI** and follow RESTful principles.
- For database access, use **SQLAlchemy** or **SQLModel**.

## 3. Accessibility & Compliance

- All code must comply with **WCAG 2.2 AA** accessibility standards.
- Reference the [WCAG checklist](../docs/accessibility/wcag-checklist.md) for requirements.
- Use semantic HTML and ARIA attributes if building web interfaces.

## 4. Testing

- All new features must include **unit tests** using **pytest**.
- Place tests in `/tests`, mirroring the structure of `src/`.
- Each function/class/route should have:
  - 1 test for expected use
  - 1 edge case test
  - 1 failure case test

## 5. Documentation

- Add docstrings to every function and class using the Google style.
- Comment non-obvious code and add `# Reason:` comments for complex logic.
- Update the main `README.md` and relevant docs when adding features or changing dependencies.

## 6. AI & Prompt Logging

- Log all AI prompts and responses in `PROMPTS.md`.
- Follow `.cursor/rules/` for backend, frontend, and general standards.

## 7. Security & Configuration

- Use environment variables for secrets/configuration.
- Never commit real secrets or API keys.
