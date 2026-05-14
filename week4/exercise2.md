# Activity 2 — ADR #1: Architecture Decision Record

## Learning Objective

By completing this assignment, your team should be able to record an important technical or design decision, explain the alternatives considered, and describe the tradeoffs and consequences of the decision.

## Activity Type

Team assignment.

## Time Allocation

30 minutes

This assignment may be completed outside class.

## Instructions

Your team must write **ADR #1** for one meaningful decision related to your project.

Choose a decision that affects the system design, implementation approach, team workflow, or delivery risk.

Good ADR topics include:

* Choosing a monolithic app vs separated frontend/backend.
* Choosing a database or storage approach.
* Choosing a status workflow.
* Choosing a booking/order/request approval flow.
* Choosing to mock an external service.
* Choosing a staff authentication or access approach.
* Choosing a local demo vs hosted demo approach.
* Choosing fixed time slots vs flexible scheduling.

Avoid weak ADR topics such as:

* Choosing a button color.
* Choosing VS Code.
* Using GitHub only because the instructor required it.
* Decisions with no meaningful tradeoff.

## ADR Template

Use this structure:

```markdown
# ADR 001: [Decision Title]

## Status
Accepted / Proposed / Deprecated

## Context
What situation or problem forced this decision?

## Decision
What did the team decide?

## Alternatives Considered (at least 1)
- Option A: Name & Short Reasoning
- Option B: ...
- Option C: ...

## Reasoning
Why did the team choose this option?

## Consequences
Positive:
- ...

Negative / Tradeoffs:
- ...

## Related backlog items (if none, create them on the board)
- Related backlog items:
- Related PRs, if any:
```

## Submission

1. Push to your team repository:

```text
/docs/architecture/adrs/0001-[short-decision-title].md
```

Example:

```text
/docs/architecture/adrs/0001-use-simple-monolithic-backend.md
```

2. Then each team document owner submits to the assignment on Google classroom of the file in rendered PDF.

## What Good Looks Like

A good ADR:

* Records a real decision.
* Explains why the decision was needed.
* Includes at least two alternatives.
* Describes tradeoffs honestly.
* Connects to the project’s scope, timeline, risks, or implementation plan.
* Is short enough to be useful later.

---
