# ICCS 372 — Term Project Case Brief

## Case 3 - GearLoop Bangkok Equipment Rental and Return Tracking

---

### 1. What this case is
Your team is acting as a small software engineering team engaged by an equipment rental business in Bangkok. The business is not asking for a large commercial logistics platform. They want a practical first version of a digital system that would make rental handling clearer and more reliable.

This document gives you the business context, the customer’s situation, and the problems they are experiencing. It is **not** a finished product brief, a completed backlog, or a final system design. Your team must still analyze the case, define the MVP, decide what is included and excluded, and justify how your solution should work.

---

### 2. Business context
GearLoop Bangkok rents equipment such as cameras, lighting kits, microphones, tripods, and accessories for short periods. Customers may ask about availability, rental periods, and return timing through phone calls, chat, or other informal channels. Staff then check item status manually and keep track of requests and returns using spreadsheets, notes, and memory.

The owner feels that this process is becoming harder to trust as the number of items and requests grows. It is still possible to run the business this way, but staff spend too much time checking whether something is available, whether it has already been promised to another customer, and whether it has actually been returned.

The owner is not trying to acquire a full warehouse or enterprise inventory system. They want a realistic first step toward better visibility over rentals and returns.

---

### 3. Current situation
The business currently handles rental requests in a way that depends heavily on manual coordination. A customer might ask whether an item is available for certain dates, and staff may need to look in one place for past notes, another for a booking list, and another for return information. Even when the answer exists somewhere, it is not always obvious quickly.

Returned items can also be difficult to track consistently. Something may be physically back, but not clearly marked as ready. Another item may still be out, but a staff member may not immediately see when it is expected to return. This creates uncertainty for both customers and staff.

---

### 4. Notes from conversations with the customer
The owner said the business often loses time not because staff do not know the business, but because the information is scattered. One person may remember that a camera is out until Friday, another may think it was already returned, and someone else may only know that “it should be available soon.”

A staff member described a common frustration: a customer asks for several items together, staff can answer about one of them quickly, but not confidently about the others. Another common issue is that a return is expected, but there is no simple shared way to see whether it has actually come back, whether it is unavailable for another reason, or whether it can be promised again.

The owner hinted that the MVP does not need to model every edge case around deposits, damage, or logistics. A simpler workflow that makes request handling, approval, and return status clearer would already be useful.

---

### 5. Main problems observed
From the case information, your team should consider problems such as:

- rental requests arriving through multiple channels
- unclear or untrusted item availability
- possible double-booking or promise conflicts
- incomplete or inconsistent customer and rental details
- unclear tracking of returned items
- limited visibility into which items are currently out, pending, or available

These are starting points for your analysis. Your team should decide which problems matter most for the first MVP.

---

### 6. What the customer hopes will improve
The business wants a clearer process for checking items, recording rental requests, and tracking returns. They want customers to have a better way to understand what can be requested, and they want staff to review requests and update item status in a more structured and reliable way.

The owner is not expecting a complete commercial rental platform. They are looking for an MVP that shows how the business could reduce confusion and improve day-to-day operations.

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
A good outcome is not the largest rental platform. A good outcome is a focused MVP that addresses the real operational confusion around requests, availability, and returns, while remaining technically coherent and realistically scoped.

Your team should aim to show that you understood the business problem, made disciplined decisions, and built something practical enough to be credible.