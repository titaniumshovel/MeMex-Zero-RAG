# Molty Project Snapshot — 2026-04-27 23:37 EDT

**agent**: molty  
**type**: snapshot  
**project**: MeMex-Zero-RAG  
**links_to**: [github.com/JPeetz/MeMex-Zero-RAG](https://github.com/JPeetz/MeMex-Zero-RAG), [github.com/titaniumshovel/MeMex-Zero-RAG/tree/molty-knowledge-decay-schema](https://github.com/titaniumshovel/MeMex-Zero-RAG/tree/molty-knowledge-decay-schema)

## Status

- JPeetz upstream (`0fe1d84`): quiet 4+ days, unchanged
- Memex server (`memex-daemon-squad.orca-decibel.ts.net`): returning 404 on /health and /nodes — ~18h+ degraded
- No squad signals (Coconut, Marvin) since 2026-04-23 ~20:00 EDT
- CLI agent timeout event at 22:54 EDT (bypassPermissions lesson — non-actionable)

## Open Items (unchanged)

| Item | Owner | Status |
|---|---|---|
| cross-worktree wiki_search test | Molty | Unblocked, unrun — awaiting Chris active |
| mcp-auth key strategy | Squad | Open — awaiting discussion |
| Issue #7 (cascade-clear worker) | TBD | Open, unassigned |
| Webhook receiver (nabu-pn7g55fc) | Chris | Tailscale unreachable |
| context-before-claim → RULES.md | Squad | Pending alignment |
| queue_reply.py structural fix | Coconut | Pending |
| PII hygiene gate | Chris | Awaiting green-light |

## Squad Sync

No new memex nodes readable (server 404). No GitHub activity on JPeetz upstream. Monday evening, quiet.

## Next Steps

1. When Chris active: run cross-worktree wiki_search test
2. When memex recovers: squad sync on mcp-auth
3. Monitor JPeetz upstream for any PR/issue activity
