
<h1 align="center">LegacyBridge</h1>

<h2 align="center">
  🔮🤖 Make existing software AI-operable. 🔧💻
</h2>

<p align="center">
  <strong><em>Without rewriting it.</em></strong>
</p>

<p align="center">
  <img src="./assets/banner.png" alt="LegacyBridge" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-8975C9?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/Skills-5-9678D3?style=flat-square" alt="Skills">
  <img src="https://img.shields.io/badge/Architecture-Agentic-697FC0?style=flat-square" alt="Architecture">
  <img src="https://img.shields.io/badge/Platform-Independent-669C91?style=flat-square" alt="Platform">
</p>

<p align="center">
  <em>Learn. Operate. Orchestrate. Audit. Recover.</em>
</p>

<p align="center">
  <a href="./docs/">Architecture</a> ·
  <a href="./skills/">Skills</a> ·
  <a href="./docs/installation.md">Quick Start</a> ·
  <a href="./examples/">Examples</a>
</p>

---



LegacyBridge is a decision-driven skill framework for AI agents operating existing desktop and web software through authorized graphical interfaces. It is a collection of behavioral instructions, not a standalone automation engine.

## Why decision-driven skills?
A common architectural mistake is to divide skills by what AI can do rather than by how AI decides what capability it needs. LegacyBridge designs each skill around a distinct decision boundary. Skills can be used independently, combined on demand, revisited or skipped. There is no mandatory pipeline.

```mermaid
flowchart TD
 U[User goal and constraints] --> D{Current capability gap}
 D -->|Interface operation| O[GUI Operator]
 D -->|Business knowledge| L[Workflow Learner]
 D -->|Complex execution| T[Task Orchestrator]
 D -->|Independent verification| A[Business Auditor]
 D -->|Interrupted or uncertain state| R[Task Recovery]
 O --> E[Evidence and task state]
 L --> E
 T --> E
 A --> E
 R --> E
 E --> D
 E -->|Goal reached or blocked| F[Report and stop]
```

## Skills
| Skill | Decision boundary |
|---|---|
| [GUI Operator](skills/legacy-gui-operator/SKILL.md) | How do I operate this interface? |
| [Workflow Learner](skills/legacy-workflow-learner/SKILL.md) | What business rules do I need? |
| [Task Orchestrator](skills/legacy-task-orchestrator/SKILL.md) | How do I deliver this complex outcome? |
| [Business Auditor](skills/legacy-business-auditor/SKILL.md) | Is the actual business state correct? |
| [Task Recovery](skills/legacy-task-recovery/SKILL.md) | How can I safely resume? |

## Experimental Results

> Can an AI agent take over legacy software workflows more effectively through decision-driven skill composition?

<div align="center">

<table>
  <tr>
    <td align="center" width="50%">
      <b>Vanilla AI Agent</b>
      <h1>150+ min</h1>
      <img src="https://img.shields.io/badge/Status-Timeout-red?style=flat-square" />
    </td>
    <td align="center" width="50%">
      <b>LegacyBridge</b>
      <h1>13m 09s</h1>
      <img src="https://img.shields.io/badge/Skills%20%2B%20Prompt-Enhanced-9575CD?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <h2>91.23%+</h2>
      Runtime Reduction
    </td>
    <td align="center">
      <h2>11.41×+</h2>
      Runtime Ratio
    </td>
  </tr>
</table>

</div>

### Benchmark Overview

| Metric | Vanilla AI | LegacyBridge |
| :--- | :---: | :---: |
| Task | Cross-system CRM migration | Cross-system CRM migration |
| Target Records | 10 | 10 |
| Installed Skills | 0 | 5 |
| Runtime | 150+ min | **13m 09s** |
| Run Status | Timeout | Run ended |
| Relative Runtime | 100% | **≤ 8.77%** |

### Observed Capability Gains

- **Decision Intelligence** — Context-aware skill selection.
- **Business Learning** — Evidence-based discovery of business rules.
- **Adaptive Execution** — Mechanism switching instead of repetitive failures.
- **Risk Control** — Write safeguards and state-aware recovery.
- **Auditability** — Quantifiable and traceable business outcomes.
- **Knowledge Reuse** — Reusable operational paths and workflow knowledge.

> [!NOTE]
> These are preliminary experimental results. The baseline
> timed out after more than 150 minutes, while the enhanced
> run combined LegacyBridge Skills with prompt optimization.
> Runtime reduction does not represent a controlled measure
> of task-completion efficiency or the independent effect
> of Skills.

## Quick start
1. Use an agent environment with authorized GUI tools and a way to load skill instructions.
2. Copy the desired skill directories into the host's supported skill location, or load their Markdown instructions manually. Host-specific installation and automatic routing are not guaranteed.
3. Optionally load [agent guidance](agents/AGENT.md). Start with synthetic data and a read-only task.
4. Try the [examples](examples/README.md). For write tasks, explicitly authorize the target and scope.

## Applications
Potential applications include CRM and ERP migration, HR record reconciliation, finance data checks, education administration, repetitive data entry and interrupted business workflows. These are application candidates, not claims of production deployments.

## Evidence
An internal synthetic CRM experiment recorded 31 minutes for the first successful migration (including debugging and human guidance), and 8 minutes for the second. The observed elapsed-time reduction was approximately 74.2%; this is not a controlled benchmark or a comparison with manual labor. See [experiment notes](benchmarks/results.md).

## Documentation
- [Architecture and design](docs/architecture.md)
- [Installation and compatibility](docs/installation.md)
- [Safety and data handling](docs/security.md)
- [Environment observations](docs/environment-notes.md)
- [Demo status](demos/README.md)

## Status
Research prototype. The five skill instructions are included. Host integration, full-batch performance and independent audit/recovery require further validation. Original demo source and raw execution logs are not included.

## License
Proposed MIT licensing; see LICENSE. The repository owner must confirm ownership and permission before public release.


---

<p align="center">
  <img src="./assets/mascot-thanks.png" width="200" alt="LegacyBridge Mascot">
</p>

<h3 align="center">Thanks for stopping by! ♡</h3>

<p align="center">
  <em>Even old software deserves a little magic.</em>
</p>

<p align="center">
  If you find LegacyBridge useful, consider leaving a ⭐
</p>

<p align="center">
  Made with curiosity, code, and a little magic. 💜
</p>

