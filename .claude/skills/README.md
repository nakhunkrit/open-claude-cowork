# Project Skills

Skills in this directory are auto-loaded by Claude Code for anyone working in
this repo. They come from two places:

## Synced from [thananon/9arm-skills](https://github.com/thananon/9arm-skills)

Vendored copies, managed by [`scripts/sync-skills.sh`](../../scripts/sync-skills.sh).
Provenance (upstream commit, sync date) is recorded in [`UPSTREAM.lock`](./UPSTREAM.lock).

| Skill | Invoke | What it does |
|---|---|---|
| [debug-mantra](./debug-mantra/SKILL.md) | `/debug-mantra` | Four-mantra debugging discipline: reproduce → trace the fail path → falsify the hypothesis → cross-reference every breadcrumb. |
| [post-mortem](./post-mortem/SKILL.md) | `/post-mortem` | Canonical engineering record of a fixed bug — root cause, mechanism, fix, validation, how it slipped through. |
| [scrutinize](./scrutinize/SKILL.md) | `/scrutinize` | Outsider-perspective end-to-end review of a plan, PR, or code change. |
| [management-talk](./management-talk/SKILL.md) | — | Rewrite engineer-to-engineer content for engineering-org leadership, shaped per channel (JIRA, Slack, email, standup, meeting). |

To pull the latest from upstream:

```bash
./scripts/sync-skills.sh          # sync from main
./scripts/sync-skills.sh <ref>    # sync from a specific branch/tag/commit
```

Do not hand-edit synced skills — changes will be overwritten on the next sync.
Send improvements upstream instead.

## Local to this repo

| Skill | What it does |
|---|---|
| [brand-guidelines](./brand-guidelines/SKILL.md) | Applies Anthropic's official brand colors and typography. |
| [remotion-best-practices](./remotion-best-practices/SKILL.md) | Best practices for programmatic video generation with Remotion. |

Local skills are listed in the `KEEP` array in `scripts/sync-skills.sh`; add new
local skills there so syncs don't delete them.
