# Week 3 Workshop Exercise 3

## Write Your Team’s Definition of Done v1

## Purpose

In this exercise, your team will define what “Done” means for your project.

The Definition of Done is a team-level quality rule. It is not written separately inside every issue. Instead, it applies to all backlog items unless clearly marked as not applicable.

Acceptance criteria are specific to each issue.\
Definition of Done is shared across the whole project.

## Difference Between Acceptance Criteria and Definition of Done

| Item                | Where it lives           | Purpose                                             |
| ------------------- | ------------------------ | --------------------------------------------------- |
| Acceptance Criteria | Inside each GitHub issue | Defines what this specific item must do             |
| Definition of Done  | Team/project document    | Defines the general quality gate for completed work |
| PR checklist        | Pull request template    | Confirms the work followed the DoD before merging   |

## Baseline Definition of Done

Start with this course baseline:

```markdown
# Definition of Done v1

A backlog item can be moved to Done only if:

1. Acceptance criteria are met.
2. Work is linked to a GitHub issue.
3. Code changes are made through a pull request.
4. At least one teammate reviews the pull request.
5. CI passes, if code was changed.
6. Minimal tests or checks exist, if relevant.
7. Documentation is updated if behavior, setup, or usage changed.
```

## Step 1 — Copy the Baseline DoD

Create a document in your repo, for example:

```text
/docs/definition-of-done.md
```

Copy the baseline DoD into the document.

## Step 2 — Discuss What Applies to Your Team

As a team, discuss:

1. What must always be true before work is Done?
2. What counts as enough testing for your MVP?
3. Who reviews pull requests?
4. When should documentation be updated?
5. How will you handle non-code items like Tasks or documentation changes?

For non-code items, some DoD rules may be not applicable.

Example:

```text
If no code was changed, CI and tests may not apply.
However, the issue must still have a clear output and be reviewed by the team.
```

## Step 3 — Add Team-Specific Rules

Add 1–3 team-specific rules if useful.

Examples:

```markdown
8. Any new setup step must be added to README.
9. Any database schema change must be briefly documented.
10. A feature cannot be moved to Done unless at least one teammate has manually checked it.
```

Do not add too many rules. A DoD that is too long may be ignored.

## Step 4 — Decide How the Team Will Use the DoD

Write a short note explaining how your team will apply the DoD.

Example:

```markdown
## How We Use This DoD

Before moving an issue to Done, the owner checks the acceptance criteria and confirms that the DoD items are satisfied. For code changes, the pull request reviewer also checks the DoD before approving the PR.
```

## Expected Output

Your team should produce:

```text
/docs/definition-of-done.md
```

The document should include:

- Course baseline DoD
- Any team-specific DoD rules
- A short note explaining how the team will apply the DoD
- Clarification for non-code items, if needed

## Reminder

The DoD is not the same as acceptance criteria.

Acceptance criteria answer:

```text
Does this specific item behave correctly?
```

Definition of Done answers:

```text
Is this work complete enough for the team to trust it?
```

