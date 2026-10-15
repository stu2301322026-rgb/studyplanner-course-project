# StudyPlanner - Data Model

## Overview

This document describes the proposed data models for the StudyPlanner application.

## Student

- id: Unique identifier
- name: Student's full name
- email: Student's email address

## StudyTask

- id: Unique identifier
- title: Task title
- description: Task details
- subject: University subject
- dueDate: Task deadline
- isCompleted: Completion status
- studentId: Reference to Student

## Exam

- id: Unique identifier
- title: Exam name
- subject: University subject
- examDate: Date and time of the exam
- studentId: Reference to Student

## Relationships

- One Student can have multiple StudyTasks.
- One Student can have multiple Exams.
- Each StudyTask belongs to one Student.
- Each Exam belongs to one Student.

## Validation Rules

- Task title cannot be empty.
- Exam title and date are required.
- Student email must have a valid format.

## Jira Reference

KAN-17 - Design application data models.
