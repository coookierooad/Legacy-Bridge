---
name: legacy-task-orchestrator
description: "Complete complex business tasks involving dependencies, branches, batches or multiple systems. Define outcomes, map semantics, schedule execution and track progress. Use for business delivery rather than simple GUI actions or learning alone."
---

# Task Orchestrator
Turn a user goal into executable and verifiable work. Dynamically organize available capabilities until the goal is reached or genuinely blocked. Do not assume software, fields, workflow, object counts or fixed procedures.

## Scope and completion
Define objects, scope, target state, permitted actions and evidence sources. Ask only when ambiguity affects correctness or authorization. All subtasks, handoffs, retries and knowledge reuse inherit constraints. GUI-only tasks prohibit source code, hidden data, business APIs and evidence from prohibited historical channels. Authorized accessibility and visual interaction are allowed. Tool availability is not permission. Unknown-provenance knowledge is not evidence for restricted tasks. Define success by business outcomes, not clicks, script exits, navigation or plans.

## Dynamic execution
- Reuse reliable workflows and operation experience after checking key conditions. Avoid full replanning. Fill only decision-critical gaps: operation via Operator, business knowledge via Learner, when available. Preserve unknowns rather than guessing.
- Decompose complex work into minimal executable units with prerequisites, inputs, outputs, identity and completion criteria. Plan only necessary steps and adjust locally as feedback arrives.
- Schedule by dependency and risk. Batch independent low-risk actions; do not parallelize conflicting window focus, clipboard or shared business state. Verify a representative object before batch writes and reassess changed conditions.
- Map fields using meaning, identifiers, formats, units, enums, purpose and feedback, not names alone. Distinguish original values, justified conversions, defaults, missing values and unknown mappings. Do not fabricate or silently discard data. Preserve evidence and report ambiguous or unsupported transformations.
- Establish target identity and create/update conditions; check for duplicates and target state before writing. Pause ambiguous conflicts. Reuse validated mappings and read only necessary data.
- Track pending, in progress, confirmed complete, failed, uncertain and blocked states per object or commit unit. Confirm actual results after writes, reusing sufficient evidence. Never count unverified records as complete. If submission is uncertain, pause writes and read back first; no blind retry or unauthorized rollback. Continue independent safe objects only if no shared risk or stop instruction exists.
- Stop when the goal is achieved; do not explore unrelated data. Report partial results and minimal next steps when blocked.

## Collaboration and continuity
Simple GUI tasks use legacy-gui-operator; learning-only tasks use legacy-workflow-learner. Independent audit uses legacy-business-auditor when warranted; otherwise perform necessary basic verification and disclose coverage. Task-level residual state or recovery uses legacy-task-recovery. Never bypass locks or permissions. Do not invent dispatch or persistence capabilities.
Save minimal checkpoints only at necessary commit boundaries or interruption risk, using authorized existing storage; disclose unavailable persistence. Revalidate live state before resuming. Share goal, constraints, inputs, state and evidence in context without mandatory files or logs. Assign reusable business rules to Learner and operation knowledge to Operator; temporary mappings and state are not durable knowledge. Report confirmed scope, failures, uncertainty, blockers and next steps using evidence-based counts. General policy changes require justification and user notification.
