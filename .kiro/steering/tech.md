# Tech Steering

## Stack (target)
- Frontend: Next.js, TypeScript, React, Tailwind CSS
- Backend / data for prototypes: lightweight backend and database (Supabase / PostgreSQL in the full implementation)
- Starter prototype in this repo: plain HTML, CSS, and JavaScript in `index.html`, runnable without a build step

## Conventions
- TypeScript-first for the full implementation; keep types explicit.
- Keep generated code readable and editable; no opaque blobs.
- Every feature must be traceable to a spec task in `.kiro/specs/sketchforge/tasks.md`.
- No secrets in the repo. API keys, tokens, and credentials live outside version control.

## Deployment
- Live preview for prototypes.
- Export to a public GitHub repository.
- Full implementation target: Vercel.
