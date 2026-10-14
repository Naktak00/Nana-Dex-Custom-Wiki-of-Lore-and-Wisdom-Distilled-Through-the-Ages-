# Personal Task Logs — Live Coordination Protocol
Updated: 2026-10-14 | **Current state only, not a historical archive.**
These entries are transparent coordination pointers. They are not proof of ongoing autonomous activity, permissions to act, or a source of private personal information.

## Current governance and maintenance
- **Nana is the sole IT owner and decision-maker** for the current operation, including architecture, permissions, priorities, approvals, and onboarding future IT staff.
- **Lightning is the requested task-log coordinator for now**, updating these records when participating in relevant sessions and after verifying new evidence. This does **not** imply autonomous continuous monitoring.
- **Mana may support implementation and suggest updates** within authorized scope. Offloading routine log updates to an existing Mana heartbeat is a *proposal*, not an active delegation; first verify the heartbeat's actual permissions, relay protocol, access, and explicit write scope. Do not modify the heartbeat's existing purpose or cadence implicitly.
- **Future clinical, administrative, or secretarial colleagues** may coordinate through ChatGPT using role-specific workflows without IT-department control. Access to student, clinical, and administrative data must follow approved least-privilege permissions and applicable privacy rules.
- Keep IT architecture changes, production deployments, permissions, and personnel access under Nana's approval. A visible backlog is not an instruction to execute.
- Workflow is intentionally provisional while Nana refines it; avoid prematurely imposing rigid procedures or assuming future staff roles.

## How entries work
Every participant's entry shows: **current focus; next action; short backlog; blockers; help welcome; last verified evidence; handoff link; last reviewed**. Mark unknown/unverified explicitly. Update in place as work changes; completed work leaves the active list after its result is recorded in the appropriate project repository. Git history is incidental, not the purpose of this board.

Anyone may **read and suggest** help. Do not edit another person's entry, take control of their branch, send messages on their behalf, or execute work merely because their backlog is visible. Obtain applicable authorization and coordinate a handoff. Avoid claiming AI agents are independently monitoring this board unless a verified process exists.

**Public privacy boundary:** No patient/student personal information, secrets, private meeting links, personal schedules, internal credentials or confidential project specifics. Private work stays in private project repositories. Keep links and summaries minimal.

## Nana — current
- **Focus:** FLC website review and Supabase Passport prioritization; LP v1.0 creative oversight.
- **Next:** Review Mana's FLC site reconstruction and verify working student navigation.
- **Backlog:** Review Passport sign-in prototype; LP release review.
- **Blockers:** Actual site review and implementation evidence pending.
- **Help welcome:** Compare functionality, accessibility and course/Zoom/Thinkific journey; propose concise acceptance tests.
- **Last verified:** FLC private master ledger and NanaDex Active Work checklists created (2026-10-14). No site approval implied.
- **Handoff:** [FLC checklist](FLC.md) | [LP checklist](LIGHTNING-PONG.md).

## Lightning — current
- **Focus:** Cross-project coordination, requirement clarification, verification and compact handoffs.
- **Next:** On request, read latest project artifacts and fill in missing assumptions or acceptance criteria for another agent.
- **Backlog:** Verify progress and help unblock FLC Passport and LP v1.0 as authorized.
- **Blockers:** No independent persistent work session; fresh evidence needed before claiming progress.
- **Help welcome:** Ask for evidence, edge cases, architecture review or a handoff summary.
- **Last verified:** Active Work project checklists committed 2026-10-14.
- **Handoff:** [Project switchboard](README.md).

## Mana — current (reported, not independently verified here)
- **Focus:** FLC website reconstruction and Lightning Pong v1.0 implementation.
- **Next:** Supply branch/build/test evidence for FLC review and LP current state.
- **Backlog:** FLC Supabase Passport prototype after site review; LP stabilization/release gates.
- **Blockers:** Current task/branch status unverified; avoid assigning new work as though accepted.
- **Help welcome:** Clear, testable requirements; review of bugs, onboarding and security.
- **Last verified:** Nana reports Mana recreated FLC site and changed Germantown address; this is not an independent code audit.
- **Handoff:** [FLC checklist](FLC.md) | [LP checklist](LIGHTNING-PONG.md).

## Future participants
**Nyancian / NyNy:** no active work entries until the participant or project is ready and the appropriate trust/authorization gates are met. Do not infer activity from a placeholder.

## Rapid pickup
1. Open [Active Work](README.md), choose a project and one branch for the day.
2. Read participant entry and linked project checklist.
3. Verify current commit/build/status before acting.
4. Offer help or request authorization; keep suggestions distinct from approved work.
5. Update current focus and next action at the end of the session.
