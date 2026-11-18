<!-- SPDX-License-Identifier: Apache-2.0 -->
# Repository agent instructions

## Priority 0 — repository-wide full-history additive superset merge rule (2026-11-18)

For every merge, preserve the historically accepted **backward-compatible optimized superset**: public API/ABI, observable behavior, cross-platform capability, native/ownership contracts, tests, bug fixes, proven algorithms and performance. Evaluate all incumbent, donor, branch and PR candidates, select the best *validated* design, allow additive API extensions, and prohibit silent regression or lost code. Inspect ancestry to the **earliest reachable commits**, relevant heads/tags, merged/closed/reverted PRs, branch/merge bases, both merge parents, renames, deletions and abandoned optimizations; never rebase `develop`. Before accepting a merge, checkpoint per ref the last checked date, exact SHA, history/PR/branch coverage, earliest ancestry reached, last verified anchor and detected losses; never label a HEAD-only sample as full-history PASS. Use existing Synexia history-loss and Maven/OpenRewrite recipe gates, with clean postimage-only public receiving repos where applicable; do not add recipe files/evidence crates to product forks. Prefer first-party Apache-2.0 and compatible Apache/permissive donors, but preserve upstream original licenses, notices and attribution: algorithm ideas can be reimplemented independently; LLM rewriting does not erase copyright or derivative-license obligations. Canonical policy and explicitly **PENDING** 236-repo registry: [com.synexia PR #18764](https://github.com/hsoliwal/com.synexia/pull/18764).



## Superset merge and history-audit rule (2026-11-18)

Read [.github/MERGE_RULE.md](.github/MERGE_RULE.md) before changing an existing implementation or integrating any branch or PR.
Preserve the supported additive API/behavior superset and select implementations by correctness, predictability, measured performance, then elegance.
Audit all reachable history back to every root, all branches/tags and all PR states for lost code or regressions; preserve append-only history.
Record actual UTC coverage and remaining work in [.github/HISTORY_AUDIT.tsv](.github/HISTORY_AUDIT.tsv); policy installation is not a completed source-history audit.
Prefer verified Apache-2.0 sources and independent implementations while preserving all existing third-party rights; LLM rewriting does not remove license obligations.
Detailed private recipe/proof records remain in canonical Synexia; the compact local policy and checkpoint make the rule discoverable here.
<!-- MERGE-SUPERSET-HISTORY-20261118-2 -->

## MOP SDK cross-repository agent read gate (2026-11-18)
<!-- MOP-AGENT-2026-11-18-1 -->
Before any source analysis, refactor, PR, merge, licensing decision, or history checkpoint, also read [AGENT.md](AGENT.md). It governs bidirectional atomization/patternization, documented contract-sealed atoms, additive best-of-best API supersets, complete available-history loss checks, dated last-verified proof, Apache-2.0 eligibility and upstream rights. Existing stronger project-specific and locked-canon constraints remain in force. Installation of this pointer does not establish that a source or historical audit has run.
