---
report_type: copilot-tools-recommendation
version: 1.0.0
assessment_date: 2025-12-19
project_name: awesome-copilot-fork
detected_technologies:
  - JavaScript/Node.js
  - JSON Schema
  - Markdown
  - GitHub Actions
  - Docker
tools_recommended: 8
tools_installed: 0
status: recommendations-only
---

# Copilot Tools Recommendation Report

## Project: awesome-copilot-fork
## Version: 1.0.0
## Date: 2025-12-19

---

## Detected Technologies

| Technology | Evidence Found |
|------------|----------------|
| JavaScript/Node.js | package.json, package-lock.json |
| JSON Schema | .schemas/*.json |
| Markdown | *.md files throughout |
| GitHub Actions | .github/workflows/*.yml |
| Docker | MCP Server references |

---

## Recommended Tools

| # | Tool | Type | Why Recommended | Status |
|---|------|------|-----------------|--------|
| 1 | debug.agent.md | Agent | Universal debugger |  Pending |
| 2 | create-readme.prompt.md | Prompt | Documentation |  Pending |
| 3 | conventional-commit.prompt.md | Prompt | Commit standards |  Pending |
| 4 | nodejs.instructions.md | Instruction | Detected Node.js |  Pending |
| 5 | json-schema.instructions.md | Instruction | Detected .schemas/ |  Pending |
| 6 | github-actions.instructions.md | Instruction | Detected workflows |  Pending |
| 7 | code-reviewer.agent.md | Agent | PR review quality |  Pending |
| 8 | janitor.agent.md | Agent | Code cleanup |  Pending |

---

## Install Commands

To install recommended tools:

```bash
# Create folders
mkdir -p .github/agents .github/prompts .github/instructions

# Agents
curl -o .github/agents/debug.agent.md https://raw.githubusercontent.com/github/awesome-copilot/main/agents/debug.agent.md
curl -o .github/agents/code-reviewer.agent.md https://raw.githubusercontent.com/github/awesome-copilot/main/agents/code-reviewer.agent.md
curl -o .github/agents/janitor.agent.md https://raw.githubusercontent.com/github/awesome-copilot/main/agents/janitor.agent.md

# Prompts
curl -o .github/prompts/create-readme.prompt.md https://raw.githubusercontent.com/github/awesome-copilot/main/prompts/create-readme.prompt.md
curl -o .github/prompts/conventional-commit.prompt.md https://raw.githubusercontent.com/github/awesome-copilot/main/prompts/conventional-commit.prompt.md
```

---

## Version History

| Version | Date | Recommended | Installed |
|---------|------|-------------|-----------|
| 1.0.0 | 2025-12-19 | 8 tools | 0 |
