---
agent: molty
type: snapshot
project: all
timestamp: 2026-05-07T22:10:00-04:00
links_to:
  - snapshot-molty-2026-05-07-18-47.md
  - daemon-squad-integration-test.md
---

# Molty Project Snapshot — 2026-05-07 22:10 EDT

## Infrastructure
- **Memex API**: NXDOMAIN / unreachable — ~213h down (since ~23:28 Apr 26). HTTP 000. No change.
- **Tailscale webhook receiver** (nabu-pn7g55fc): DOWN ~14 days. 0 active Teams webhook subs since Apr 23. Molty deaf to live Teams events.
- **MeMex upstream**: No commits from Joerg/Coconut in 3+ days.

## Active Projects

### Boswell N.B (Recording Ingest)
- **Status**: Blocked on Task #5 — Graph scope verification (Chris must toggle `settings.integrations.recordings.enabled = true`, restart, re-auth via device code, observe AD consent prompt).
- Tasks #7–#10 all gated on #5. No code changes since Apr 29.
- Boswell main stream: Slice 008 (onboarding) scaffold merged 2026-05-06. Full implementation pending.

### POC Kitchen / TrendInsight
- No recent signals. Memory 13+ days old. Assumed steady.

### Shipwright (AI-DLC)
- Chris's capacity limited (acknowledged to Edward 2026-05-06). Arch shift in progress: away from markdown roles toward programmatic workflow definitions. Layer 2 markdown docs are transitional.

### MeMex-Zero-RAG
- Fork 1-commit stale vs upstream main. Low-priority sync. No squad PRs pending.

## Pending Items (unchanged)
- OpenClaw update: 2026.3.28 available (current 2026.2.9)
- AAD app secrets expiring (bd6209be-717c-41a1-add5-19095aeeebec) — Chris action item
- queue_reply.py — Coconut pending
- PII gate — Chris green-light pending
- RULES.md process TODOs — outstanding
- Fork unsync: titaniumshovel/MeMex-Zero-RAG main ~1 commit behind upstream

## Squad Sync
- Memex unreachable — can't query agent logs
- Upstream quiet 3d+
- No coco-joerg post warranted
