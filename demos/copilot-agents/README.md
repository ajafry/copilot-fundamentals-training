# Copilot Agents Demo

Use the following 3 files to setup your Copilot Agents demo. 
Paste the ISSUE.md file into a new issue in that repository. 

## What this demo shows
- Assign an issue to Copilot to start an agent task
- Monitor progress in AgentHQ
- Re-steer mid-session with a new requirement
- Review the resulting PR like a teammate’s work

## Demo files
- `ISSUE.md` contains the exact issue text to copy/paste into GitHub
- `STEER.md` contains the mid-session requirement change to paste while the agent is working

## Quick demo steps
1. Create a new GitHub Issue by copying the Title and Body from `ISSUE.md`
2. Assign the issue to Copilot to start the agent task
3. Open AgentHQ to monitor progress
4. Paste `STEER.md` into the agent session to re-steer the work
5. Review the PR diff for clarity, completeness, and constraints.
6. Verify the PR edited the README.md file by adding priority levels plus the steered examples. 

---

## Ticket Triage Policy

We triage support tickets using both Severity and Priority.

### Severity levels
| Level | Description |
|-------|-------------|
| Low | Minor annoyance; easy workaround exists |
| Medium | Meaningful user impact; workaround exists |
| High | Blocks key workflows or causes data loss |

### Priority levels
| Label | Meaning |
|-------|---------|
| P0 | Critical — production down, immediate action required |
| P1 | High — major feature broken, fix within 1 business day |
| P2 | Medium — degraded experience, fix within the sprint |
| P3 | Low — cosmetic or minor issue, fix when capacity allows |

### Severity → Priority mapping
| Severity | Default Priority |
|----------|-----------------|
| High | P0 / P1 |
| Medium | P2 |
| Low | P3 |

### How to triage in 60 seconds
1. **Read** the ticket title and description.
2. **Assign Severity** (Low / Medium / High) based on user impact.
3. **Set Priority** using the mapping above; adjust if context warrants.
4. **Label & assign** the ticket to the appropriate owner.
5. **Add a comment** with your reasoning if you deviate from the default mapping.
