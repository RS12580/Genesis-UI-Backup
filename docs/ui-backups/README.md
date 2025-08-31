# UI Backups & Restore

This folder tracks lean UI backups and the exact steps to restore **v1.0.6** (and later).

## What lives here
- `Genesis-UI-Complete-V1.0.6-LEAN.zip` (no `node_modules`, no `.next`)
- (Optional) `checksums.txt` if you generate one

## Use cases

### A) Restore from a zip _inside this repo_ (preferred)
1. Ensure the zip is **< 100 MB** (no `node_modules`, `.next`, `dist`, etc.).
2. Path: `docs/ui-backups/Genesis-UI-Complete-V1.0.6-LEAN.zip`
3. Extract into the UI app folder that exists in this repo:
   - If `genesis-ui-pages/` exists → extract there
   - Else if `apps/ui/` exists → extract there
   - If the zip also contains `genesis-control-panel/`, place it at **repo root** (sibling to the UI folder); **no double-nesting**
4. Install deps and verify routes:
   `/controls /launch /tokenizer /rendr /signal /vault /actview /metrics /nexus`

**Builder prompt**:
