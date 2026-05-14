# ICCS 372 — Week 4 Activities & Assignments

## Architecture Page, ADRs, Sprint Meeting Practice, and Kick-off Presentation

---

# Overview

This week marks the transition from project planning into implementation readiness.

By the end of this week, each team should have:

1. A first version of the Architecture Page.
2. At least one Architecture Decision Record (ADR #1).
3. Experience conducting a structured sprint meeting.
4. A prepared project kick-off / implementation readiness presentation for the next class.

The purpose is not to create perfect documents. The purpose is to make the team’s design, decisions, responsibilities, and implementation direction clear enough to begin building responsibly.

---

# Activity 1 — Architecture Page v1

## Learning Objective

By completing this activity, your team should be able to explain the high-level structure of your system, including the main users, interfaces, backend/application logic, database or storage, external or mocked services, and the main request/data flow.

## Activity Type

Team activity and team assignment.

## Time Allocation

**In class:** maximum 1 hour
**Outside class:** teams may continue refining and submit within 3–5 days after class

## Instructions

During class, your team will begin drafting your Architecture Page v1.

Your architecture page should be short and practical. It should help another person understand what your team is building and how the major parts of the system relate to each other.

Your page should include:

1. **System Overview**

   * What system are you building?
   * Who are the main users?
   * What core workflow does the system support?

2. **High-Level Architecture Diagram**

   * Use a C4-lite style diagram.
   * You may combine System Context and Container-level ideas.
   * The diagram does not need to follow strict C4 notation, but it must be understandable.

3. **Main Components / Containers**

   * Customer-facing interface
   * Staff/admin interface
   * Backend/application logic
   * Database or persistent storage
   * External or mocked services, if any

4. **Main Data Flow**

   * Explain one or two important flows.
   * Example: customer submits order/booking/request → backend validates and stores it → staff views and updates status.

5. **Data Storage**

   * What data must be stored?
   * Where will it be stored?
   * Examples: users, services, menu items, bookings, orders, rental requests, statuses.

6. **External or Mocked Dependencies**

   * What external services, APIs, or integrations are real?
   * What will be mocked?
   * What is out of scope?

7. **Current Limitations / Open Questions**

   * What is still unclear?
   * What may change during implementation?

## Minimum Expected Diagram Content

Your diagram should show:

* Main users / actors
* Customer-facing interface
* Staff/admin interface
* Backend / application logic
* Database / persistent storage
* External or mocked services, if any
* Arrows showing the main request/data flow

## Suggested Tools

You may use any clear diagramming tool, such as:

* Miro (Recommended)
* diagrams.net / draw.io
* Mermaid
* Excalidraw
* Google Slides shapes

## Submission

Push to your team repository:

```text
/docs/architecture/architecture-page-team[xx].md   # without the bracket []
```

If your diagram is created externally, embed it as an image or link it clearly inside the architecture page.

On google classroom, document owner must submit the rendered version, use:

```text
Team[xx]_Architecture_Page_v1.pdf
```

## What Good Looks Like

A good Architecture Page v1 is:

* Clear enough for another team member to understand.
* Consistent with the product brief and backlog.
* Honest about what is real, planned, mocked, or out of scope.
* Focused on high-level structure, not unnecessary detail.
* Updated later if implementation changes significantly.

---

# Activity 2 — ADR #1: Architecture Decision Record

## Learning Objective

By completing this assignment, your team should be able to record an important technical or design decision, explain the alternatives considered, and describe the tradeoffs and consequences of the decision.

## Activity Type

Team assignment.

## Time Allocation

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

# Activity 3 — In-Class Sprint Meeting Practice

## Learning Objective

By completing this activity, your team should learn how to conduct a structured sprint meeting that reviews previous work, discusses current issues, assigns responsibility, and produces a clear client update.

## Activity Type

In-class team activity.

## Time Allocation

This activity must be done during class.

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

## Required Output

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
   docs/sprint-meetings/individual/contribution_sprint[x].md
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
Sprint Goal:

Selected Issues:
| Issue | Priority | Estimate | Owner | Notes |
|---|---|---|---|---|
| | | | | |

## 4. Risks / Blockers (if any)
- ...

## 5. Decisions Made (major decisions)
- ...

## 6. Action Items
| Action | Owner | Due Date |
|---|---|---|
| | | |

## 7. Client Update Owner
Name:
```

## Client Update Email Template

```text
Subject: [Team Name] Sprint Update — Week [X]

Dear [Client/Instructor],

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

Best regards,
[Name]
On behalf of [Team Name]
```

---

# Activity 4 — Individual Contribution Log: Week 4 and Ongoing

## Learning Objective

By maintaining a weekly contribution log, each student should be able to provide evidence of their personal contribution, reflect on their work, and communicate honestly about progress, blockers, and learning.

## Activity Type

Individual ongoing assignment.

## Time Allocation

Update weekly outside class.

Recommended time:

```text
10–20 minutes per week
```

## Instructions

Each student must write a weekly contribution log.

This does not need to be long or overly formal, but it must be specific enough to show what you personally contributed.

You should update your log every week. It will be graded at the end of the term.

## Contribution Log Template

```markdown
# Individual Contribution Log — Week [X]

Name:
Team:
Week / Date Range:

## 1. What I planned to do this week
- ...

## 2. What I actually did
- ...

## 3. Evidence Links
- Issue(s):
- Pull Request(s):
- Commit(s):
- Document(s):
- Meeting notes / other evidence:

## 4. Testing / Verification
- How did I check that my work was correct?
- Did someone review it?
- Did CI pass, if relevant?

## 5. Team Communication / Collaboration
- Meetings attended:
- Help given to teammates:
- Help received from teammates:

## 6. Blockers / Problems
- What blocked me?
- How did I respond?

## 7. Short Reflection
- What did I learn this week?
- What should I improve next week?

## 8. AI Assistance, if any
- What AI tool did I use?
- What did I use it for?
- How did I verify the result?
```

## What Good Looks Like

A good contribution log:

* Is updated weekly.
* Clearly states what the student personally did.
* Includes evidence links where possible.
* Mentions testing or verification.
* Shows honest reflection.
* Documents AI assistance if used.

Weak contribution logs usually say only:

```text
I helped the team.
I attended the meeting.
I worked on the project.
```

These are too vague. Be specific.

---

# Activity 5 — Project Kick-off / Implementation Readiness Presentation

## Learning Objective

By completing this assignment, your team should be able to consolidate your project artifacts into a professional client-style presentation and explain your project direction before implementation continues.

## Activity Type

Team assignment and team presentation.

## Time Allocation

**Preparation:** outside class
**Presentation:** next class

## Duration

Maximum presentation time:

```text
30 minutes per team
```

Recommended structure:

```text
20–25 minutes presentation
5–10 minutes Q&A
```

There is no strict slide limit. However, your team must not exceed the time limit.

## Instructions

Prepare a client-style project kick-off / implementation readiness presentation.

You are presenting to the client/instructor.

The purpose is to show that your team understands the problem, has a realistic scope, has begun architectural thinking, and is ready to proceed with implementation.

## Required Content

Your presentation should include:

1. **Project Overview**

   * What is the project?
   * What problem are you solving?

2. **Target Users**

   * Who are the main user roles?
   * What do they need?

3. **Problem and Pain Points**

   * What is wrong with the current workflow?
   * Why does the problem matter?

4. **Scope**

   * What is in scope?
   * What is out of scope?
   * What is optional only if the core is stable?

5. **Current Backlog and Sprint 1 Focus**

   * What are the most important backlog items?
   * What is the Sprint 1 goal?
   * What thin vertical slice will you build first?

6. **Architecture Page**

   * Show your high-level diagram.
   * Explain the main components.
   * Explain the main request/data flow.
   * Explain your data storage choice.
   * Mention external or mocked services.

7. **ADR #1**

   * What decision did you record?
   * What alternatives did you consider?
   * What tradeoffs did you accept?

8. **Sprint Plan and Responsibility Split**

   * Who is responsible for what?
   * What roles are currently assigned?
   * How will the team coordinate?

9. **Risks and Assumptions**

   * What are the main risks?
   * How will the team reduce those risks?
   * What assumptions should the client/instructor know?

10. **Next Steps**

* What will the team do immediately after this presentation?
* What should be ready for the Sprint 1 demo?

## Presentation Advice

Good presentation behavior:

* Do not read every word from slides.
* Use slides as support, not as a script.
* Explain decisions, not just features.
* Show the architecture diagram clearly.
* Be honest about risks and limitations.
* Make sure every team member understands the whole project.
* Practice once before presenting.
* Stay within the time limit.

Weak presentation behavior:

* Showing only UI mockups without explaining the system.
* Listing technologies without explaining responsibilities.
* Claiming too many features with no realistic plan.
* Having only one person understand the project.
* Presenting an architecture diagram that does not match the backlog.

## Submission

Submit the presentation slides before the next class.

Recommended format:

```text
PDF
```

If your team uses Google Slides, submit the shareable view link and ensure access is open to the instructor.

## File Naming

```text
TeamName_Week4_Kickoff_Presentation.pdf
```

---

# Week 4 Submission Summary

## Team Submissions

1. Architecture Page v1

   * `/docs/architecture/`

2. ADR #1

   * `/docs/architecture/adrs/0001-[decision-title].md`

3. Sprint Meeting Notes

   * suggested location: `/docs/sprint-meetings/week4.md`

4. Client Update Email

   * sent by one team member after the sprint meeting

5. Project Kick-off / Implementation Readiness Presentation

   * prepared outside class
   * presented next class

## Individual Submission

1. Individual Contribution Log — Week 4

   * updated individually
   * continue weekly until the end of the term

---

# Suggested Due Dates

The instructor may adjust exact dates in Canvas or Google Classroom.

Recommended timing:

| Item                                 | Work Mode                      | Suggested Due                                       |
| ------------------------------------ | ------------------------------ | --------------------------------------------------- |
| Architecture Page v1                 | Start in class, finish at home | 3–5 days after class                                |
| ADR #1                               | Outside class                  | Same deadline as Architecture Page or shortly after |
| Sprint Meeting Practice              | In class                       | During class                                        |
| Sprint Meeting Notes                 | In class / shortly after       | End of class or same day                            |
| Client Update Email                  | After sprint meeting           | Same day or within 24 hours                         |
| Individual Contribution Log — Week 4 | Individual, outside class      | End of week                                         |
| Kick-off Presentation Slides         | Outside class                  | Before next class                                   |
| Kick-off Presentation                | In class                       | Next class                                          |

---

# Closing Reminder

This week is about making the project buildable.

A good team does not need a perfect plan before implementation starts.

But a good team should have:

* a shared architecture picture,
* recorded technical decisions,
* a visible sprint plan,
* clear ownership,
* honest risk awareness,
* and evidence of individual contribution.

From this week onward, your team is expected to move from planning into implementation while keeping your artifacts updated as the project evolves.
