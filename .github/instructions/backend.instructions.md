---
applyTo: "src/backend/**/*"
---

## Backend Guidelines

- All API endpoints must be defined in the `src/backend/routers/` folder.
- Load example database content from the `database.py` file.
- Log full error details on the server, but only return safe, sanitized, user-facing error messages to the frontend (for example via a `detail` field). Never expose sensitive internal details such as stack traces, raw exception messages, secrets, or infrastructure information.
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If potentially breaking changes are found, mention them to the developer.
