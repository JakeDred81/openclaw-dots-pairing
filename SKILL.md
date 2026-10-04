---
name: openclaw-dots-pairing
description: "Pair OpenClaw with OpenAI dots; hand off bounded tasks through a verified existing dot conversation and return checked results."
license: CC-BY-4.0
---

# OpenClaw Dots Pairing

1. Establish the handoff contract. Identify the existing dot from scoped project context, one execution owner, the current instruction revision, allowed actions, and a checkable deliverable. Consult [the handoff template](references/handoff-template.md). Done when the brief names the target and contains only the context needed for this task.

2. Inspect applicable native APIs or authenticated connectors before UI work. Use a supported interface when available for the requested operation; otherwise use the browser-mediated route below. Connected tools or MCP Events alone do not prove a full external-agent task lifecycle interface. Consult [capability boundaries](references/capabilities.md). Done when the selected route and any unsupported operations are explicit.

3. Verify authorized browser access. Follow the installed browser-automation skill, use an authorized session and task-owned tab, and verify the account, workspace, exact dot conversation, and browser control before sending. Preserve unrelated tabs and avoid taking the user’s foreground. Reconcile uncertain browser state before retrying. Leave human-only authentication to the user without capturing credentials. Done when the target and authorized control are verified.

4. Inspect current conversation state and pending work. Distinguish live paused/running status from historical notes. Assign a unique handoff marker and instruction revision; define delegation, external-action, resource, and disclosure boundaries explicitly. Do not transfer broad conversation history or assume the dot inherits OpenClaw's tools or policy enforcement. Done when the current brief is compatible with observed work and contains no competing execution owner.

5. Dispatch once. Fill the composer, read it back, and compare the complete normalized text with the prepared brief before using Send. Record target, marker, timestamp, and dispatch state. Verify the matching visible message and any read receipt. After an uncertain result, inspect for the marker and response before retrying; the marker aids reconciliation but is not server-side idempotency. Done when dispatch is verified, or recorded as UNKNOWN without a duplicate send.

6. Retrieve and assess the correlated reply. Use fresh browser references and a uniquely scoped conversation selector when broad snapshots truncate content or match multiple surfaces. A read receipt or acknowledgment proves neither finished work nor permanent policy adoption. Check the requested deliverable, sources, artifacts, and reported limitations; preserve the owner's required reviews and approvals before consequential use. Done when the output is verified to the agreed criteria or a concrete remaining blocker is returned to the parent.

7. Reconcile completion, interruption, and future use. A dot pause does not establish cancellation of delegated tasks or schedules; inspect affected work before reporting it stopped. Save the dot mapping and task receipt in scoped local project memory, not this reusable skill. Report the route used, verified outcome, unresolved work, and any untested automation. Do not call browser handoffs an unattended bridge or claim measured usage savings without measurements. Done when receipt and remaining ownership are clear.

For attribution and licensing, see [ATTRIBUTION.md](ATTRIBUTION.md) and [LICENSE.txt](LICENSE.txt).
