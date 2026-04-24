---
title: Molty Project Snapshot — 2026-04-23 21:10 EDT
type: synthesis
created: 2026-04-23
author: molty
tags:
  - agent:molty
  - type:snapshot
  - project:memex-zero-rag
  - infra:webhook-down
  - topic:mcp-auth
links_to:
  - KNOWLEDGE-DECAY.md
  - wiki/synthesis/snapshot-molty-2026-04-23-2010.md
  - RULES.md
---

# Molty Project Snapshot — 2026-04-23 21:10 EDT

---

## MeMex-Zero-RAG

**Status:** Stable. No new code commits from any squad member since 18:10.

**Gap resolved:** Unpushed wiki snapshots (18:10, 19:10, 20:10) pushed to titaniumshovel fork this hour. Fork branch `molty-knowledge-decay-schema` is now current. Squad can read via GitHub.

**Upstream:** PR#6 merge commit `0fe1d84` confirmed in JPeetz/upstream/main. No new upstream activity in last 4 hours.

---

## Daemon Squad — mcp-auth discussion

Coconut proposed Tailscale ACLs + API key as two-layer MCP auth model. Molty agreed in daemon-squad-bot channel this session:

- Network layer: Tailscale restricts access to known squad identities
- App layer: API key scopes what authenticated identities can do
- **Open design question:** per-bot keys (easier revocation, higher config overhead) vs. single squad key (simpler, broader blast radius if compromised)

This decision is unresolved. No implementation started.

---

## Infrastructure

Webhook receiver still DOWN. `nabu-pn7g55fc.tailbf57c9.ts.net` Tailscale node unreachable. Molty remains deaf to incoming Teams pings; outbound sends (send-teams.sh) functional.

---

## Open items

| Item | Owner | Status |
|---|---|---|
| mcp-auth key strategy (per-bot vs squad key) | Squad | Open — design discussion |
| Issue #7 (cascade-clear worker) | TBD | Open, unassigned |
| Webhook receiver (nabu-pn7g55fc) | Chris | Node unreachable |
| cross-worktree wiki_search test | Molty | Unblocked, unrun |
| context-before-claim → RULES.md | Squad | Pending |
| queue_reply.py structural fix | Coconut | Pending |
| PII hygiene gate | Chris | Awaiting green-light |

---

## Squad activity this hour

- Coconut: Active in daemon-squad-bot re mcp-auth (last seen ~20:00 EDT)
- Marvin: No activity (last: 2026-04-22)
- Joerg: No activity (last: PR#6 merge at 5:22 PM EDT)
