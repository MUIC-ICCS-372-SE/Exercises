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

# Team 03 — CityBite Bangkok

## Final Score: 16.2 / 20

## Summary

This is a good early Product Brief v0.5. Your team understood the general CityBite problem: orders arrive through multiple channels, menu information may be inconsistent, order details may be inaccurate, and order status is unclear. The proposed direction of a digital ordering and status-tracking system fits the case.

The brief is complete and covers all required sections. The MVP scope is not unreasonable for a team of six students over about two months, **if** the features are implemented simply. Menu display, cart/order submission, availability toggles, staff order inbox, and status updates can fit a reasonable MVP. Customization and ETA can also fit if kept basic and staff-controlled rather than automated or complex.

The main improvements needed are writing quality, clearer user-need wording, and more measurable success criteria. The user needs are not completely wrong, but some of them are written too much like features or are too vague. For v1, rewrite them as user problems first, then connect them to possible features.

## Score Breakdown

| Criterion                                             |       Score | Feedback                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ----------------------------------------------------- | ----------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Problem Understanding and Case Alignment**       | **3.2 / 4** | The problem statement correctly identifies multiple ordering channels, inaccurate orders, inconsistent menu information, unclear order status, and increased difficulty as demand grows. This fits the CityBite case. However, the explanation is still general. For v1, add more concrete operational detail: unavailable items may still be requested, order changes may be missed, staff may not know the exact current status of an order, or customers may need to ask repeatedly for updates.                                                                                                                                             |
| **2. Stakeholders, User Roles, and User Needs**       | **2.4 / 3** | Customer, Staff, and Owner are appropriate roles. The staff and owner needs are reasonably connected to the case. The user needs are not mostly wrong, but some are vague or feature-like. For example, “they interact with the real time tracker” describes a feature rather than a user need. “Immediate response” should be rewritten as something like: “Customers need to quickly know which menu items are available and whether their order has been received.” “Status Information” should be rewritten as: “Customers need a clear way to check order progress without repeatedly calling or messaging staff.”                         |
| **3. MVP Scope and Out-of-Scope Boundaries**          | **2.6 / 3** | The MVP scope is broad but generally feasible for a 6-person team over about two months if implemented simply. Menu display, limited customization, operating hours, cart/order submission, status tracker, staff availability updates, order inbox, and order details can form a coherent food-ordering MVP. The team should still prioritize carefully: the core workflow should be customer views available menu → submits order → staff sees order → staff updates order status. ETA should be simple and staff-controlled, not automatically calculated. Customization should be limited to simple options rather than complex menu logic. |
| **4. Assumptions, Constraints, and Risks**            | **2.3 / 3** | The assumptions, constraints, and risks are present and mostly relevant. Scope creep, staff adoption, data synchronization, over-engineering, and unfamiliar technologies are good risks. However, some assumptions need clearer writing, such as “Menu items is do not require highly complex, multi-level customization.” Some mitigations may also introduce complexity, such as “real-time syncing.” A simpler mitigation may be manual staff toggles for item availability and simple status updates.                                                                                                                                      |
| **5. Success Criteria / What Makes the MVP Valuable** | **2.2 / 3** | Several success criteria are useful: centralization, menu accuracy, preventing unavailable item orders, structured order lists, and status visibility. However, some are vague or difficult to measure, such as “Customer feeling” and reducing messages asking “what when why how.” For v1, rewrite success criteria so they are judgeable, for example: “Customers can submit an order only with currently available items,” or “Staff can view all active orders and update their status from one dashboard.”                                                                                                                                |
| **6. Initial Technical Direction and Feasibility**    | **2.0 / 2** | The initial technical direction is acceptable for this stage. React, Kotlin with Spring Boot or Ktor, PostgreSQL, GitHub, local demo, and basic CI are reasonable choices. If the team is comfortable with Kotlin, this is a valid backend direction. The technology choices are clear enough for Product Brief v0.5.                                                                                                                                                                                                                                                                                                                           |
| **7. Organization, Clarity, and Professionalism**     | **1.5 / 2** | The document is organized and all main sections are present, but the writing needs polish. Phrases like “operational costs slips,” “tons of order,” and “what when why how” are too informal or unclear for a product brief. For v1, revise for clearer and more professional wording.                                                                                                                                                                                                                                                                                                                                                          |

## Main Improvements for v1

1. Make the problem statement more concrete and operational.
2. Rewrite user needs so they describe user problems first, then connect them to features.
3. Define one clear core MVP workflow.
4. Keep ETA and customization simple; do not turn them into complex automated features.
5. Make success criteria measurable and judgeable.
6. Proofread grammar and replace informal wording with professional wording.
7. Clarify whether Kotlin/Spring is familiar to the team, even though it is acceptable as an initial technical direction.

## Concrete Examples for Revising User Needs

| Current wording                                                                                       | Why it can improve                                      | Better user-need wording                                                                                             |
| ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| “Customer... interact with the real time tracker.”                                                    | This describes a feature more than a need.              | Customers need a clear way to check order progress without repeatedly calling or messaging the shop.                 |
| “Immediate response.”                                                                                 | This is too broad. Immediate response to what?          | Customers need to quickly know which items are currently available and whether their order was received.             |
| “Status Information.”                                                                                 | The idea is right, but the sentence is unclear.         | Customers need to know whether their order is pending, being prepared, ready, or out for delivery/pickup.            |
| “Staff needs to quickly update order status, manage menus and be able to see all the orders at once.” | This is valid, but can be separated into clearer needs. | Staff need one place to view incoming orders, update item availability, and change order status during busy periods. |
