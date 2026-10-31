# Quote Review Agent — Practice Project

> **PRACTICE PROJECT — FICTIONAL DATA.** This is a learning exercise that walks one business process from discovery to a validated, handed-off AI workflow. Every customer, part number, price, cost, rule, and approver title in this repository is **invented**. Nothing here describes a real company, product, or policy. **A human must review every output before it is used.**

## What this is

A practice case for an AI Agent Specialist role in aerospace pricing. The process: **reviewing customer price quotes for connector products before they go out.**

## Ground rules

1. Fictional data only. No real companies, customers, prices, or internal policies.
2. A human reviews every output before use. The workflow returns a recommendation, never a final decision.
3. Every document carries the practice-project notice.
4. Everything is versioned in git, with a tag at each step.

## Progress

| Step | Deliverable | Status |
|---|---|---|
| 1. Discovery | `docs/01_discovery.md` | Draft, awaiting review |
| 2. Use case | scope, success criteria, baseline | Not started |
| 3. Build | reusable quote-review skill | Not started |
| 4. Test | 20 test cases and results | Not started |
| 5. Improve | fixes and change log | Not started |
| 6. Recommend | go / no-go with evidence | Not started |
| 7. Handoff | requirements, rules, test evidence, limitations, user guide, release notes | Not started |

## Folder layout

```
data/
  price_book.csv        14 fictional connector parts with list price and unit cost
  sample_quotes.csv     30 fictional quote requests
rules/
  rulebook_v1.0.md      discount limits, margin floor, approval thresholds
docs/
  01_discovery.md       interview questions, process map, pain points, notes template
CHANGELOG.md
```

More folders appear as steps are completed.

## Versioning

- Commits are made at the end of each step and tagged `step-1-discovery`, `step-2-use-case`, and so on.
- `CHANGELOG.md` records what changed and why.
- Project version is `0.x` until handoff; the handoff release is `1.0.0`.

## Putting it on GitHub

```bash
git remote add origin <your-repo-url>
git push -u origin main --follow-tags
```

Commits use a placeholder author. Set your own with `git config user.name` and `git config user.email` before pushing if you want your identity on future commits.
