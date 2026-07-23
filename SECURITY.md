# Security Policy

## Why this repo's security model is unusual

This repository contains no executable code. It is markdown skill files that people load into AI agents like Claude Code and Cursor. No dependencies, no build step, no CI workflows.

That means the surface that matters is **content integrity**: these files become instructions an agent follows. A malicious edit could try to steer someone's agent into harmful actions.

## What counts as a vulnerability here

- Content in a skill that instructs an agent to exfiltrate data, run commands unrelated to the skill's stated purpose, or fetch remote content
- Prompt-injection patterns hidden in the files (encoded text, invisible characters, instructions disguised as examples)
- Anything that misrepresents what a skill does when loaded

## Reporting

Use GitHub's private vulnerability reporting (Security tab → "Report a vulnerability"), or email iabullaisi@gmail.com. Solo maintainer, so expect a first response within a few days. Please keep security reports out of public issues.

## The standing rule for contributions

This pack stays markdown-only. Any pull request adding scripts, workflows, binaries, or remote fetches will be declined regardless of intent. That rule is what keeps the install-and-trust story simple: what you read is all there is.
