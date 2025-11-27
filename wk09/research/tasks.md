# Evaluation Tasks — Week 9

## Task 1: Filter and Complete
**Scenario**: you have just cooked for your family

**Instructions**:
1. Find the task titled "Cook dinner"
2. Delete it
3. Verify it's deleted

**Success criteria**:
- Participant finds correct task within 30 seconds
- deleting the task works (task is removed)
- Visual confirmation shown (task no longer there)

**Inclusion focus**: Keyboard access, screen reader announcement

---

## Task 2: Add New Task
**Scenario**: You've just been assigned a new coursework deadline.

**Instructions**:
1. Add a new task: "Submit COMP2870 Assignment 2"
2. Confirm it appears in the list

**Success criteria**:
- Form submission works (HTMX + no-JS)
- New task appears immediately (or after reload for no-JS)
- Confirmation message shown

**Inclusion focus**: Error handling (if blank title), status announcements

---

## Task 3: Edit Task Inline
**Scenario**: You made a typo in a task title.

**Instructions**:
1. Find task "Buy milk"
2. Edit it to "Buy oat milk"
3. Save the change

**Success criteria**:
- Edit mode activates (input appears)
- Save updates the title
- Focus returns to edited task

**Inclusion focus**: Focus management, keyboard-only editing, Cancel button

---

## Task 4: Delete Completed Task
**Scenario**: You've completed "Email supervisor" and want to remove it.

**Instructions**:
1. Find task "Email supervisor"
2. Delete it
3. Confirm it's gone

**Success criteria**:
- Confirmation shown (HTMX) OR form submits (no-JS)
- Task removed from list
- Status message announced

**Inclusion focus**: Confirmation (HTMX has `hx-confirm`, no-JS has none - documented trade-off)

---

## Metrics per Task

For each task, record:
- **Time-on-task** (seconds from start to completion)
- **Success** (1 = completed, 0 = abandoned)
- **Error count** (validation errors, wrong clicks)
- **Mode** (HTMX or no-JS)
