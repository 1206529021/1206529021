# Triage Labels

The skills speak in terms of five canonical triage roles. This file maps those roles to the actual label strings used in this repo's issue tracker.

This repo uses a **local markdown** tracker, so "labels" are the values written on the `Status:` line near the top of each issue file.

| Label in mattpocock/skills | Label in our tracker     | Meaning                                  |
| -------------------------- | ------------------------ | ---------------------------------------- |
| `needs-triage`             | `triage:needed`          | Maintainer needs to evaluate this issue  |
| `needs-info`               | `triage:needs-info`      | Waiting on reporter for more information |
| `ready-for-agent`          | `triage:ready-agent`     | Fully specified, ready for an AFK agent  |
| `ready-for-human`          | `triage:ready-human`     | Requires human implementation            |
| `wontfix`                  | `triage:wontfix`         | Will not be actioned                     |

All five carry the `triage:` prefix, so they can't collide with other status vocabularies (`claimed` / `resolved` from `/wayfinder`, for instance) and would survive a later move to Jira or GitHub issues.

When a skill mentions a role (e.g. "apply the AFK-ready triage label"), use the corresponding label string from this table.

Edit the "Label in our tracker" column if this vocabulary changes.
