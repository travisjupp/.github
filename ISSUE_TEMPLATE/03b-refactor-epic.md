---
name: 'Refactor (Complex: Phases)'
about: Use for multi-stage architectural shifts or complex logic changes.
title: 'refactor: '
labels: refactor
---

## Goal: <Describe the objective, e.g., Migrate Item state to data-first pattern>

### Context
<Why is this necessary? e.g., "Components-in-state anti-pattern causing re-render lag">

### Phase 1: Structure & Interfaces
- [ ] <Type/DTO Task: e.g., "Define ItemFormData interface in AppTheme.ts">
- [ ] <Abstraction Task: e.g., "Extract Discovery/Definition fields to Item.tsx">
- [ ] <add specific structural task>

### Phase 2: Logic & Data Flow
- [ ] <State Task: e.g., "Initialize itemsFormData array in LoadItem">
- [ ] <Sync Task: e.g., "Implement updateItemFormData for onBlur synchronization">
- [ ] <add specific logic task>

### Phase 3: Testing & Cleanup
- [ ] Implement/Update relevant automated tests
- [ ] Verify logic flow and state transitions via logging/debugging
- [ ] Remove temporary debug code or internal logs
- [ ] Application functions as expected in target environment

