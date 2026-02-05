# Static preview (Five Server)

This folder is **intentionally static-only** and is meant to be served by the VS Code **Five Server** extension.

## Important notes

- Five Server **will not** execute PHP.
- Five Server **will not** render Laravel Blade templates.
- Use this folder for:
  - HTML/CSS prototypes
  - Static mockups
  - Quick asset previews

## How to run

1. Install the VS Code extension **Five Server**.
2. Open this repository in VS Code.
3. Start Five Server (Command Palette):
   - `Five Server: Start`
   - or click the **Go Live** button (depending on your setup)

It will serve this folder at: http://localhost:5500

## Laravel app (dynamic)

For Laravel routes/controllers/views, run Laravel separately, e.g.:

```bash
PORT=3001 composer run start
```

Then visit: http://localhost:3001
