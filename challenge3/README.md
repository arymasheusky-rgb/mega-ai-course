# S01E03 — what it shows

Public deliverables for MEGA challenge `what it shows`.

## Tickets (GitHub issues)

One issue per cause found in merged ticket #4471:

| cause | reports | issue |
| --- | ---: | --- |
| `parser` | 379 | https://github.com/arymasheusky-rgb/mega-ai-course/issues/2 |
| `hint` | 33 | https://github.com/arymasheusky-rgb/mega-ai-course/issues/3 |

## KB page

- Source: `support-kb/src/routes/kb/incidents/4471-causes/+page.svx` (signed)
- Desk view: `desk-view.html` (how the desk sees that page)

Counts come from `uniqueById(reports-4471.json)` filtered to `mergedInto === 4471`, then `groupByCause` / `causeOf` in `support-kb/src/lib/kb/causes.ts`.
