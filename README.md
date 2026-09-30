# Awesome Subagents

Copy-paste subagent templates for **Claude Code** (`.claude/agents/`) and **Cursor** (`.cursor/agents/`).

Every template is available in both formats, checked against the official docs:
[Claude Code subagents](https://code.claude.com/docs/en/sub-agents) · [Cursor subagents](https://cursor.com/docs/subagents)

👉 **Browse all 33 with both formats + an in-browser Claude ↔ Cursor converter:**
https://bilallabs.vercel.app/ai/subagents

## Contents

### Review & quality
- [Code Reviewer](https://bilallabs.vercel.app/ai/subagents/code-reviewer) · [Claude](claude/code-reviewer.md) · [Cursor](cursor/code-reviewer.md) — read-only review of your diff, reported by severity
- [Security Auditor](https://bilallabs.vercel.app/ai/subagents/security-auditor) · [Claude](claude/security-auditor.md) · [Cursor](cursor/security-auditor.md) — auth, payments, uploads, user input
- [Performance Reviewer](https://bilallabs.vercel.app/ai/subagents/performance-reviewer) · [Claude](claude/performance-reviewer.md) · [Cursor](cursor/performance-reviewer.md) — N+1 queries, re-renders, blocking I/O
- [Verifier](https://bilallabs.vercel.app/ai/subagents/verifier) · [Claude](claude/verifier.md) · [Cursor](cursor/verifier.md) — independently checks that work actually meets the request
- [Secrets Scanner](https://bilallabs.vercel.app/ai/subagents/secrets-scanner) · [Claude](claude/secrets-scanner.md) · [Cursor](cursor/secrets-scanner.md) — API keys, tokens, private keys in staged changes
- [Accessibility Auditor](https://bilallabs.vercel.app/ai/subagents/accessibility-auditor) · [Claude](claude/accessibility-auditor.md) · [Cursor](cursor/accessibility-auditor.md) — WCAG 2.2 AA
- [Dependency Auditor](https://bilallabs.vercel.app/ai/subagents/dependency-auditor) · [Claude](claude/dependency-auditor.md) · [Cursor](cursor/dependency-auditor.md)
- [Dead Code Finder](https://bilallabs.vercel.app/ai/subagents/dead-code-finder) · [Claude](claude/dead-code-finder.md) · [Cursor](cursor/dead-code-finder.md)

### Testing & debugging
- [Debugger](https://bilallabs.vercel.app/ai/subagents/debugger) · [Claude](claude/debugger.md) · [Cursor](cursor/debugger.md)
- [Test Runner](https://bilallabs.vercel.app/ai/subagents/test-runner) · [Claude](claude/test-runner.md) · [Cursor](cursor/test-runner.md)
- [Test Writer](https://bilallabs.vercel.app/ai/subagents/test-writer) · [Claude](claude/test-writer.md) · [Cursor](cursor/test-writer.md)
- [CI Failure Fixer](https://bilallabs.vercel.app/ai/subagents/ci-fixer) · [Claude](claude/ci-fixer.md) · [Cursor](cursor/ci-fixer.md)
- [Log Analyzer](https://bilallabs.vercel.app/ai/subagents/log-analyzer) · [Claude](claude/log-analyzer.md) · [Cursor](cursor/log-analyzer.md)
- [TypeScript Type Fixer](https://bilallabs.vercel.app/ai/subagents/type-fixer) · [Claude](claude/type-fixer.md) · [Cursor](cursor/type-fixer.md)
- [Lint Fixer](https://bilallabs.vercel.app/ai/subagents/lint-fixer) · [Claude](claude/lint-fixer.md) · [Cursor](cursor/lint-fixer.md)

### Planning & code changes
- [Codebase Explorer](https://bilallabs.vercel.app/ai/subagents/codebase-explorer) · [Claude](claude/codebase-explorer.md) · [Cursor](cursor/codebase-explorer.md)
- [Architect / Planner](https://bilallabs.vercel.app/ai/subagents/architect) · [Claude](claude/architect.md) · [Cursor](cursor/architect.md)
- [Refactorer](https://bilallabs.vercel.app/ai/subagents/refactorer) · [Claude](claude/refactorer.md) · [Cursor](cursor/refactorer.md)
- [Upgrade Assistant](https://bilallabs.vercel.app/ai/subagents/upgrade-assistant) · [Claude](claude/upgrade-assistant.md) · [Cursor](cursor/upgrade-assistant.md)
- [API Designer](https://bilallabs.vercel.app/ai/subagents/api-designer) · [Claude](claude/api-designer.md) · [Cursor](cursor/api-designer.md)

### Data & infra
- [Database Migration Reviewer](https://bilallabs.vercel.app/ai/subagents/migration-reviewer) · [Claude](claude/migration-reviewer.md) · [Cursor](cursor/migration-reviewer.md)
- [Read-Only Database Query](https://bilallabs.vercel.app/ai/subagents/db-reader) · [Claude](claude/db-reader.md) · [Cursor](cursor/db-reader.md)
- [Dockerfile Reviewer](https://bilallabs.vercel.app/ai/subagents/dockerfile-reviewer) · [Claude](claude/dockerfile-reviewer.md) · [Cursor](cursor/dockerfile-reviewer.md)

### Docs & git
- [Docs Writer](https://bilallabs.vercel.app/ai/subagents/docs-writer) · [Claude](claude/docs-writer.md) · [Cursor](cursor/docs-writer.md)
- [Commit Message Writer](https://bilallabs.vercel.app/ai/subagents/commit-message-writer) · [Claude](claude/commit-message-writer.md) · [Cursor](cursor/commit-message-writer.md)
- [Pull Request Description Writer](https://bilallabs.vercel.app/ai/subagents/pr-description-writer) · [Claude](claude/pr-description-writer.md) · [Cursor](cursor/pr-description-writer.md)
- [Changelog Writer](https://bilallabs.vercel.app/ai/subagents/changelog-writer) · [Claude](claude/changelog-writer.md) · [Cursor](cursor/changelog-writer.md)
- [AGENTS.md Writer](https://bilallabs.vercel.app/ai/subagents/agents-md-writer) · [Claude](claude/agents-md-writer.md) · [Cursor](cursor/agents-md-writer.md)

### Framework-specific
- [Next.js App Router Reviewer](https://bilallabs.vercel.app/ai/subagents/nextjs-reviewer) · [Claude](claude/nextjs-reviewer.md) · [Cursor](cursor/nextjs-reviewer.md)
- [React Component Reviewer](https://bilallabs.vercel.app/ai/subagents/react-component-reviewer) · [Claude](claude/react-component-reviewer.md) · [Cursor](cursor/react-component-reviewer.md)
- [Frontend UI Reviewer](https://bilallabs.vercel.app/ai/subagents/frontend-reviewer) · [Claude](claude/frontend-reviewer.md) · [Cursor](cursor/frontend-reviewer.md)
- [Python Reviewer](https://bilallabs.vercel.app/ai/subagents/python-reviewer) · [Claude](claude/python-reviewer.md) · [Cursor](cursor/python-reviewer.md)
- [i18n Checker](https://bilallabs.vercel.app/ai/subagents/i18n-checker) · [Claude](claude/i18n-checker.md) · [Cursor](cursor/i18n-checker.md)

## Quick start

**Claude Code** — save as `.claude/agents/code-reviewer.md` (or `~/.claude/agents/` for all projects):

```markdown
---
name: code-reviewer
description: "Reviews uncommitted or branch changes for bugs, regressions and missing tests. Use proactively after finishing a feature and before committing."
tools: Read, Grep, Glob, Bash
model: sonnet
---

You are a strict senior code reviewer for this repository. ...
```

**Cursor** — save as `.cursor/agents/code-reviewer.md` (or `~/.cursor/agents/`):

```markdown
---
name: code-reviewer
description: "Reviews uncommitted or branch changes for bugs, regressions and missing tests. Use proactively after finishing a feature and before committing."
model: inherit
readonly: true
---

You are a strict senior code reviewer for this repository. ...
```

## Format cheatsheet

| Field | Claude Code | Cursor |
|---|---|---|
| `name` | required | optional (defaults to file name) |
| `description` | required — the delegation trigger | optional, but needed for auto-delegation |
| `tools` / `disallowedTools` | allowlist / denylist | — (use `readonly`) |
| `readonly` | — | `true` blocks edits and state-changing shell commands |
| `model` | `sonnet`, `opus`, `haiku`, `inherit` | `inherit` or a Cursor model ID |
| background | `background: true` | `is_background: true` |

Tips:
- Write the `description` as *when* to use it: "Use proactively after …" delegates far more reliably than a generic summary.
- Quote the `description` if it contains `: ` — otherwise the YAML is invalid.
- Cursor also loads `.claude/agents/`, but ignores `tools`. For read-only agents keep a Cursor copy with `readonly: true`.

## Contributing

PRs welcome: one `.md` file per agent in `claude/` and `cursor/`, with a description that says when to delegate. Keep reviewers read-only.

## License

CC0 — copy freely.
