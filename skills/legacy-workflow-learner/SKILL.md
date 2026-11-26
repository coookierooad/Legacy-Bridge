---
name: legacy-workflow-learner
description: "Learn, summarize, reuse or update business rules, variables, prerequisites, dependencies, branches and completion criteria. Use for a business knowledge gap or explicit learning request, not routine GUI operations."
---

# Workflow Learner
Convert actual business actions and feedback into reusable business knowledge rather than recording mouse and keyboard sequences. Can learn independently from demonstrations, records and evidence without GUI tools.

## Decision rules
- Reuse reliable knowledge after checking applicability and current state. Do not relearn established workflows.
- Extract only the knowledge needed for decisions from user instructions, actual actions and feedback. Learn during execution rather than repeating it. First-time GUI operation or a failed control is not itself a reason to invoke this skill.
- If a rule is unclear, reuse evidence first; make a minimal read-only observation or ask the user only when it affects a decision. Never create, delete or modify business data to test a hypothesis.
- If a branch changes or a rule becomes invalid, update only affected conditions, dependencies and completion criteria. A single GUI failure does not invalidate business rules.
- Stop when further observations add no useful business knowledge or cannot be authorized. Do not traverse every sample by default. Persist only new or corrected knowledge.

## Abstraction and evidence
Identify goals, business objects and identifiers, inputs, prerequisites, actions, state transitions and completion conditions. Distinguish variables, verified rules and incidental actions. A single success does not prove necessity, uniqueness or universality. Derive dependencies and branches only from evidence; observed order is not necessarily mandatory. Express actions semantically and reference operation experience rather than copying scripts or coordinates. Do not generalize software-specific rules without evidence.
Distinguish observed facts, verified rules, hypotheses and invalid experience; label source and scope, including user-provided rules. Check applicability before reuse and validate through actual results. Preserve uncertainty; never mark an uncertain result successful or blindly repeat writes. Inherit source restrictions, including restrictions on historical evidence.

## Persistence and collaboration
Use existing authorized persistence, concise Markdown or JSON, no required schema. Record relevant goals, scope, variables, rules, dependencies, branches, evidence and invalidation conditions. Load only relevant knowledge; retain unresolved conflicts. Update incrementally without duplicating logs, sensitive data or failed scripts. If persistence is unavailable, disclose it and summarize. Workflows express intent and decision conditions, not mandatory scripts.
GUI interaction belongs to legacy-gui-operator; request only minimal observations. Complex execution, independent audit and recovery belong to legacy-task-orchestrator, legacy-business-auditor and legacy-task-recovery respectively. Share evidence, do not assume tools or dispatch interfaces, and do not expand scope, change rules or initiate writes for learning. General policy changes require justification and user notification.
