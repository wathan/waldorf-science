# CLAUDE.md

## Repository structure

- `docs/` — published GitHub Pages site (HTML deliverables only); do not put source materials here.
- `source/` — source markdowns and reference PDFs behind the published HTMLs.
- `adr/` — Architecture Decision Records.
- `agent-docs/` — agent / skill instructions (Issue tracker, Triage labels, Domain docs).
- `CONTEXT.md` — project glossary (canonical terminology).

## Agent skills

### Issue tracker

Local markdown files under `.scratch/<feature>/`. See `agent-docs/issue-tracker.md`.

### Triage labels

Five canonical roles, default names. See `agent-docs/triage-labels.md`.

### Domain docs

Single-context: `CONTEXT.md` + `adr/` at repo root. See `agent-docs/domain.md`.
