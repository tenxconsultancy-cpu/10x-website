# gemini.md — Project Constitution
> ⚖️ This file is LAW. Only update when: a schema changes, a rule is added, or architecture is modified.

---

## 🗺️ Project Overview
| Field | Value |
|---|---|
| **Project Name** | TBD (pending Discovery) |
| **North Star Goal** | TBD |
| **System Pilot** | Antigravity (B.L.A.S.T. Protocol) |
| **Protocol Version** | B.L.A.S.T. v1 / A.N.T. 3-Layer |
| **Initialized** | 2026-02-23 |
| **Status** | 🔴 HALTED — Discovery Phase |

---

## 📁 Directory Structure
```
├── gemini.md           # Project Constitution (this file)
├── .env                # API Keys & Secrets (never committed)
├── architecture/       # Layer 1: SOPs (Markdown)
├── tools/              # Layer 3: Python scripts (deterministic)
└── .tmp/               # Ephemeral intermediate files
```

---

## 📐 Data Schema
> ⛔ LOCKED until Discovery Questions are answered and schema is approved.

### Input Schema
```json
{
  "TBD": "Pending Phase 1 Blueprint discovery"
}
```

### Output Schema (Payload)
```json
{
  "TBD": "Pending Phase 1 Blueprint discovery"
}
```

---

## 🔌 Integrations
| Service | Purpose | Auth Method | Status |
|---|---|---|---|
| TBD | TBD | TBD | ⛔ Not Configured |

---

## 📜 Behavioral Rules
> Rules defined here override any default behavior.

1. *(TBD — defined in Blueprint phase)*

---

## 🚫 Invariants (Never Break These)
1. No code written in `tools/` before Data Schema is approved.
2. All intermediate/temp data goes to `.tmp/` — never pollutes project root.
3. All secrets live in `.env` — never hardcoded.
4. If a tool fails, patch → test → update the SOP in `architecture/`. Never just patch silently.
5. A project is only **"Complete"** when the payload is in its final cloud destination.

---

## 🛠️ Maintenance Log
| Date | Change | Reason |
|---|---|---|
| 2026-02-23 | File initialized | Protocol 0 — Project Bootstrap |
