# Project Instructions

Use these rules when working in this repository with OpenCode or local GitHub Copilot in VS Code.

## Priorities

- Prefer OpenCode for this repo
- Keep changes small, direct, and easy to review
- Preserve existing patterns unless there is a clear reason to change them

## Security

- This repository is for internal use only
- Do not share code, prompts, screenshots, logs, or chat content outside the organization
- Do not expose secrets, tokens, internal URLs, or private data in prompts or generated output
- Do not enable chat sharing in OpenCode
- Do not introduce MCP servers in this repo

## Working Style

- Read the existing code and config before changing things
- Prefer minimal edits over broad rewrites
- Document setup and customization clearly when updating docs
- If you change OpenCode config, remind the user to restart OpenCode

## Repo-Specific Locations

- `opencode.json`: OpenCode configuration
- `.opencode/prompts/frontend.md`: frontend agent prompt
- `.agents/skills/`: local reusable skills
