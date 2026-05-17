# Activity 3 — In-Class Sprint Meeting Practice

## Learning Objective

By completing this activity, your team should learn how to conduct a structured sprint meeting that reviews previous work, discusses current issues, assigns responsibility, and produces a clear client update.

## Activity Type

In-class team activity.

## Time Allocation

This activity is demonstrated in class once. Then it must be conducted 45-90 minutes for every team each weekly sprint.
Occasionally the instructor may join as an observer/advisor during the sprint meetings throughout the term.

Recommended duration:

```text
30–45 minutes per team
```

The instructor may adjust the time.

## Purpose

From this week onward, teams should be able to conduct their own sprint meetings using a consistent structure.

The sprint meeting is not only a technical meeting. It is also a coordination and communication practice.

The goal is to keep work:

* visible,
* realistic,
* human,
* assigned,
* and aligned with the sprint goal.

## Sprint Meeting Structure

Your team should conduct the meeting using the following structure.

### 1. Opening

Start the meeting by greeting one another.

Each member briefly answers:

```text
How do you feel today?
```

This is not a technical question. It is a simple practice to remind the team that you are people working together, not just task machines.

### 2. Retrospective / Previous Sprint Review

Discuss what happened since the previous planning period.

Questions to answer:

* What did we complete?
* What did we not complete?
* What issues or blockers appeared?
* How were they handled?
* Which unfinished items should be moved to the current sprint?
* Which unfinished items should be paused, resized, or dropped?

### 3. Current Sprint Planning

Decide what should go into the current sprint.

For each selected issue, discuss:

* What is the issue about?
* Why is it important?
* What is the priority?
* What is the estimated size?
* Who owns it?
* Does it depend on another task?
* How will we know it is done?

Update the GitHub Project board during the meeting.

### 4. Short Closing Ceremony

Before ending the meeting, confirm:

* Sprint goal
* Selected sprint issues
* Owners
* Main blockers or risks
* Next immediate actions
* Who will send the client update email

### 5. Client Update Email

After the meeting, one team member sends a short email to the client/instructor summarizing the sprint meeting.

## Suggested Sprint Meeting Roles

Roles may rotate. One student may hold more than one role.

### Facilitator / Coordinator

* Runs the meeting.
* Keeps the discussion focused.
* Makes sure every member has a chance to speak.
* Watches the time.
* Prevents one issue from taking too much of the meeting.

### Board Operator (Could be the same person as facilitator)

* Updates the GitHub Project board during the meeting.
* Moves issues between columns.
* Updates priority, estimate, target sprint, and owner.

### Scribe / Documentation Owner

* Writes meeting notes.
* Records decisions, blockers, action items, and unresolved questions.

### Client Communication Owner

* Sends the sprint update email after the meeting.

### QA / Definition of Done Owner

* Reminds the team whether items satisfy the Definition of Done.
* Checks that review, CI, tests, and documentation are considered.

### Architecture / ADR Owner (Technically could be all or anyone)

* Notices when the team makes a decision that should become an ADR.
* Reminds the team to update the architecture page if needed.

### Jacks and Jills

* Flexible team members who help wherever needed.
* May support implementation, review, testing, documentation, debugging, or research.

## Required Output for each sprint meeting

Your team should produce:

1. Sprint meeting notes.
   Documentation Owner must push to team repository:\

   ```
   docs/sprint-meetings/notes/notes_sprint[x].md
   ```

2. Updated GitHub Project board.

3. Client update email.

4. Individual contribution log entries for the week.
   Each member must push to team repository:\

   ```
   docs/sprint-meetings/individual/[YourFirstName]_log_sprint[x].md
   ```

## Sprint Meeting Notes Template

```markdown
# Sprint Meeting Notes — Week [X]

Team:
Date:
Attendees:

## 1. Opening Check-in
- Member 1:
- Member 2:
- Member 3:
- Member 4:

## 2. Previous Work Review
Completed:
- Backlog item No# 
- ...

Not completed:
- Backlog item No# 
- ...

Problems / blockers:
- ...

## 3. Current Sprint Plan
Sprint Goal - (Description of purposeful goal(s) to achieve this sprint):

Selected Issues:
| Issue | Priority | Estimate | Owner | Notes |
|---|---|---|---|---|
| | | | | |

## 4. Risks / Blockers (if any)
- ...

## 5. Decisions Made (major decisions)
- ...

## 6. Action Items 
(Apart from backlog tasks on the board, any other small tasks (call client/write emails etc.) you agreed somebody should do? If no then don't fill it.)
| Action | Owner | Due Date |
|---|---|---|
| | | |

## 7. Client Update Owner
Name:
```

## Client Update Email Template

```text
Subject: "Team[YY] - Sprint [X] Update" -----> Where YY is your team number, and X is the sprint number, e.g. "Team07 - Sprint 1 Update".

Dear [Client/Company/Organization Name],

[Your message / Context / Warm and not alarming / But honest]

Completed since last update:
- ...

Current sprint focus:
- ...

Main blockers or risks:
- ...

Key decisions made:
- ...

Next actions:
- ...

[You can add anything else you deem necessary]:
- ...

Best regards,
[Name]
On behalf of [Team Name]
```

---
