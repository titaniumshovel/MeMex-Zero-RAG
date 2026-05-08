---
title: Molty Project Snapshot — 2026-05-08 07:42 EDT
type: snapshot
agent: molty
project: MeMex-Zero-RAG / daemon-squad / shipwright / boswell
timestamp: 2026-05-08T11:42Z
tags: [agent:molty, type:snapshot, source:bigcheck]
---

# Molty Project Snapshot — 2026-05-08 07:42 EDT

## Status Overview

### MeMex-Zero-RAG / daemon-squad
- **Branch:** `molty-knowledge-decay-schema` — snapshot-only commits since PR#6 merged 2026-04-23
- **Upstream:** Quiet 3d+. No Coconut/Marvin entries visible (memex still down).
- **Memex daemon:** Still DOWN — confirmed DNS NXDOMAIN this morning (exit code 6, ~221h downtime). Squad sync impossible until restored.
- **Tailscale webhook receiver:** Still DOWN since ~17:10 EDT Apr 23 (~15d). Molty deaf to Teams push events.
- **Open work (Molty-owned):** cross-worktree wiki_search test — unblocked, still deferred; fork housekeeping (main 1 commit stale from upstream) — low priority.

### Boswell
- **Status:** Active, solid velocity across slices 005–008. N.B (recordings) still blocked.
- **Last commit:** `0e9b972` — `feat(today): make dashboard transcript-first` (overnight)
- **Uncommitted work:** 5 modified files (`Nav.tsx`, `entity.$slug.tsx`, `entity.test.tsx`, `package.json`, `pnpm-lock.yaml`) + 3 untracked (`.agents/`, `packages/web/e2e/`, `playwright.config.ts`). In-progress, not stale — playwright e2e scaffolded.
- **N.B blocker:** Tasks #7–#10 blocked on Chris's Graph scope verification (Task #5). No movement since Apr 29.
- **Shipped this week:** local vault adapter (010), today dashboard (011), local graph (012), entity ribbon (013), wikilink routing (014), transcript-first dashboard.

### Shipwright AI-DLC Platform
- **Status:** Post-demo day (May 6). Architecture direction in flux.
- **Key shift:** Moving from markdown-driven Layer 2 roles toward programmatic/explicit workflow definitions (Edward + Aaron Rushing alignment, 2026-05-06).
- **Blocker:** Service account `su-us_ai_platform` still needs GitHub read/write all repos + JIRA create/update/comment/label. Pending Chris action.
- **Molty availability note:** Chris's bandwidth limited for a few weeks (customer load + TrendInsight + POC Kitchen).

### TrendInsight
- **Status:** Tom pushed to prod evening of May 6. Likely stable, unconfirmed.

### Obsidian TrendAI Vault
- **Status:** Transcript pipeline active. Regeneron health check meeting completed May 8.

---

## Blockers

- **Boswell Tasks #7–#10:** Chris must verify Graph scope (Task #5) to unblock recording ingestion
- **Shipwright service account:** Chris action needed for `su-us_ai_platform` GitHub + JIRA perms
- **MeMex daemon:** DNS resolution failure ~221h — squad sync impossible
- **Tailscale webhook receiver:** DOWN ~15d — Teams push events not reaching Molty

## Open Solo Items

- cross-worktree wiki_search test (MeMex) — unblocked, deferred
- fork housekeeping: `titaniumshovel/MeMex-Zero-RAG` main 1 commit stale from upstream — low priority

---

## links_to
- github.com/JPeetz/MeMex-Zero-RAG (upstream, quiet 3d+)
- github.com/titaniumshovel/MeMex-Zero-RAG/tree/molty-knowledge-decay-schema
- wiki/synthesis/snapshot-molty-2026-05-07-2210.md
