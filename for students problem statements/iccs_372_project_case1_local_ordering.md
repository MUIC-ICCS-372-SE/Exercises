# ICCS 372 — Term Project Case Brief

## Case 1 - CityBite Bangkok Digital Ordering

---

### 1. What this case is
Your team is acting as a small software engineering team engaged by a local food business in Bangkok. The business is not asking for a full commercial ordering platform. They want a practical first version of a digital system that would make customer ordering and internal order handling clearer.

This document gives you the business context, the customer’s situation, and the problems they are experiencing. It is **not** a finished product brief, a completed backlog, or a final system design. Your team must still analyze the case, define the MVP, decide what is included and excluded, and justify how your solution should work.

---

### 2. Business context
CityBite Bangkok is a small food business that currently handles orders through a mix of walk-in traffic, phone calls, and chat messages. Staff also answer questions about menu items, prices, availability, delivery area, and order progress through these same channels. Information is often updated manually and passed around informally.

The owner feels that this process is becoming harder to manage consistently. Orders still get through, but staff spend too much time re-checking what was ordered, whether something is still available, and what stage an order is at. When the shop gets busy, small mistakes and misunderstandings become more likely.

The owner is not asking for a full delivery ecosystem or enterprise retail platform. They want a sensible first step toward a clearer digital ordering workflow.

---

### 3. Current situation
At the moment, customers may ask what is available, place an order through chat or phone, or show up in person and ask for changes. Staff then record order details manually, communicate status informally, and try to keep menu information current across whichever channels are being used that day.

This creates several recurring problems. Menu information may not appear consistent to all customers. Item availability may change, but not everyone sees the change immediately. Staff may know that an order exists, but not have one clear place to verify the exact contents, customer details, or current status. Even when the business is functioning, the process can feel fragile once the pace picks up.

---

### 4. Notes from conversations with the customer
The owner said that most mistakes are not dramatic. More often, they are small operational slips: an item was unavailable but still requested, a customer changed something midway, a phone order was recorded differently from what the customer expected, or staff had to ask each other where an order currently stood.

A staff member mentioned that customers often ask the same kinds of things: “What do you still have?” “Can I order for pickup?” “Do you deliver nearby?” “Has my order been accepted yet?” “How long will it take?” Staff can usually answer, but they do not always have one reliable place to check.

The owner hinted that a useful MVP does not need to model every business rule or payment path. A simpler system that helps customers place clearer orders and helps staff track them more consistently would already be useful.

---

### 5. Main problems observed
From the case information, your team should consider problems such as:

- orders arriving through multiple channels
- inconsistent menu and availability information
- missed or imperfectly recorded order details
- unclear order progress
- slow or uncertain answers to customer questions
- limited visibility into what is being ordered and what is still in progress

These are starting points for your analysis. Your team should decide which problems matter most for the first MVP.

---

### 6. What the customer hopes will improve
The business wants a clearer path from browsing to order submission and from order receipt to status tracking. They want customers to understand what can be ordered and submit orders in a more structured way. They also want staff to handle incoming orders with less confusion.

The owner is not expecting every feature a commercial platform would have. They are looking for a believable MVP that shows how the business could reduce confusion and improve daily order handling.

---

### 7. Your task
Your team must turn this case into your own project proposal and delivery plan.

In your product brief and later project documents, your team must decide and justify:

- **Stakeholders and user roles** — who the key stakeholders and user roles are
- **User needs** — what the main user needs are
- **MVP scope** — what the MVP should include
- **Out of scope** — what should be excluded from the MVP
- **Assumptions** — what assumptions your team is making
- **Constraints** — what constraints affect your project
- **Risks** — what risks may affect delivery or product usefulness
- **Success criteria** — what success would look like for the first version
- **Usefulness evidence** — what evidence would show that the MVP is useful enough for this case

Do not simply list every possible feature. Your goal is to define a realistic first version that addresses the most important problems within the project time available.

---

### 8. Technical direction to include in your product brief
Your product brief should include an initial technical direction. Briefly state what type of system your team plans to build and what technologies you expect to use, including front end, back end, database or storage, and demo or hosting approach.

These choices do not need to be final at the start, but they should be realistic for your team and suitable for your proposed MVP. If your team later changes a major technical choice, record the reason in an ADR.

---

### 9. Expected project deliverables
Your team will still be expected to produce the course project deliverables, including:

- a product brief or kick-off document
- a backlog with user stories and acceptance criteria
- a project timeline
- high-level architecture and component diagrams
- ADRs
- a design document
- a working MVP
- handover materials as required by the course

This case brief only gives the starting situation. Your team’s job is to turn it into a clear, justified, and buildable software engineering project.

---

### 10. What a good outcome for this case looks like
A good outcome is not the largest food-ordering platform. A good outcome is a focused MVP that addresses the real confusion around order intake, menu clarity, and order tracking while remaining technically coherent and realistically scoped.

Your team should aim to show that you understood the business problem, made disciplined scope choices, and built something practical enough to be credible.