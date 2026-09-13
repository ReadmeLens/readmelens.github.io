ReadmeLens v0.11.3

Fixes Mermaid diagrams never finishing rendering.

- Every diagram has hung on its loading spinner forever since v0.11.0
  — a project-config bug left mermaid.min.js out of where the app
  looked for it, so every render failed before it could start
- Links that are a whole line by themselves (a TOC entry, a bare
  reference link) now show a pointing-hand cursor on hover

