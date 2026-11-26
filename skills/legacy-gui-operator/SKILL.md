---
name: legacy-gui-operator
description: "Operate unfamiliar desktop or web interfaces, locate controls, enter data, navigate, verify actions and reuse interaction experience. Use when the capability gap is GUI operation rather than business knowledge."
---

# GUI Operator
Translate authorized business intent into verifiable GUI actions. Use screen, mouse, keyboard, accessibility and visual tools actually available. Do not assume software type, menus, fields or paths. Work independently when other skills are absent.

## Decision rules
- Reuse reliable experience using the lowest-cost verified mechanism. Spot-check one or two critical controls; do not replay exploration. Skip known invalid mechanisms.
- When information is missing, observe only what the next decision needs. Stop exploring when a usable path is found. For unfamiliar actions, perform one action, observe feedback and adjust before batching.
- Locate semantically (role and label), then structurally (parent and relative position), then visually. Confirm the match through feedback. Reobserve only when the interface changes or location fails.
- Establish focus, input or paste, then verify. Prefer native clipboard paste for non-ASCII or special characters. Avoid redundant window activation and arbitrary waits.
- On failure, reobserve and relocate. Confirm no side effects before retrying. Count failures by underlying action, object and tool mechanism; changing parameters or wrappers does not reset the count. After two failures switch to a genuinely different authorized mechanism. Explicit syntax incompatibility, missing tools or unavailable interfaces require immediate mechanism change, not repeated debugging. If no safe alternative exists, stop and report the action, location, window state and available evidence.
- Verify according to risk: batch low-risk reads, navigation and unsaved non-autosaving input with checks at key transitions; verify each save or write at least once; verify unfamiliar, destructive or external actions step by step and obtain authorization for destructive actions. If submission is uncertain, read back before any retry.

## Experience
Record only verified software identifiers, paths, locating evidence, input methods, success signals, failure modes, environment and alternatives. Use existing authorized persistence in concise Markdown or JSON; no mandatory schema. Mark invalid experience and skip it later. Revalidate across environments. Do not invent files, controls, interfaces or capabilities. If persistence is unavailable, report that limitation and summarize useful experience. Keep software-specific coordinates and paths out of this skill; see the optional environment notes for examples.

## Collaboration
Use legacy-workflow-learner for business rules, legacy-task-orchestrator for complex execution, legacy-business-auditor for independent audit, and legacy-task-recovery for task-level residual state or uncertain submissions. Only invoke available capabilities when needed; otherwise use authorized tools or report limitations. Share evidence and context without mandatory handoff files. Do not duplicate observations or assume a dispatch interface. Clarify ambiguous write intent before acting. General policy changes require explicit justification and user notification.
