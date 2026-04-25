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

## Ticket Triage Policy (Current)

We currently triage support tickets using Severity only.

### Severity levels
- Low means minor annoyance with an easy workaround
- Medium means a meaningful user impact but workarounds exist
- High means blocks key workflows or causes data loss

### Current rules
- Triage happens daily
- High severity should be addressed first
- We do not currently define priority labels, default ownership, or a fast triage checklist

---

## Priority Levels

| Priority | Label | Definition |
|----------|-------|------------|
| P0 | Critical | Service is down or data loss is occurring; immediate response required (24/7) |
| P1 | High | Major feature broken with no workaround; response required within 4 hours during business hours |
| P2 | Medium | Meaningful user impact but a workaround exists; response required within 2 business days |
| P3 | Low | Minor annoyance or cosmetic issue; address in the next sprint or backlog grooming |

### Severity → Default Priority Mapping

| Severity | Default Priority |
|----------|-----------------|
| High | P0 or P1 |
| Medium | P2 |
| Low | P3 |

> **Note:** Engineers may escalate or de-escalate priority based on customer impact, business context, or SLA obligations.

---

## How to Triage in 60 Seconds ✅

1. **Read the ticket title and description** – understand what is broken and who is affected.
2. **Assign a Severity** – use the severity definitions above (High / Medium / Low).
3. **Set the default Priority** – use the mapping table above as your starting point.
4. **Adjust if needed** – escalate to P0/P1 if a paying customer or critical path is affected; de-escalate if impact is narrow.
5. **Add a label** – apply the appropriate `P0` / `P1` / `P2` / `P3` label in GitHub.
6. **Assign an owner** – P0/P1 tickets must have an owner immediately; P2/P3 can be assigned during daily triage.
7. **Leave a comment** – briefly note your triage decision so the team has context.
