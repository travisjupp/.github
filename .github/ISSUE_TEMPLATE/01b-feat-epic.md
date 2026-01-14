---
name: 'Feature Epic (A-B-C)'
about: Use for high-level orchestration of multi-phase features and complex data lifecycles.
title: '[Epic] feat: '
labels: epic, enhancement
---

## Goal
[Describe the high-fidelity orchestration this Epic aims to achieve. Focus on
the user's journey from transient interaction to final data persistence and
reconciliation.]

## Technical Context
[Identify the infrastructure and data-pipes involved. Mention specific Redux
slices, the Wall of Providers, or hardware-bridged components like BottomSheet.
Reference relevant architectural documentation.]

## Implementation Track

### Phase 1: [Scaffolding & Initial Interaction]
- [ ] [Primary task for UI/Infrastructure foundation] (#[IssueNumber])
- [ ] [Action-dispatch or state-initialization task] (#[IssueNumber])
- [ ] [Refinement of design tokens or localized styling] (#[IssueNumber])

### Phase 2: [The Logic/Factory Engine]
- [ ] [Implementation of the primary container and lifecycle] (#[IssueNumber])
- [ ] [Architectural task for factory or sub-component logic] (#[IssueNumber])
- [ ] [Development of DTO factory logic for iterative expansion] (#[IssueNumber])
- [ ] **Verification**: [Describe the integration test suite required to ensure determinism] (#[IssueNumber])
- [ ] **Refactor**: [Describe any necessary architectural pivots or logic hardening] (#[IssueNumber])

### Phase 3: [Review & Reconciliation]
- [ ] **Architecture**: [Describe schema synchronization or data-pipe alignment] (#[IssueNumber])
- [ ] [Implementation of the review/audit interface] (#[IssueNumber])
- [ ] [Integration of reconciliation flow into the primary feature container] (#[IssueNumber])
- [ ] [Development of filter logic for final DTO reconciliation] (#[IssueNumber])
- [ ] [Implementation of final data persistence and transient store reset] (#[IssueNumber])

## Acceptance Criteria
- [ ] [Criteria 1: Successful navigation through the feature lifecycle]
- [ ] [Criteria 2: Verification of data reconciliation and collision prevention]
- [ ] [Criteria 3: User ability to audit and mutate transient data before persistence]
- [ ] [Criteria 4: Confirmation of final state persistence and transient store cleanup]

