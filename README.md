# Dennis Cooper — Project Showcase Index

This repository backs the public project showcase index. Every entry under
`showcase/` is a Markdown record with YAML front matter. The records are the
source of truth for the website build.

## Structure

```
showcase/
  2024-11-20-policy-scan.md
  2025-02-08-signal-drift-monitor.md
  2025-05-12-neurocast-engine.md
  2025-06-03-streamforge-pipeline.md
  2025-06-18-quantum-route-planner.md
  2025-07-02-tiny-model-zoo.md
```

## Conventions

- One record per showcased work.
- `status` values: `under review`, `pending review`, `published`.
- `repository` is optional and points at a released companion repository.
