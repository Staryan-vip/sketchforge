# Structure Steering

```
/
├── README.md
├── LICENSE
├── index.html            # Starter prototype (canvas + voice note + spec preview)
├── docs/
│   ├── KIRO_USAGE.md     # How Kiro was used
│   └── VIDEO_SCRIPT.md   # 3-minute demo video outline
└── .kiro/
    ├── steering/
    │   ├── product.md
    │   ├── tech.md
    │   └── structure.md
    ├── specs/
    │   └── sketchforge/
    │       ├── requirements.md
    │       ├── design.md
    │       └── tasks.md
    └── hooks/
        └── format-on-save.json
```

## Rules
- `.kiro/` must stay in the repository root and must not be gitignored.
- Specs live under `.kiro/specs/<feature>/` as requirements, design, and tasks.
- Docs that explain Kiro usage, demo, and submission live under `docs/`.
