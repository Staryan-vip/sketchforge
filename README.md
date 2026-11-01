# SketchForge

**Draw it, say it, ship it — turn a hand-drawn sketch and a voice note into a working full-stack app in minutes.**

SketchForge is a Kiroween 2026 entry in the **Frankenstein** category. It stitches together three things that do not normally live in one flow: hand-drawn sketch input, voice-note intent, and Kiro's spec-driven agentic coding — so an idea can go from a rough drawing to a runnable prototype with a live preview, instead of stopping at a static mockup.

## What it does

1. Draw screens on a canvas, or upload a photo of a paper sketch.
2. Record or type a short voice note explaining what the app should do.
3. SketchForge produces an editable spec (requirements, design, tasks).
4. It builds a runnable prototype and shows a live preview.
5. Iterate by chatting, for example: "make the signup form add email verification."

## Try the starter prototype

Open `index.html` in a browser, or serve the repo locally:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 and try the sketch canvas, voice-note field, and spec preview. This starter prototype demonstrates the sketch + voice + spec flow in the browser. The full Next.js implementation is tracked in `.kiro/specs/sketchforge/tasks.md`.

## How it was built with Kiro

- **Specs** — `.kiro/specs/sketchforge/` holds requirements, design, and tasks. The spec is shown before code generation, so the plan can be corrected first.
- **Steering** — `.kiro/steering/product.md`, `tech.md`, and `structure.md` keep product, tech, and structure consistent.
- **Hooks** — `.kiro/hooks/` automates formatting and checks on save.
- **MCP** — code generation is connected to GitHub and preview deployment, so export and redeploy are real actions in the full implementation.

See `docs/KIRO_USAGE.md` for the full Kiro usage breakdown.

## Project links

- Kiroween 2026: https://kiroween.devpost.com/
- Category: Frankenstein
- License: MIT, see `LICENSE`

## Status

Starter prototype (v0.1) for Kiroween 2026. See `tasks.md` for what is done, what is in progress, and what is next.
