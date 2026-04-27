---
title: Molty Project Snapshot — 2026-04-27 08:27 EDT
type: synthesis
created: 2026-04-27
author: molty
tags:
  - agent:molty
  - type:snapshot
  - project:memex-zero-rag
  - infra:webhook-down
links_to:
  - KNOWLEDGE-DECAY.md
  - wiki/synthesis/snapshot-molty-2026-04-27-0727.md
  - RULES.md
---

# Molty Project Snapshot — 2026-04-27 08:27 EDT

**Status:** Stable. Upstream unchanged ~96h. Monday morning, Chris active.

## Branch state

- `upstream/main`: `0fe1d84` (PR#6 merge) — unchanged ~96h
- `grobomo/coconut`: no new commits
- `upstream/feat/marvin`: no new commits
- `molty-knowledge-decay-schema`: 97 commits ahead (wiki snapshots only)

## Open items (unchanged)

| Item | Owner | Status |
|---|---|---|
| cross-worktree wiki_search test | Molty | Unblocked, unrun — highest leverage |
| PII hygiene gate (5 wiki files) | Chris | Awaiting green-light |
| mcp-auth key strategy | Squad | Open discussion pending |
| Issue #7 (cascade-clear worker) | TBD | Unassigned |
| Webhook receiver nabu-pn7g55fc | Chris | Tailscale unreachable since Apr 23 (~4d) |
| queue_reply.py structural fix | Coconut | Pending |
| context-before-claim → RULES.md | Squad | Pending alignment |

## Infrastructure

- Memex SSE server: Reachable (307 redirect on /sse) but /nodes API returning 404 — persistent since last night's 23:28 review
- Webhook receiver: Still unreachable, now ~4 days

## Squad signals

- No new commits to upstream/main, grobomo/coconut, or upstream/feat/marvin
- Memex /nodes 404 prevents direct squad query — no signals to surface

## Monday context (Trend Micro)

Chris has active Monday queue (work-facing):
1. AAD cert expiration (app bd6209be-...) — resolve
2. Jane / Regeneron C1WS bucket analysis
3. Vlad Rotshteyn — Local Apps API reply
4. Nancy Henley — VP board talking points (high priority)
5. Bonus target letters from Brent

Molty role: support when asked, not blocking on any of these.

## Next steps

1. **wiki_search cross-worktree test** — do when Chris ready, still highest-leverage
2. **Webhook receiver** — worth checking Tailscale status if Chris has a moment
3. **squad discussion** — mcp-auth strategy, cascade-clear owner
