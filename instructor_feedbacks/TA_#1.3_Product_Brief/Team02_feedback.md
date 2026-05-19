# ICCS 372 — Product Brief v0.5 Grading and Feedback

## Rubric Used — 20 pts

| Criterion                                         | Max Points |
| ------------------------------------------------- | ---------: |
| 1. Problem Understanding and Case Alignment       |          4 |
| 2. Stakeholders, User Roles, and User Needs       |          3 |
| 3. MVP Scope and Out-of-Scope Boundaries          |          3 |
| 4. Assumptions, Constraints, and Risks            |          3 |
| 5. Success Criteria / What Makes the MVP Valuable |          3 |
| 6. Initial Technical Direction and Feasibility    |          2 |
| 7. Organization, Clarity, and Professionalism     |          2 |
| **Total**                                         |     **20** |

## General Grading Note

This assignment is graded as a **Product Brief v0.5**, meaning it is an early draft and a first attempt at this kind of software engineering artifact. The grading therefore rewards serious effort, complete structure, clear case understanding, and reasonable early engineering judgment.

At the same time, the feedback is intentionally specific. The purpose of v0.5 is to help improve the next version. Mistakes such as unclear scope, copied wording that does not fit the assigned case, weak success criteria, or unrealistic MVP planning are still pointed out because they matter for Product Brief v1 and later project work.

Using the provided example as a structural guide is acceptable. However, the content must be adapted carefully to the team’s own case. The main issue is not using the example; the issue is leaving example-specific wording or logic in the submission when it no longer fits the assigned project.

---

# Team 02 — FixFlow Bangkok

## Final Score: 18.1 / 20

## Summary

This is the strongest Product Brief v0.5 among the submissions. Your team clearly understood the FixFlow case and the AI-assisted nature of the project. The problem statement explains the scattered repair request process well, and your stakeholder and user-needs sections are detailed and relevant.

The best parts are the problem statement, the stakeholder/user needs section, the AI guardrails, and the success criteria. You correctly recognize that AI must not make final decisions, diagnose dangerous problems, guarantee prices, or assign technicians without human review.

The main issue is still MVP scope, but it is not as severe as it may first appear. With a team of five students and about two months, the scope can be feasible **if** it is implemented as a simple repair request ticketing workflow: intake → AI-assisted summary → staff/owner review → job ticket → status update. The scope becomes too large only if the team tries to implement every listed idea fully, especially full communication sessions, multiple intake channels, authentication/security beyond basics, and technician coordination.

## Score Breakdown

| Criterion                                             |       Score | Feedback                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------------------------------------------------- | ----------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Problem Understanding and Case Alignment**       | **4.0 / 4** | The problem statement is strong. It clearly explains that FixFlow currently depends on manual coordination through phone calls and chat messages. You identify vague repair descriptions, scattered photos/addresses/times, lack of centralized tracking, limited visibility, and delayed customer updates. This is well aligned with the case.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **2. Stakeholders, User Roles, and User Needs**       | **3.0 / 3** | Customer, Staff/Technicians, and Owner are appropriate user roles. You explain what each role needs clearly. Customer needs include easy reporting, AI assistance, photo submission, and status visibility. Staff/technicians need structured job details and status updates. The owner needs oversight and AI review. This section is strong and case-specific.                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **3. MVP Scope and Out-of-Scope Boundaries**          | **2.1 / 3** | The MVP scope is broad, but many of the proposed items can fit if they are implemented in a simple way. A basic job request form, simple staff-entered request, status tracking, AI-generated summary, and owner/staff review can form one coherent ticketing workflow. However, the scope still needs tightening. Authentication, “basic security,” multiple intake methods, ongoing customer-technician communication, AI review pipeline, and expert/client loops should not all be treated as equally important MVP requirements. For v1, clearly define the must-have workflow and move secondary items to later scope. A good MVP core would be: customer submits repair issue with AI help → AI drafts structured request → owner/staff reviews → job ticket is created → staff/technician updates status. |
| **4. Assumptions, Constraints, and Risks**            | **2.5 / 3** | You include meaningful assumptions, constraints, and risks. The AI and human-in-the-loop constraints are especially good. However, some assumptions are too strong or risky, such as assuming all technicians will update statuses in real time and assuming terms/privacy policies are already handled. The risk table also has duplicated risks: “Staff interface or dashboard might become too large” duplicates “The staff dashboard becomes too large,” and “Overscoping AI complexity” appears twice. These should be merged in the next version.                                                                                                                                                                                                                                                           |
| **5. Success Criteria / What Makes the MVP Valuable** | **3.0 / 3** | This section is strong. The success criteria are clearly connected to the problem: structured intake, centralized dashboard, unified job context, owner oversight, and AI limitations. The AI limitation criterion is especially important and appropriate for this case. These are suitable success criteria for judging whether the first version is useful.                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **6. Initial Technical Direction and Feasibility**    | **2.0 / 2** | The initial technical direction is acceptable for Product Brief v0.5. ReactJS, Kotlin with Spring API, PostgreSQL, GitHub, local demo, and Docker Compose are clear and credible choices. For v1, you can strengthen this section by clarifying whether the AI assistant will use an external API, mocked AI, rule-based prototype, or hybrid approach.                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **7. Organization, Clarity, and Professionalism**     | **1.5 / 2** | The document is complete and generally well structured. However, some wording needs polishing, such as “expertise” when you likely mean “technician” or “expert.” There are repeated risks and some grammar issues. The writing is understandable, but the next version should be cleaner and more concise.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

## Main Improvements for v1

1. Define the MVP as one clear repair request ticketing workflow.
2. Separate must-have MVP items from optional/later items.
3. Move advanced or secondary ideas to later scope: full communication sessions, multiple intake channels, advanced security, deployment, and complex technician coordination.
4. Clean up the out-of-scope list and use more professional wording.
5. Merge duplicate risks: “Staff interface or dashboard might become too large” and “The staff dashboard becomes too large” are the same risk.
6. Merge duplicate risks: “Overscoping AI complexity” appears twice.
7. Revise overly optimistic assumptions, especially around technician real-time updates and privacy/legal handling.
8. Clarify the AI implementation approach.
9. Use “technician” or "expert" consistently instead of unclear wording such as “expertise.”

---

