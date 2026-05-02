# Molty Project Snapshot — 2026-05-02 09:04 EDT

**agent:** molty  
**type:** snapshot  
**project:** MeMex-Zero-RAG  
**tags:** project=MeMex-Zero-RAG, agent=molty, type=snapshot  
**links_to:** project_boswell_nb, project_obsidian_vault, reference_graph_api, reference_memex_jpeetz

---

## State as of 2026-05-02 09:04 EDT

**Time since last snapshot:** ~10.5h (prior: 2026-05-01 22:36 EDT)  
**Upstream activity since last snapshot:** None

### MeMex-Zero-RAG (JPeetz/MeMex-Zero-RAG)
- upstream/main: stable at `0fe1d84` — Merge PR#6 (2026-04-23 17:22 EDT), no new commits in 9 days
- Local branch: `molty-knowledge-decay-schema` — current with upstream after PR#6
- origin/main (titaniumshovel fork): 1 commit only — fork's main was never synced. **Not a crisis** — all work went through upstream PRs directly. Fork's main is just an unsync'd base.
- No open PRs; Issue #7 (cascade-clear worker) open and unassigned

### Memex infrastructure
- `memex-daemon-squad.orca-decibel.ts.net`: **DOWN** — curl exit 6 (CURLE_COULDNT_RESOLVE_HOST)
- Outage duration: ~124h (since ~2026-04-27 ~21:30 EDT)
- Squad signals unavailable for entire review period

### Tailscale webhook receiver
- `nabu-pn7g55fc`: UNREACHABLE since ~17:10 EDT Apr 23 (~9.5 days)
- Molty deaf to incoming Teams pings during this period

### Open items (unchanged)
| Item | Owner | Status |
|---|---|---|
| mcp-auth key strategy | Squad | Open — awaiting discussion |
| Issue #7 (cascade-clear worker) | TBD | Open, unassigned |
| Webhook receiver (nabu-pn7g55fc) | Chris | Tailscale node unreachable |
| cross-worktree wiki_search test | Molty | Unblocked, unrun |
| context-before-claim → RULES.md | Squad | Pending alignment |
| queue_reply.py structural fix | Coconut | Pending |
| PII hygiene gate | Chris | Awaiting green-light |
| Fork origin/main sync | Molty | Low-priority housekeeping |

### Squad activity
- **Coconut**: Unknown — memex down, no GitHub activity since Apr 23
- **Marvin**: Unknown — memex down, last known active Apr 22
- **Joerg**: Unknown since PR#6 merge Apr 23; GitHub last push 2026-04-23T21:22Z

### Next steps (priority order)
1. **Memex restoration** — Chris-owned (Tailscale reconnect or node re-registration); blocks all squad sync
2. **Webhook receiver** — Chris-owned (Tailscale); blocks Molty Teams awareness
3. **cross-worktree wiki_search test** — Molty-owned, unblocked; do in next active Chris session
4. **Issue #7** — squad design discussion needed once memex is up

### Note on fork origin/main
The titaniumshovel fork's `main` has only the initial `693d51b` upload commit from Apr 10 — it was never fast-forwarded from upstream. All merged work (PRs #3–#6) lives in JPeetz/upstream/main. This is a minor housekeeping item: `git checkout main && git merge upstream/main && git push origin main` when convenient.
