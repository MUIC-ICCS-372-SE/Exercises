# Week 3 Workshop Exercise 2

## Create Backlog Items on the GitHub Project Board

## Purpose

In this exercise, your team will convert selected user stories and technical work into backlog items on your GitHub Project board.

The goal is to create a usable **Backlog v1** that your team can use for Sprint 1 planning.

## Required Board Item Types

Use these types:

| Type    | Meaning                             | Example                                  |
| ------- | ----------------------------------- | ---------------------------------------- |
| Feature | User-visible product capability     | Customer submits booking request         |
| Bug     | Something expected does not work    | Booking status does not update correctly |
| Chore   | Setup, maintenance, or support work | Set up project repository structure      |
| Task    | Investigation or research work      | Investigate suitable database option     |

For this course, use **Task** instead of “Spike.”

## Required Fields

Each board item should include:

1. **Title**
2. **Type**
3. **Description**
4. **Acceptance Criteria**
5. **Notes / Constraints**
6. **Priority**
7. **Estimate**

Use priority:

```text
P0 = must have for core workflow / Sprint 1 candidate
P1 = important for MVP
P2 = useful if core is stable
P3 = optional or likely out of scope for now
```

Use estimate:

```text
S = small
M = moderate
L = large or risky
XL = too large; should probably be split
```

## Step 1 — Create GitHub Issues from Your Candidate Stories

Take your strongest candidate user stories from Exercise 1 and create GitHub issues for them.

Minimum:

- 3 customer/user feature items
- 3 staff/admin feature items
- 2 Chore or Task items

Each issue should be added to your GitHub Project board.

## Step 2 — Write Clear Titles

A title should be short and specific.

Weak title:

```text
Booking
```

Better title:

```text
Customer submits booking request
```

Weak title:

```text
Database
```

Better title:

```text
Choose database for Sprint 1 MVP
```

## Step 3 — Write the Description

The description explains the intention of the item.

It should usually be **one short paragraph**. For larger items, use at most **2–3 short paragraphs**.

A good description should explain:

- What this item is about
- Which user or problem it supports
- What behavior or outcome is expected
- Any important context the team should know

Example description:

```markdown
## Description

A customer should be able to select a space and submit a basic booking request with their name, contact details, preferred date/time, and selected space. This creates a booking request that staff can review later from the staff view.
```

## Step 4 — Write Acceptance Criteria

Acceptance criteria explain how the team knows this item works.

Use Given / When / Then where appropriate.

Example:

```markdown
## Acceptance Criteria

- Given a customer is viewing an available space, when they enter the required booking details and submit the request, then the system records the booking request.
- Given a required field is missing, when the customer tries to submit the request, then the system shows a validation message.
- Given a booking request was submitted successfully, when staff opens the booking list, then the new request appears with customer name, space, requested time, and status.
```

For a **Task**, acceptance criteria should describe the expected research output.

Example Task:

```markdown
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
```

## Step 5 — Add Notes / Constraints

Use this section for important boundaries.

Examples:

```markdown
## Notes / Constraints

- No login is required for Sprint 1.
- Payment is out of scope.
- Use mock data if the real data model is not finalized.
- Keep the first version simple enough for a live demo.
```

## Step 6 — Add Priority and Estimate

Each board item should have:

```markdown
## Priority

P0 / P1 / P2 / P3

## Estimate

S / M / L / XL
```

Items marked **L** or **XL** should be reviewed. They may need to be split into smaller items.

## Expected Output

Your GitHub Project board should contain:

- 8–12 backlog items
- Each item has a clear title
- Each item has a type: Feature / Bug / Chore / Task
- Each item has a description
- Sprint 1 candidate items have acceptance criteria
- Each item has Notes / Constraints if needed
- Each item has Priority: P0–P3
- Each item has Estimate: S / M / L / XL
- Items are visible on the GitHub Project board

---


