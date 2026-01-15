---
name: 'Feature Epic (A-B-C)'
about: Use for high-level orchestration of multi-phase features and complex data lifecycles.
title: '[Epic] feat: '
labels: epic, enhancement
---

## Goal
[State the primary objective: e.g., "Implement a high-fidelity system for [user action] that ensures [data integrity/outcome] through a multi-step [lifecycle/process]."]

## Technical Context
[Identify the core modules: e.g., "Utilizes [Module A] for data-pipes and [Module B] for environmental orchestration. Reference [Schema/Doc] for persistence specifications."]

## Implementation Track

### Phase 1: [Scaffolding & Foundation]
- [ ] [Primary infrastructure task: e.g., "Provision the directory structure and base interfaces"] (#[IssueNumber])
- [ ] [State initialization: e.g., "Scaffold the initial state slice and dispatchers"] (#[IssueNumber])
- [ ] [Visual presentation: e.g., "Standardize design tokens and presentation components"] (#[IssueNumber])

### Phase 2: [Core Logic & Engine]
- [ ] [Lifecycle management: e.g., "Implement the primary container and lifecycle hooks"] (#[IssueNumber])
- [ ] [Business logic: e.g., "Architect the core factory logic or calculation engine"] (#[IssueNumber])
- [ ] [Data-transfer: e.g., "Engineer the DTO factory for iterative state expansion"] (#[IssueNumber])
- [ ] **Verification**: [Test suite description: e.g., "Execute integration tests to ensure logic determinism"] (#[IssueNumber])
- [ ] **Refactor**: [Hardening task: e.g., "Refactor the data-pipe to resolve environmental fragility"] (#[IssueNumber])

### Phase 3: [Review & Finalization]
- [ ] **Architecture**: [Alignment task: e.g., "Synchronize the transient schema with the persistent database"] (#[IssueNumber])
- [ ] [Audit interface: e.g., "Implement the user-facing review and reconciliation screen"] (#[IssueNumber])
- [ ] [Reconciliation logic: e.g., "Develop filter logic for final data reconciliation"] (#[IssueNumber])
- [ ] [Finalization: e.g., "Implement final data persistence and transient state reset"] (#[IssueNumber])

> **Note on Phase Structure**:
> To maintain a **modular** and **logical** track, structure phases by the flow of **Persistence**:
> - **Phase 1 (The Foundation)**: Focus on **Scaffolding**, **Interfaces**, and **Mocks**. This is the "Setup."
> - **Phase 2 (The Engine)**: Focus on **Processing**, **State Sync**, and **Verification**. This is the "Action."
> - **Phase 3 (The Persistence)**: Focus on **Reconciliation**, **Cleanup**, and **Final Audit**. This is the "Result."

## Acceptance Criteria
- [ ] [Lifecycle: e.g., "User successfully navigates from initial entry to final review."]
- [ ] [Integrity: e.g., "Verification of data reconciliation and prevention of state collisions."]
- [ ] [Audit: e.g., "User can audit and mutate transient data before final confirmation."]
- [ ] [Persistence: e.g., "Final confirmation clears transient stores and persists data to the main database."]
- [ ] Logic flow is verified via relevant automated tests
- [ ] State transitions are verified via terminal logging or debugger
- [ ] Build/Bundler successfully executes in target environment

