# Molty Project Snapshot — 2026-05-01 22:36 EDT

**agent:** molty  
**type:** snapshot  
**project:** MeMex-Zero-RAG  
**tags:** project=MeMex-Zero-RAG, agent=molty, type=snapshot  
**links_to:** project_boswell_nb, project_obsidian_vault, reference_graph_api, reference_memex_jpeetz

---

## State as of 2026-05-01 22:36 EDT

**Time since last snapshot:** ~35h (prior: 2026-04-29 11:25 EDT)  
**Upstream activity since last snapshot:** None — upstream quiet 8+ days

### MeMex-Zero-RAG (JPeetz/MeMex-Zero-RAG)
- All merged PRs (#3–#6) unchanged; no new upstream commits in 8+ days
- Local branch: `molty-knowledge-decay-schema` — current with origin after PR#6 merge
- No open PRs from Molty

### Memex infrastructure
- `memex-daemon-squad.orca-decibel.ts.net:8080`: **DNS failure** (getaddrinfo error)
- Outage duration: ~113h (since ~2026-04-27 ~21:30 EDT)
- Tailscale 100.64.0.1 also unreachable
- Pattern: TCP timeout → DNS failure at 02:38 EDT May 1 (possible deregistration or local Tailscale disconnect)
- Squad signals unavailable for this entire review period

### Open items (unchanged from 2026-04-24 snapshot)
| Item | Owner | Status |
|---|---|---|
| mcp-auth key strategy | Squad | Open — awaiting discussion |
| Issue #7 (cascade-clear worker) | TBD | Open, unassigned |
| Webhook receiver (nabu-pn7g55fc) | Chris | Tailscale node unreachable |
| cross-worktree wiki_search test | Molty | Unblocked, unrun |
| context-before-claim → RULES.md | Squad | Pending alignment |
| queue_reply.py structural fix | Coconut | Pending |
| PII hygiene gate | Chris | Awaiting green-light |

### Related active projects
- **Boswell (second-brain)**: On `main` branch; last commit 2026-04-29 17:58 EDT (h.2 test suite). Blocked on Task #5 (Chris Graph scope verification). Chat route work (`POST /api/chat/ask`, `POST /api/chat/promote`) previously on `003b-compile-pipeline-rest` branch — merged to main or branch switched.
- **Pipeline (.second-brain)**: Last AI call 2026-05-01 09:13 EDT. Session compiler blocked at 155 entries (last compiled 2026-04-28 13:11 UTC). 306 sessions in draining queues unchanged 3+ days.
- **Wiki (TrendAI Obsidian)**: 5 transcripts today (TrendInsight SE Dashboard, POC Kitchen Standup, TrendAI Mass Gen Cadence, Chris+Edward Sync, SPARK 2026 Global Series). Last sync 17:15 EDT. 102 uncommitted modified files (pipeline accumulation).

### Next steps (priority order)
1. **cross-worktree wiki_search test** — unblocked, Molty-owned; defer to next Chris-active session
2. **mcp-auth strategy** — squad discussion needed; memex down blocks async coordination
3. **Memex restoration** — Chris-owned (Tailscale reconnect or node re-registration)
4. **Boswell Task #5** — Chris's Graph scope verification

### Squad activity
- **Coconut**: Unknown since memex down; last known active 2026-04-23 ~20:00 EDT
- **Marvin**: Unknown since memex down; last known active 2026-04-22
- **Joerg**: Unknown since PR#6 merge 2026-04-23 17:22 EDT
- **Signals available**: None (memex DNS failure blocks all squad sync)
