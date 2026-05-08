Week 3 Workshop Exercise 1

Deriving User Stories from the Product Brief

Purpose

In this exercise, your team will turn your Product Brief into candidate user stories. The goal is to identify what different users need from the system before creating formal backlog items on the project board.

A user story should describe value from the user’s perspective, not only a technical task.

User Story Format

Use this format:

As a [user role], I want [capability], so that [benefit].

Example:

As a customer, I want to browse available spaces so that I can decide what to book.

Step 1 — Review Your Product Brief

Open your team’s Product Brief and review:

Problem Statement

Target Users

In-Scope Functionality

Out-of-Scope Functionality

Success Criteria

Assumptions and Risks

Look for sentences that imply something a user needs.

Example brief statement:

Customers need a clearer way to submit booking requests, and staff need a simple way to manage reservations.

Possible user stories:

As a customer, I want to submit a booking request so that staff can review my reservation.

As staff, I want to view incoming booking requests so that I do not miss reservations.

Step 2 — Identify User Roles

List the main user roles in your project.

Examples:

Customer
Staff
Admin
Owner

Keep the roles simple. Do not create too many roles unless they truly behave differently in the system.

Step 3 — Derive Candidate User Stories

Write candidate user stories for each major role.

Minimum output:

At least 3 customer/user stories

At least 3 staff/admin stories

Focus on core MVP functionality first.

Avoid optional or advanced features unless your core workflow is already clear.

Step 4 — Check Story Quality

For each story, ask:

Is the user role clear?

Is the capability clear?

Is the benefit or reason clear?

Is this small enough to build and check?

Does this support the MVP?

Weak story:

As a user, I want a booking system.

Better story:

As a customer, I want to submit a booking request so that staff can review and confirm my reservation.

Expected Output

Submit or prepare a list of candidate user stories containing:

User role

User story

Short note explaining why the story matters

Indication of whether the story is likely core MVP or optional

Suggested format:

Role

User Story

Why It Matters

Core / Optional

Customer

As a customer, I want to browse available spaces so that I can decide what to book.

Customers need to see what is available before booking.

Core

Staff

As staff, I want to update booking status so that reservations can be tracked clearly.

Staff need to manage the booking workflow.

Core

Week 3 Workshop Exercise 2

Create Backlog Items on the GitHub Project Board

Purpose

In this exercise, your team will convert selected user stories and technical work into backlog items on your GitHub Project board.

The goal is to create a usable Backlog v1 that your team can use for Sprint 1 planning.

Required Board Item Types

Use these types:

Type

Meaning

Example

Feature

User-visible product capability

Customer submits booking request

Bug

Something expected does not work

Booking status does not update correctly

Chore

Setup, maintenance, or support work

Set up project repository structure

Task

Investigation or research work

Investigate suitable database option

For this course, use Task instead of “Spike.”

Required Fields

Each board item should include:

Title

Type

Description

Acceptance Criteria

Notes / Constraints

Priority

Estimate

Use priority:

P0 = must have for core workflow / Sprint 1 candidate
P1 = important for MVP
P2 = useful if core is stable
P3 = optional or likely out of scope for now

Use estimate:

S = small
M = moderate
L = large or risky
XL = too large; should probably be split

Step 1 — Create GitHub Issues from Your Candidate Stories

Take your strongest candidate user stories from Exercise 1 and create GitHub issues for them.

Minimum:

3 customer/user feature items

3 staff/admin feature items

2 Chore or Task items

Each issue should be added to your GitHub Project board.

Step 2 — Write Clear Titles

A title should be short and specific.

Weak title:

Booking

Better title:

Customer submits booking request

Weak title:

Database

Better title:

Choose database for Sprint 1 MVP

Step 3 — Write the Description

The description explains the intention of the item.

It should usually be one short paragraph. For larger items, use at most 2–3 short paragraphs.

A good description should explain:

What this item is about

Which user or problem it supports

What behavior or outcome is expected

Any important context the team should know

Example description:

## Description

A customer should be able to select a space and submit a basic booking request with their name, contact details, preferred date/time, and selected space. This creates a booking request that staff can review later from the staff view.

Step 4 — Write Acceptance Criteria

Acceptance criteria explain how the team knows this item works.

Use Given / When / Then where appropriate.

Example:

## Acceptance Criteria

- Given a customer is viewing an available space, when they enter the required booking details and submit the request, then the system records the booking request.
- Given a required field is missing, when the customer tries to submit the request, then the system shows a validation message.
- Given a booking request was submitted successfully, when staff opens the booking list, then the new request appears with customer name, space, requested time, and status.

For a Task, acceptance criteria should describe the expected research output.

Example Task:

## Title

Choose database for Sprint 1 MVP

## Type

Task

## Description

Investigate whether SQLite is sufficient for the Sprint 1 MVP or whether the team should use PostgreSQL instead. The goal is to choose the safer database option for the first working demo, considering setup difficulty, team familiarity, and basic persistence needs.

This is an investigation task. The output should be a short recommendation, not production code.

## Acceptance Criteria

- Given the expected Sprint 1 data needs, when SQLite and PostgreSQL are compared, then the team can explain which option better fits the MVP.
- Given the team’s current skill level, when setup difficulty is reviewed, then the team can identify which option is safer for Sprint 1.
- Given the investigation is complete, when the issue is closed, then the issue contains a short recommendation with reasoning.

## Notes / Constraints

- Focus only on Sprint 1 needs.
- Do not build the full database layer as part of this task.
- Keep the investigation short and practical.

## Priority

P0

## Estimate

S

Step 5 — Add Notes / Constraints

Use this section for important boundaries.

Examples:

## Notes / Constraints

- No login is required for Sprint 1.
- Payment is out of scope.
- Use mock data if the real data model is not finalized.
- Keep the first version simple enough for a live demo.

Step 6 — Add Priority and Estimate

Each board item should have:

## Priority

P0 / P1 / P2 / P3

## Estimate

S / M / L / XL

Items marked L or XL should be reviewed. They may need to be split into smaller items.

Expected Output

Your GitHub Project board should contain:

8–12 backlog items

Each item has a clear title

Each item has a type: Feature / Bug / Chore / Task

Each item has a description

Sprint 1 candidate items have acceptance criteria

Each item has Notes / Constraints if needed

Each item has Priority: P0–P3

Each item has Estimate: S / M / L / XL

Items are visible on the GitHub Project board

Week 3 Workshop Exercise 3

Write Your Team’s Definition of Done v1

Purpose

In this exercise, your team will define what “Done” means for your project.

The Definition of Done is a team-level quality rule. It is not written separately inside every issue. Instead, it applies to all backlog items unless clearly marked as not applicable.

Acceptance criteria are specific to each issue.Definition of Done is shared across the whole project.

Difference Between Acceptance Criteria and Definition of Done

Item

Where it lives

Purpose

Acceptance Criteria

Inside each GitHub issue

Defines what this specific item must do

Definition of Done

Team/project document

Defines the general quality gate for completed work

PR checklist

Pull request template

Confirms the work followed the DoD before merging

Baseline Definition of Done

Start with this course baseline:

# Definition of Done v1

A backlog item can be moved to Done only if:

1. Acceptance criteria are met.
2. Work is linked to a GitHub issue.
3. Code changes are made through a pull request.
4. At least one teammate reviews the pull request.
5. CI passes, if code was changed.
6. Minimal tests or checks exist, if relevant.
7. Documentation is updated if behavior, setup, or usage changed.

Step 1 — Copy the Baseline DoD

Create a document in your repo, for example:

/docs/definition-of-done.md

Copy the baseline DoD into the document.

Step 2 — Discuss What Applies to Your Team

As a team, discuss:

What must always be true before work is Done?

What counts as enough testing for your MVP?

Who reviews pull requests?

When should documentation be updated?

How will you handle non-code items like Tasks or documentation changes?

For non-code items, some DoD rules may be not applicable.

Example:

If no code was changed, CI and tests may not apply.
However, the issue must still have a clear output and be reviewed by the team.

Step 3 — Add Team-Specific Rules

Add 1–3 team-specific rules if useful.

Examples:

8. Any new setup step must be added to README.
9. Any database schema change must be briefly documented.
10. A feature cannot be moved to Done unless at least one teammate has manually checked it.

Do not add too many rules. A DoD that is too long may be ignored.

Step 4 — Decide How the Team Will Use the DoD

Write a short note explaining how your team will apply the DoD.

Example:

## How We Use This DoD

Before moving an issue to Done, the owner checks the acceptance criteria and confirms that the DoD items are satisfied. For code changes, the pull request reviewer also checks the DoD before approving the PR.

Expected Output

Your team should produce:

/docs/planning/definition-of-done.md

The document should include:

Course baseline DoD

Any team-specific DoD rules

A short note explaining how the team will apply the DoD

Clarification for non-code items, if needed

Reminder

The DoD is not the same as acceptance criteria.

Acceptance criteria answer:

Does this specific item behave correctly?

Definition of Done answers:

Is this work complete enough for the team to trust it?

