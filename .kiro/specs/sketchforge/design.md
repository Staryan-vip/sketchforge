# SketchForge — Design

## Flow
1. Input: canvas sketch and/or sketch upload + voice note.
2. Interpret: sketch layout + voice intent -> structured spec (screens, components, flows, data).
3. Review: user edits the spec (requirements, design, tasks).
4. Build: spec -> frontend, backend, and data model -> live preview.
5. Iterate: chat change -> spec update -> rebuild -> new preview.
6. Export: source + README + license -> GitHub.

## Components
- SketchCanvas: drawing, upload, and layout notes.
- VoiceNote: recording / typed note, transcribed to intent text.
- SpecEditor: editable requirements, design, and task list.
- Preview: runnable prototype in an iframe / preview pane.
- Exporter: GitHub export and redeploy actions.

## Data model (prototype)
- Project: id, name, sketch (canvas data / image reference), voiceNote (text), spec (JSON), preview (generated app reference).
- Spec: screens[], features[], flows[], dataModel[].

## Frankenstein rationale
Sketch recognition, voice understanding, and agentic coding are unrelated technologies on their own. SketchForge stitches them together with a human-readable spec in the middle, which is what makes the combination controllable and explainable.
