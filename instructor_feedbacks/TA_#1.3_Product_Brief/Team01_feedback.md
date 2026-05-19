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

# Team 01 — LearnNest Bangkok

## Final Score: 17.2 / 20

## Summary

This is a good first Product Brief v0.5. Your team clearly understood the main LearnNest problem: inquiries and trial requests arrive through scattered channels, students or parents need clearer course information, staff need to distinguish inquiry stages, and the business needs better follow-up and seat visibility.

The strongest parts are the problem statement, user needs, assumptions, and constraints. The brief shows that your team understands the case and has a reasonable direction for the MVP.

However, several sections still contain wording or logic from the example case, especially “booking” and “room/desk” language. Since your case is about tutoring inquiries and enrollment coordination, “room/desk” clearly does not fit and should be removed. The word “booking” is also not ideal here; for LearnNest, “inquiry,” “trial request,” “class seat availability,” or “enrollment coordination” would usually be more precise.

Time slots themselves are valid for this case because classes, trial sessions, and schedules naturally involve time. The issue is not the idea of time slots; the issue is using example-case wording that makes the project sound like a room/desk booking system instead of a tutoring inquiry and enrollment system.

Another important correction: the AI Assistant should not be treated as a stakeholder or user role in the same way as Student/Parent, Staff, or Owner. It is better described as a system component, AI-assisted feature, or external service that supports the workflow. Your document does partly recognize this by saying the AI Assistant is a supporting component rather than a primary user, so this is not a severe misunderstanding, but the section should be reorganized for v1.

## Score Breakdown

| Criterion                                             |       Score | Feedback                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ----------------------------------------------------- | ----------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Problem Understanding and Case Alignment**       | **3.9 / 4** | You clearly identify the current situation and pain points: inquiries through chat and phone, trial requests, unclear seat availability, missed follow-ups, and the gap between inquiry and confirmed enrollment. This is strongly connected to the LearnNest case. The small deduction is mainly for wording. Phrases such as “communication and booking information is a mess” are understandable but too informal for a product brief, and “booking” is slightly less precise than “inquiry/enrollment information” for this case.                                                               |
| **2. Stakeholders, User Roles, and User Needs**       | **2.6 / 3** | Student/Parent, Staff, and Owner/Manager are appropriate roles, and their needs are mostly well explained. The user needs section is strong and case-specific. However, the AI Assistant should not be listed as a stakeholder or user role. It does not have its own business goals, responsibilities, or needs. It should be described as a system component, external service, or AI-assisted feature. Since your text also says the AI is a supporting component rather than a primary user, this is a moderate issue rather than a severe one.                                                 |
| **3. MVP Scope and Out-of-Scope Boundaries**          | **2.4 / 3** | The MVP direction is mostly realistic: course listing, inquiry form, staff dashboard, inquiry status update, course information management, and persistent records all fit the case. The core workflow is also clear. However, the “Staff Booking Dashboard” section mentions “selected room/desk,” which clearly belongs to the WorkNook example and does not fit LearnNest. The AI-assisted functionality should also be stated more explicitly in the MVP scope, because this is an AI-assisted case.                                                                                            |
| **4. Assumptions, Constraints, and Risks**            | **2.7 / 3** | The assumptions and constraints are good. You correctly mention demo data, manual enrollment confirmation, simplified seat availability, AI API limitations, and staff review of AI-generated summaries/classifications. Time slots are legitimate for this case because classes, trial sessions, and schedules can involve time-based availability. The main issue is wording and framing: risks should be written in LearnNest-specific terms, such as class seat conflicts, trial request conflicts, missed follow-ups, outdated course information, AI misclassification, and AI hallucination. |
| **5. Success Criteria / What Makes the MVP Valuable** | **2.4 / 3** | The success criteria are generally useful: students/parents can view class information, submit inquiries, see seat availability, and staff can follow up. However, the section still says “clearer booking workflow,” which should be “clearer inquiry and enrollment workflow.” Also add at least one AI-related success criterion, such as: “AI-generated summaries or inquiry classifications can be reviewed by staff before action is taken.”                                                                                                                                                  |
| **6. Initial Technical Direction and Feasibility**    | **1.6 / 2** | React, Node.js + Express, PostgreSQL, Git, and local demo are reasonable choices. However, because this is an AI-assisted case, the technical direction should mention how the AI assistant will be implemented: external API, mocked AI response, rule-based prototype, or another approach. You should also mention how AI outputs will be reviewed or stored.                                                                                                                                                                                                                                    |
| **7. Organization, Clarity, and Professionalism**     | **1.6 / 2** | The brief is well organized and mostly easy to read. The structure is complete. However, copied/mismatched wording reduces professionalism. The MVP list also skips numbering from 6 to 8. For the next version, proofread carefully and make sure every phrase fits the LearnNest case.                                                                                                                                                                                                                                                                                                            |

## Main Improvements for v1

1. Move the AI Assistant out of “Stakeholders and User Roles” and describe it as a system component or external service.
2. Replace remaining “room/desk” wording with LearnNest-specific wording.
3. Replace vague or mismatched “booking workflow” wording with “inquiry workflow,” “trial request workflow,” or “enrollment coordination workflow.”
4. Keep time slots where they make sense, but frame them as class schedules, trial class slots, or seat availability rather than coworking-style booking slots.
5. Make the AI assistant’s in-scope role clearer.
6. Rewrite risks around inquiry classification, class seat visibility, trial request conflicts, missed follow-ups, and AI misclassification.
7. Add success criteria for staff-reviewed AI summaries or classifications.
8. Proofread numbering and case-specific terminology.

**Score: 17.2 / 20**


