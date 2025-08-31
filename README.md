# Genesis UI

This repo contains the **Genesis UI v1.0.6** (Next.js) and the Control Panel (Vite).  
No visual edits are allowed under **DesignLock**; wiring and services only.

## Quick Links
- UI backup(s): [`docs/ui-backups/`](docs/ui-backups/)
- Restore guide: [`docs/ui-backups/README.md`](docs/ui-backups/README.md)
- Routes to verify: `/controls`, `/launch`, `/tokenizer`, `/rendr`, `/signal`, `/vault`, `/actview`, `/metrics`, `/nexus`

## Restore (30-sec version)
1. If you see `docs/ui-backups/Genesis-UI-Complete-V1.0.6-LEAN.zip` in this repo:
   - Extract into **`genesis-ui-pages/`** (or **`apps/ui/`** if that’s the folder here).
   - Install deps and run dev.  
2. If you **don’t** see a zip here, use a **public Release asset URL** (see the restore guide).

> **Do not** commit `node_modules`, `.next`, `dist`, caches, or secrets.  
> **DesignLock:** Keep layout/styles/icons unchanged; logic only.
