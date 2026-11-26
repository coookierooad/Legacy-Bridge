---
name: legacy-task-recovery
description: "Recover interrupted or partially completed business tasks, uncertain submissions and task-level failures by reconstructing state and choosing a safe continuation point. Use only with authorization; routine control failures belong to Operator."
---

# Task Recovery
Restore business continuity after interruption, partial success, uncertain commit or environmental change. Choose actions by state, not a fixed recovery procedure. Inspection alone does not authorize recovery. Never resume after a user stop without renewed authorization.

## Recovery decisions
1. Inherit original goal, scope, permissions, source restrictions and latest instructions. Historical records are clues; never bypass constraints via recovery or tool switching. Pause writes and ask if authorization is unclear.
2. Reconstruct minimal live state using reliable checkpoints, records and verified experience. Confirm system, objects and current state. Prefer bulk GUI text, accessibility or authorized native query/copy/export; screenshots fill gaps. Collect then compare locally, avoiding repeated window switches or per-field screenshots.
3. Classify objects as verified complete, not executed, partial, uncertain, failed or environmentally blocked. Clicks and save messages alone are not business completion. For uncertain submissions, read back stable identifiers and required fields before retrying. Pause ambiguous matches.
4. Choose the smallest safe action: skip verified complete objects; continue unexecuted objects from prerequisites; fill only confirmed missing authorized parts; verify uncertain commits; relocate or adjust invalid paths locally. Preserve correct results rather than rerunning everything.
5. Compensation, overwrite, deletion or rollback require explicit impact scope and appropriate authorization. Do not promise rollback without a reliable inverse. If unsafe, preserve state and report. Independent authorized objects may continue unless stopped or shared risk exists.
6. After two failures of the same underlying mechanism without progress, switch to a genuinely different permitted mechanism; explicit incompatibility requires immediate switching. If alternatives fail, pause affected scope and report evidence and requirements. Never bypass locks or permissions. On stop, issue no new operations; mark already-issued irreversible actions uncertain if needed, without additional verification calls.
7. Verify affected business results after recovery, reuse evidence and avoid full duplicate audit. Stop at the authorized goal; preserve unresolved items.

## Collaboration and experience
Use legacy-gui-operator for control issues, legacy-workflow-learner for rule gaps, legacy-task-orchestrator for resumed planning and legacy-business-auditor for independent audit. Only invoke actual available capabilities as needed. Share state and evidence without mandatory handoff files. When authorized persistence exists, save minimal checkpoints: scope, constraints, identifiers, confirmed results, pending/uncertain states, provenance and next safe action. Disclose inability to persist; do not promise cross-session recovery. Record only verified failure mechanisms, environment, alternatives and recovery conditions; label hypotheses. Operation experience belongs to Operator, business rules to Learner, recovery experience here. Do not duplicate sensitive data or rewrite general skill policy autonomously.

## Report
Default to a detailed conversational report proportional to task size: original goal, interruption cause (facts versus hypotheses), before/after state and counts, recovered/skipped/pending/uncertain objects, actions and evidence, remaining risks and next safe step. Separate actual execution from recommendations; do not invent success, timing or coverage. On user stop, report existing evidence only. Ask whether a formal file or recovery checklist is wanted when appropriate; if already requested, deliver if supported. No mandatory report files or logs.
