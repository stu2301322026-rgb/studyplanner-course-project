# StudyPlanner - Test Scenarios

## Overview
This document describes planned test scenarios for StudyPlanner.

## TC-01: Create Study Task
Jira: KAN-6

Steps:
1. Open the study task creation form.
2. Enter a title, description, subject and deadline.
3. Click Save.

Expected Result: The new task appears in the task list.

## TC-02: Edit Study Task
Jira: KAN-7

Steps:
1. Open an existing study task.
2. Change its title and deadline.
3. Save the changes.
4. Reopen the task.

Expected Result: The updated information is displayed.

## TC-03: Validate Empty Task Title
Jira: KAN-6

Steps:
1. Open the task creation form.
2. Leave the title empty.
3. Click Save.

Expected Result: A validation error is shown and the task is not saved.

## TC-04: Add Exam
Jira: KAN-10

Steps:
1. Open the exam creation form.
2. Enter the exam name, subject, date and time.
3. Click Save.

Expected Result: The exam appears in the upcoming exams list.

## TC-05: Validate Exam Date
Jira: KAN-19

Steps:
1. Open the exam creation form.
2. Enter an exam name and select a date in the past.
3. Click Save.

Expected Result: A validation error is shown and the exam is not saved.

## Execution Status
All scenarios are documented for future execution. No automated tests have been run.

## Jira Reference
KAN-18 - Prepare test scenarios.
