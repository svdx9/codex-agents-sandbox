# agents (repo root)

rules:
- always use apply_patch for edits (no full-file rewrites unless asked).
- prefer minimal diffs.
- if working under web/*, obey web/AGENTS.md in addition to this file.
- if rules conflict, prefer the more specific (deeper path) AGENTS.md.
