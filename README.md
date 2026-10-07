# 7cmd

**Status: SKELETON — no application code exists yet.**

## What this repo is

Intended project (per repo description): **"7cmd creates a script, chmod +x, edits, runs, and logs it instantly."**
A CLI/script-runner tool concept.

## What exists

- Agent-runtime policy files only: `AGENTS.md`, `CLAUDE.md`, `GEMINI.md`, `.github/copilot-instructions.md`
- All point to the canonical skills library: https://github.com/coden607/skills
- Single commit on `main`

## Promised vs missing

| Promised (description) | Status |
|---|---|
| Script creation + `chmod +x` flow | ❌ no code |
| Edit / run / log pipeline | ❌ no code, no CLI entry point |
| Any buildable artifact | ❌ no `package.json`, no source |

## Next steps to make this real

1. Choose implementation (Node CLI is the natural fit).
2. Implement: `7cmd new <name>` → creates, chmods, opens editor, runs, appends to a run log.
3. This is a **server/CLI tool**, not a static site — GitHub Pages is not an appropriate host. Needs-host: any machine/npm, no env vars required unless log shipping is added.

_Audited by factory wave2, 2026-10-08._
