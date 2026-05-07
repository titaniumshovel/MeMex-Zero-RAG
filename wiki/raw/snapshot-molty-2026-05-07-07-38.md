---
title: Molty Project Snapshot — 2026-05-07 07:38 EDT
type: snapshot
agent: molty
project: MeMex-Zero-RAG / daemon-squad / shipwright / boswell
timestamp: 2026-05-07T11:38Z
tags: [agent:molty, type:snapshot, source:bigcheck]
---

# Molty Project Snapshot — 2026-05-07 07:38 EDT

## Status Overview

### MeMex-Zero-RAG / daemon-squad
- **Branch:** `molty-knowledge-decay-schema` — only snapshot commits since PR#6 merged 2026-04-23
- **Upstream:** Quiet ~14d. No Coconut/Marvin wiki entries visible (memex still down).
- **Memex daemon:** Still DOWN ~182h (DNS failure since ~23:28 Apr 26). Port 3001 unreachable.
- **Tailscale webhook receiver:** Still DOWN since ~17:10 EDT Apr 23. 0 active subscriptions.
- **Open work (Molty-owned):** cross-worktree wiki_search test — deferred pending Chris availability; MeMex fork 1 commit stale from upstream (low priority)

### Shipwright AI-DLC Platform
- **Architecture shift (2026-05-06):** Edward confirmed moving away from markdown-driven Layer 2 role definitions → programmatic/explicit workflow builder. Informed by Aaron Rushing's team's Claude-triggered approach. Layer 2 markdown docs are now transitional — don't invest in editing them.
- **Chris's capacity message (2026-05-06 4:21 PM):** Chris told Edward he's load-balanced (customers + TrendInsight + POC Kitchen) for "a few more weeks." Contributions limited accordingly.
- **No action items for Molty on Shipwright.**

### Boswell N.B. (Recordings Ingest)
- **Status:** Blocked at same point since 2026-04-29. Tasks #7–10 blocked on Chris's Graph scope verification (Task #5).
- **New since last snapshot:** Boswell Slice 008 scaffold (PR #18, `b8816ea`) merged 2026-05-06 — onboarding + explainer surfaces scaffold, full implementation still pending.
- **Test count:** 228 server tests pass.

### Obsidian TrendAI Vault
- **Pipeline:** Running. Process-transcripts.mjs active.
- **Transcript gap (May 5 afternoon):** Louise, AI Integration 2PM, Eliz 3PM, Canfield 4PM — still absent. Likely recording gap.

### TrendInsight
- **Status:** Stable. D365 API integration still blocked in legal review.

---

## Blockers (Persistent)
- **Boswell Tasks #7–10:** Chris must run Graph scope verification (Task #5) to unblock
- **MeMex daemon:** Tailscale reconnect + DNS fix needed to restore squad sync
- **AAD app secrets:** Two TM app registration secrets expiring soon (bd6209be-717c-41a1-add5-19095aeeebec) — Chris aware

## Open Solo Items
- cross-worktree wiki_search test (MeMex) — unblocked, still deferred
- OpenClaw update: 2026.3.28 available (current: 2026.2.9)

---

## links_to
- github.com/JPeetz/MeMex-Zero-RAG (upstream, quiet ~14d)
- github.com/titaniumshovel/MeMex-Zero-RAG/tree/molty-knowledge-decay-schema
- wiki/raw/snapshot-molty-2026-05-06-09-26.md
