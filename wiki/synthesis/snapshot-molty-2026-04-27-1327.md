# Molty Project Snapshot — 2026-04-27 13:27 EDT

**Agent:** molty
**Type:** snapshot
**Project:** daemon-squad-sentinel / MeMex-Zero-RAG

## State

- **Upstream:** `0fe1d84` — 4 days old (PR#6 merged Apr 23). No new commits in last 4h.
- **Local:** 88 commits ahead of upstream/main (all wiki snapshots, unpushed)
- **Memex:** Server responding HTTP 404 on all paths (`/nodes`, `/health`, `/`) — uvicorn process running, API routes not found. Persistent since 23:28 Apr 26 (~14h).
- **Squad:** No signals. Coconut last active ~20:00 Apr 23; Marvin last active Apr 22; Joerg last active Apr 23.

## Open Items (unchanged)
1. cross-worktree wiki_search test — **Molty-owned, unblocked, unrun** (highest-leverage)
2. mcp-auth key strategy — squad discussion needed
3. Issue #7 (cascade-clear worker) — unassigned
4. queue_reply.py structural fix — Coconut
5. PII hygiene gate (5 sensitive wiki files) — Chris green-light needed
6. Webhook receiver (nabu-pn7g55fc) — Tailscale unreachable since Apr 23

## Notable this review
- Memex changed from "connection refused" (earlier today) → HTTP 404. Service is running on uvicorn but routes 404. No functional difference for squad queries.

## Next Steps
1. Cross-worktree wiki_search test (Chris's call to initiate)
2. Investigate memex 404 — may need squad awareness
3. mcp-auth discussion (squad-level)

## links_to
- github.com/JPeetz/MeMex-Zero-RAG/pull/6 (MERGED)
- github.com/titaniumshovel/MeMex-Zero-RAG/tree/molty-knowledge-decay-schema
- wiki/synthesis/snapshot-molty-2026-04-24-0210.md
