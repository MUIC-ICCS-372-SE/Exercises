# Assignment 1 — Architecture Page v1

## Learning Objective

By completing this assignment, your team should be able to explain the high-level structure of your system, including the main users, interfaces, backend/application logic, database or storage, external or mocked services, and the main request/data flow.

## Activity Type

Team activity and team assignment.

## Time Allocation

**In class:** maximum 1 hour \
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
