# Triage Labels

The skills speak in terms of two canonical category roles and six canonical state roles. This file maps those roles to the actual label strings used in this repo's issue tracker.

| Label in mattpocock/skills | Label in our tracker | Meaning |
| --- | --- | --- |
| `bug` | `bug` | Something is broken |
| `enhancement` | `enhancement` | New feature or improvement |
| `needs-triage` | `needs-triage` | Maintainer needs to evaluate |
| `needs-info` | `needs-info` | Waiting on reporter for more information |
| `needs-enrichment` | `needs-enrichment` | Useful work is present, and enrichment should continue from what is present before the next triage decision. The note names what is already present or working. If a concrete observed failure exists, the note may name that failure and the thing not to do. Without a concrete observed failure, hand back to the author or assigned researcher without prescribing a solution, future task, direction, or constraint. Do not ask the author to reduce, reject, fold away, relocate, or justify the work unless a concrete observed failure shows that action failed or must not be done. |
| `ready-for-agent` | `ready-for-agent` | Fully specified, ready for an AFK agent |
| `ready-for-human` | `ready-for-human` | Pair-ready: an agent can work it, but a human should be present for decisions, discussion, access, or checks that cannot be handled AFK |
| `wontfix` | `wontfix` | Will not be actioned |

When a skill mentions a role, use the corresponding label string from this table.

Every triaged issue should carry exactly one category role and one state role.
