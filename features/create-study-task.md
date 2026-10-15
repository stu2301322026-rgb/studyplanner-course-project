# Create Study Task - Feature Specification

## Jira Reference
KAN-6 - Create Study Task

## User Story
As a student, I want to create study tasks so that I can organize my university assignments.

## Functional Requirements
- The student can enter a task title.
- The student can enter an optional description.
- The student can select a university subject.
- The student can select a deadline.
- The system validates required fields before saving.
- The new task appears in the task list after saving.

## Acceptance Criteria
1. The task creation form contains title, description, subject and deadline fields.
2. The title field is mandatory.
3. A task cannot be saved with an empty title.
4. A successfully saved task appears in the task list.

## Validation
- Empty or whitespace-only titles are rejected.
- Invalid dates are rejected.
- Validation errors are displayed to the student.

## Implementation Status
This document describes the planned functionality. Implementation is outside the scope of this documentation change.
