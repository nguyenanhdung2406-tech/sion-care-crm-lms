# Architecture — SION CARE CRM LMS V1

## Current V1

V1 is a browser-based pilot. The UI and workflow live in `index.html`. Data persistence is localStorage.

```text
Browser
  -> index.html
  -> UI state
  -> localStorage
```

## Target production architecture

```text
Browser
  -> Web UI
  -> Authentication
  -> API / server logic
  -> PostgreSQL
  -> File storage
```

The production migration must preserve the business rules in `docs/WORKFLOW.md` and the editable-content boundary in `docs/EDITING.md`.