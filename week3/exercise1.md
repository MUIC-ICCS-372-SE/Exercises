# Week 3 Workshop Exercise 1

## Deriving User Stories from the Product Brief

## Purpose

In this exercise, your team will turn your Product Brief into candidate user stories. The goal is to identify what different users need from the system before creating formal backlog items on the project board.

A user story should describe value from the user’s perspective, not only a technical task.

## User Story Format

Use this format:

```text
As a [user role], I want [capability], so that [benefit].
```

Example:

```text
As a customer, I want to browse available spaces so that I can decide what to book.
```

## Step 1 — Review Your Product Brief

Open your team’s Product Brief and review:

- Problem Statement
- Target Users
- In-Scope Functionality
- Out-of-Scope Functionality
- Success Criteria
- Assumptions and Risks

Look for sentences that imply something a user needs.

Example brief statement:

```text
Customers need a clearer way to submit booking requests, and staff need a simple way to manage reservations.
```

Possible user stories:

```text
As a customer, I want to submit a booking request so that staff can review my reservation.

As staff, I want to view incoming booking requests so that I do not miss reservations.
```

## Step 2 — Identify User Roles

List the main user roles in your project.

Examples:

```text
Customer
Staff
Admin
Owner
```

Keep the roles simple. Do not create too many roles unless they truly behave differently in the system.

## Step 3 — Derive Candidate User Stories

Write candidate user stories for each major role.

Minimum output:

- At least **3 customer/user stories**
- At least **3 staff/admin stories**

Focus on core MVP functionality first.

Avoid optional or advanced features unless your core workflow is already clear.

## Step 4 — Check Story Quality

For each story, ask:

1. Is the user role clear?
2. Is the capability clear?
3. Is the benefit or reason clear?
4. Is this small enough to build and check?
5. Does this support the MVP?

Weak story:

```text
As a user, I want a booking system.
```

Better story:

```text
As a customer, I want to submit a booking request so that staff can review and confirm my reservation.
```

## Expected Output

Submit or prepare a list of candidate user stories containing:

- User role
- User story
- Short note explaining why the story matters
- Indication of whether the story is likely core MVP or optional

Suggested format:

| Role     | User Story                                                                             | Why It Matters                                          | Core / Optional |
| -------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------- | --------------- |
| Customer | As a customer, I want to browse available spaces so that I can decide what to book.    | Customers need to see what is available before booking. | Core            |
| Staff    | As staff, I want to update booking status so that reservations can be tracked clearly. | Staff need to manage the booking workflow.              | Core            |

---
