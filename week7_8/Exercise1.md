# Activity — Project Realignment and Artifact Repair

## Learning Objective

By completing this assignment, your team should be able to reassess earlier project artifacts based on instructor feedback, revise them so they accurately represent the current system and scope, record recent important decisions through ADR #2, and make realistic project decisions so the remaining implementation can be completed on time.

## Activity Type

Team in-class assignment.

## Time Allocation

Lecture / briefing: in class

Working time: in class

Final cleanup and submission: after class if needed, by Wednesday next week.

## Instructions

This activity takes place after the instructor has already given feedback on your earlier Product Brief and Architecture Page.

Your team must now use that feedback to revise the project in a realistic and professional way.

This is not a full rewrite of the project.

This activity is meant to show that your team can:

* reassess earlier work honestly
* repair important project artifacts
* incorporate instructor feedback where applicable in both content and presentation/style
* adjust scope if necessary
* record recent important decisions in ADR #2
* keep the project finishable within the remaining time

By the end of Week 10, implementation should be complete. Your revisions should therefore help your team make realistic decisions about what can still be built.

## Writing Expectations

Your writing in this activity should be specific, concrete, and professional.

This means:

* name actual features, flows, pages, modules, or decisions instead of speaking only in vague general terms
* explain your reasoning, not only your conclusion
* use professional academic and engineering language
* avoid casual, unclear, or overly conversational wording
* make sure each section says something meaningful and evidence-based

Weak example:

* "We changed some things to make the project better."
* "The board is good and we are doing fine."

Stronger example:

* "We removed the booking cancellation feature from the current implementation scope because the approval flow and status update flow are not yet stable. This allows the team to focus on completing the core booking submission and staff review workflow first."
* "The board shows that frontend booking form integration and order status update logic remain unfinished. These are now the highest-priority implementation tasks because both are required for the core end-to-end workflow."

Students in this course are expected to take the activity seriously and write at an appropriate university level.

## Required Content (4 tasks)

Your team must complete the following:

1. Revised Product Brief

   * Update the existing Product Brief markdown file in your repository.
   * Revise it so it accurately reflects the team’s current project direction.
   * Apply earlier instructor feedback where applicable.
   * Focus especially on:

     * problem statement
     * user roles
     * in-scope items
     * out-of-scope items
     * assumptions / constraints
     * success criteria if needed

2. Revised Architecture Page

   * Update the existing Architecture Page markdown file in your repository.
   * Revise it so it accurately reflects the system your team actually intends to build.
   * Apply earlier instructor feedback where applicable.
   * Make sure it clearly shows:

     * main users / actors
     * major system parts
     * main request / data flow
     * persistent storage
     * mocked / external / excluded parts if relevant

3. ADR #2

   * Add an ADR #2 document to your repository.
   * Keep it short and focused.
   * Follow the same general structure and expectations as ADR #1.
   * Record meaningful recent decisions your team has made, changed, or seriously considered.
   * This document may contain one ADR or multiple ADR entries, depending on your team’s recent decisions.

   Good topics include decisions related to:

   * scope reduction or scope change
   * architecture or data flow adjustments
   * implementation approach changes
   * mocking, simplification, or deferral choices
   * workflow or delivery decisions with real tradeoffs

   Avoid weak ADRs that describe trivial preferences or decisions with no meaningful tradeoff.

4. Project Realignment Report

   In one Google Doc, write a short report with the following three sections.

   Each required sub-section should be about 100–400 words.

   ### Section A: Scope Recalibration

   Write this section in two separate sub-sections:

   * Sub-section 1: Explain what was reduced, removed, simplified, deferred, or kept.
   * Sub-section 2: Explain why those decisions were made and what your team now considers the minimum realistic implementation.

   Be concrete. Name actual features, flows, or parts of the system. Explain why the decision was made. Do not write only general statements such as “we adjusted the scope to make it smaller.”

   ### Section B: Current Delivery Alignment

   Write this section in two separate sub-sections and include screenshot evidence.

   * Sub-section 1: Explain the team’s current priority or work direction, and explain what the board / current work status shows.
   * Sub-section 2: List and explain the 3–5 most important remaining implementation tasks.

   Required evidence:

   * include updated board screenshot(s)

   The screenshots must be readable and relevant. The writing must refer to the evidence shown. Do not just paste screenshots without explanation. Use professional language and explain what the evidence means.

   ### Section C: Completion Forecast

   Write this section in two separate sub-sections:

   * Sub-section 1: Explain the biggest remaining risks or blockers.
   * Sub-section 2: State clearly whether the current plan is realistic and why.

   This section should be honest and specific. If your team is behind, say so clearly. If your plan depends on simplifying scope, say that clearly as well. Do not avoid difficult realities by using vague language.

## Submission

Submit the following:

1. Repository updates

   * Update the existing Product Brief and Architecture Page markdown files directly in your repository.
   * Add ADR #2 to your repository.
   * Do not submit separate replacement copies of those files unless the instructor explicitly asks for them.

2. Google Classroom submission

   * Create one Google Doc containing:

     * Project Realignment Report
     * required screenshots / evidence
   * The report must contain these three sections:

     * Scope Recalibration
     * Current Delivery Alignment
     * Completion Forecast
   * Within each of those sections, write the required parts in separate sub-sections.
   * Export that Google Doc as PDF.
   * Submit the PDF to the Google Classroom assignment.

## File Naming

Submit the Google Classroom PDF using this file name:

```
Team[xx]_Project_Realignment_and_Artifact_Repair.pdf
```

## In-Class Working Advice

Use your class time efficiently.

Suggested order:

1. Review earlier instructor feedback together
2. Identify only the most important fixes and decisions
3. Decide whether scope needs adjustment
4. Update Product Brief
5. Update Architecture Page
6. Write ADR #2
7. Prepare the Google Doc report and screenshots
8. Confirm the remaining implementation plan

## What Not to Do

Do not:

* rewrite the entire project from zero
* add many new features just because they sound interesting
* spend all your time polishing wording or formatting
* keep unrealistic scope just to avoid cutting things
* leave contradictions between documents and implementation
* ignore earlier instructor feedback

## Rubric — Project Realignment and Artifact Repair (20 pts)

| Criterion                                                                    | Excellent                                                                                                                                                                                                                      | Good                                                                                                                                                                                         | Satisfactory                                                                                                                                         | Not Acceptable                                                                                                              |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Product Brief revision and scope realism (5 pts)                             | **5 pts** — Product Brief is revised clearly and realistically. It reflects the current project accurately, applies earlier feedback well, and shows strong scope judgment.                                                    | **3.5 pts** — Product Brief is mostly revised well and reflects the current project, but some parts remain vague, weak, or insufficiently corrected.                                         | **1.5 pts** — Product Brief shows limited revision. Some correction is visible, but realism, scope clarity, or feedback incorporation is still weak. | **0 pts** — Product Brief is not meaningfully revised, does not reflect the current project, or ignores important feedback. |
| Architecture Page revision and system alignment (5 pts)                      | **5 pts** — Architecture Page clearly reflects the current intended system, responsibilities, and major flow. Earlier feedback is incorporated well, and the page aligns with the actual project direction.                    | **3.5 pts** — Architecture Page is mostly understandable and reasonably updated, but some important parts are unclear, incomplete, or not fully aligned.                                     | **1.5 pts** — Architecture Page shows only partial revision. Alignment with the current system is weak or still confusing.                           | **0 pts** — Architecture Page is missing, not meaningfully revised, or does not represent the current system.               |
| ADR #2 quality and relevance (4 pts)                                         | **4 pts** — ADR #2 records one or more meaningful recent decisions clearly. It reflects real project tradeoffs, is relevant to the current project state, and follows the expected ADR style well.                             | **3 pts** — ADR #2 records a mostly relevant decision, but the reasoning, alternatives, or tradeoffs are somewhat thin or incomplete.                                                        | **1 pt** — ADR #2 is present but weak, vague, or only loosely connected to the real project situation.                                               | **0 pts** — ADR #2 is missing, trivial, or does not record a meaningful decision.                                           |
| Feedback incorporation and professional revision quality (3 pts)             | **3 pts** — Team clearly uses earlier instructor feedback in both content and presentation/style where relevant. Revisions are thoughtful, specific, well-reasoned, and professionally written.                                | **2 pts** — Team uses some earlier feedback appropriately, but the application is uneven or incomplete. Writing is mostly acceptable but may still contain some vagueness or weak reasoning. | **1 pt** — Team responds to feedback only superficially or inconsistently. Writing is often vague, weakly reasoned, or unprofessional.               | **0 pts** — Team ignores earlier feedback or shows no meaningful attempt to apply it.                                       |
| Project realignment report, supporting evidence, and completion plan (3 pts) | **3 pts** — The report is clear, realistic, and supported by meaningful evidence such as board screenshots and remaining tasks. Scope recalibration, current delivery alignment, and completion forecast are all handled well. | **2 pts** — The report and evidence are mostly useful, but some parts are shallow, unclear, or only partly realistic.                                                                        | **1 pt** — The report is basic and shows limited evidence of realistic planning or delivery awareness.                                               | **0 pts** — The report/evidence is missing or does not show realistic planning.                                             |
