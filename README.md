# Project Starter Template for Cursor IDE

<img src="https://img.shields.io/badge/Accessibility-WCAG%202.2%20AA-brightgreen" alt="WCAG 2.2 AA Compliant">
<img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python 3.8+">
<img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License">

A comprehensive GitHub Template Repository designed to kickstart your projects with accessibility, planning, and AI-powered development workflow in mind. This template makes it easy to reuse a robust starter setup across multiple projects with just a single click.

## 💬 Need Help? Interactive Chat Support

Get instant help and guidance for this repository using the [gitMCP Chat](https://gitmcp.io/mpaiva/project-starter-template-cursor/chat).

[![Open Chat](https://img.shields.io/badge/Chat-gitMCP-blue?logo=github)](https://gitmcp.io/mpaiva/project-starter-template-cursor/chat)

**Example Questions to Ask the Chat:**

- "How do I set up this project locally?"
- "What are the main features of this repository?"
- "Can you explain the folder structure?"
- "How do I run the tests?"
- "Where can I find the API documentation?"
- "What coding standards should I follow here?"
- "How do I contribute a new feature?"
- "Who do I contact for support?"

## 🌟 Overview

This template provides a structured foundation for any new project, with a specific focus on accessibility compliance and enhancing your AI development workflow in Cursor IDE. It includes essential scaffolding, configuration files, and development best practices to get you started quickly and efficiently.

### Why Use This Template?

1. **Time-Saving**: Eliminates hours of initial setup and configuration
2. **Best Practices**: Built-in adherence to modern development standards
3. **Accessibility**: WCAG 2.2 AA compliance from day one
4. **AI-Enhanced**: Optimized for Cursor IDE's AI capabilities
5. **Documentation**: Comprehensive templates and guidelines

## ✨ Features

### Development Environment

- **Pre-configured Cursor IDE Setup**: Optimized settings and configurations for Cursor's AI capabilities
- **Code Quality Tools**: Pre-configured with Black, Flake8, MyPy, and Prettier
- **Type Safety**: Built-in type checking and validation
- **Testing Framework**: Pytest setup with example tests

### Accessibility & Standards

- **Accessibility First**: Built-in scaffolding for WCAG 2.2 AA compliance
- **Documentation Templates**: Ready-to-use templates for all project phases
- **Code Style**: Consistent formatting and linting rules
- **Best Practices**: Industry-standard development patterns

### Project Management

- **Planning Structure**: Templates for project documentation and planning
- **Task Tracking**: Integrated task management templates
- **Version Control**: Pre-configured Git setup
- **CI/CD Ready**: GitHub Actions workflow templates

## 🛠️ Project Structure

```
project-starter-template-cursor/
│
├── .cursor/                   # Cursor IDE configuration
│   ├── mcp.json               # Cursor project metadata/config (gitignored, local only)
│   ├── mcp.json_example       # Example MCP config (commit this, no secrets)
│   └── rules/                 # Custom rules for Cursor AI
│       ├── backend/           # Backend-specific AI rules
│       │   └── api-standards.mdc
│       ├── frontend/          # Frontend-specific AI rules
│       │   └── ui-guidelines.mdc
│       └── general.mdc        # General project rules
│
├── docs/                      # Project documentation
│   ├── planning/              # Planning documents (e.g., architecture.md)
│   └── accessibility/         # Accessibility guidelines (e.g., wcag-checklist.md)
│
├── src/                       # Source code (empty by default)
│
├── .gitignore                 # Git ignore configuration
├── LICENSE                    # Project license
├── PROMPTS.md                 # Log of AI prompts and responses
├── PRD.md                     # Product requirements document
├── ROADMAP.md                 # Project roadmap
└── README.md                  # Project documentation (this file)
```

## 🚀 Getting Started

### Using This Template

1. Click the "Use this template" button at the top of this repository
2. Name your new repository and provide a description
3. Clone your new repository to your local machine
4. Open the project in Cursor IDE

After completing these steps, see the **"Customizing the Template"** section below for guidance on adapting the template to your project's needs.

### Prerequisites

- [Cursor IDE](https://cursor.sh/) installed on your machine
- Git for version control
- Any additional project-specific dependencies

## 🔍 AI Workflow with Cursor

This template is optimized to work with Cursor's AI capabilities to enhance your development workflow:

1. **AI Context Rules**: The `.cursor/rules/` directory contains modular rule files for backend, frontend, and general project standards. These provide context to Cursor's AI about your project structure, coding standards, and accessibility requirements.

   - `backend/api-standards.mdc`: Backend API and code standards
   - `frontend/ui-guidelines.mdc`: Frontend UI and accessibility standards
   - `general.mdc`: General project rules and conventions

2. **Consistent Code Generation**: These rules help maintain coding standards, accessibility best practices, and architectural consistency when using AI for code generation and review.

3. **Prompt Logging**: All AI prompts and responses are logged in `PROMPTS.md` for transparency and traceability.

4. **Accessibility Compliance**: AI assistance is configured to suggest accessible implementations and flag potential accessibility issues, supporting WCAG 2.2 AA compliance.

## ♿ Accessibility Commitment

All work created using this template must comply with [WCAG 2.2 AA accessibility guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/). The template includes:

- Accessibility checklists
- WCAG 2.2 AA compliance structure
- Best practices for maintaining accessibility throughout development

## 📝 Customizing the Template

1. **Update Documentation**: Edit `README.md`, `PRD.md`, and `ROADMAP.md` with your project-specific information and requirements.
2. **Adjust AI Rules**: Modify or extend the modular rule files in `.cursor/rules/` to fit your project's needs:
   - `backend/api-standards.mdc` for backend/API standards
   - `frontend/ui-guidelines.mdc` for frontend/UI and accessibility standards
   - `general.mdc` for general project rules and conventions
3. **Add Configuration Files**: Include any additional configuration files required for your tech stack (e.g., linter configs, CI/CD workflows).
4. **Expand Documentation**: Add or update files in `docs/planning/` and `docs/accessibility/` to reflect your project's architecture, planning, and accessibility requirements.
5. **Maintain Accessibility**: Update accessibility guidelines and checklists in `docs/accessibility/` as your project evolves.
6. **Log AI Interactions**: Continue to log all AI prompts and responses in `PROMPTS.md` for transparency.

## 🧩 MCP (Model Context Protocol) Integration

### What is MCP?

MCP (Model Context Protocol) is a standard for connecting your development environment to external tools, APIs, and AI services in a modular, extensible way. It allows you to run context-aware commands, access documentation, perform code analysis, and more—directly from your IDE.

### Included MCP Tools

This template comes pre-configured with several MCP servers in `.cursor/mcp.json`:

- **github**: Access GitHub APIs (requires a personal access token)
- **project-starter-template-cursor Docs**: Fetches documentation for this template
- **context7-mcp**: Connects to Context7 for advanced context and documentation
- **sequential-thinking**: Enables step-by-step, chain-of-thought AI reasoning
- **perplexity-ask**: Integrates with Perplexity AI (requires API key)
- **playwright**: Automated browser testing via Playwright
- **clear-thought**: Advanced context and reasoning tools
- **a11y-accessibility**: Accessibility analysis and compliance checks

### Adding or Configuring MCP Tools

- Edit `.cursor/mcp.json` to add, remove, or configure MCP servers.
- For tools that require API keys or tokens (e.g., GitHub, Perplexity), replace the placeholder values (`<YOUR_TOKEN>`, `YOUR_API_KEY_HERE`) with your actual credentials.

### Security Best Practices

- **Never commit real API keys or secrets to your public repository.**
- Use environment variables or a local `.env` file (which is already gitignored) to store sensitive information.
- In `.cursor/mcp.json`, you can reference environment variables (e.g., `"GITHUB_PERSONAL_ACCESS_TOKEN": "${GITHUB_PERSONAL_ACCESS_TOKEN}"`).
- If you need to share the template, always reset or remove sensitive values before pushing to a public repo.
- **Commit `.cursor/mcp.json_example` as a template for required config structure.**
- **Commit `.env_example` as a template for required environment variables.**
- **Add `.cursor/mcp.json` and `.env` to your `.gitignore`.**

**Example: Using Environment Variables in mcp.json**

```json
"env": {
  "GITHUB_PERSONAL_ACCESS_TOKEN": "${GITHUB_PERSONAL_ACCESS_TOKEN}"
}
```

Then, set the variable in your local `.env` file (see `.env_example`) or export it in your shell.

#### Setup Steps

1. Copy `.cursor/mcp.json_example` to `.cursor/mcp.json`:
   ```sh
   cp .cursor/mcp.json_example .cursor/mcp.json
   ```
2. Copy `.env_example` to `.env` and add your secrets:
   ```sh
   cp .env_example .env
   ```
3. Ensure `.cursor/mcp.json` and `.env` are listed in `.gitignore`.

## 🤝 Contributing

Contributions to improve this template are welcome! Please feel free to submit a pull request or open an issue.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Created by [Marcelo Paiva](https://github.com/mpaiva)
