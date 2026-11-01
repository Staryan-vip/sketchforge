# Kiro Usage

## Products and features used
- **Kiro IDE**: primary development environment for this repo.
- **Specs**: `.kiro/specs/sketchforge/` — requirements, design, and tasks drive implementation, and the spec is shown to the user before code generation.
- **Steering**: `.kiro/steering/product.md`, `tech.md`, `structure.md` — keep product, tech, and structure consistent.
- **Hooks**: `.kiro/hooks/format-on-save.json` — automate formatting and checks on save.
- **MCP**: connected to GitHub and preview deployment, so export and redeploy are real actions in the full implementation.
- **Vibe coding vs. spec coding**: vibe coding was used for quick exploration; spec coding was used for the actual build, because the plan stays explicit, reviewable, and fixable.

## What Kiro changed
Without specs, sketch + voice input produced plausible but wrong apps. With an editable spec in the middle, wrong interpretations can be corrected before code is generated, and frontend, backend, and data model stay consistent.
