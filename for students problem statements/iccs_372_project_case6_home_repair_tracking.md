# ICCS 372 — Term Project Case Brief

## Case 6 - FixFlow Bangkok AI-Assisted Home Repair Request Tracking

### 1. What this case is
Your team is acting as a small software engineering team engaged by a neighborhood home-repair and maintenance business in Bangkok. The business is not asking for a full contractor management platform. They want a practical first version of a digital system that would make repair requests, job details, and job status easier to manage.

The business is also interested in using a simple AI-assisted chatbot to help customers describe repair problems more clearly and help staff turn messy customer messages into structured job requests.

This document gives you the business context, the customer’s situation, and the problems they are experiencing. It is **not** a finished product brief, a completed backlog, or a final system design. Your team must still analyze the case, define the MVP, decide what is included and excluded, and justify how your solution should work.

---

### 2. Business context
FixFlow Bangkok provides small home-repair services such as plumbing checks, air-conditioner cleaning coordination, electrical fixes, furniture assembly, and minor maintenance jobs. Customers usually contact the business through phone calls, chat messages, photos, or referrals from previous customers.

The business is small, and the owner personally coordinates most requests with a few regular technicians. This has worked for a while, but the process is becoming harder to manage as more customers ask for help, send unclear descriptions, change appointment times, or ask for updates.

The owner is not looking for an enterprise field-service platform, technician payroll system, or advanced route-planning system. They want a first step toward a clearer way to receive requests, structure job details, track progress, and reduce confusion.

---

### 3. Current situation
At the moment, repair requests arrive in different forms. One customer may send photos of a leaking pipe through chat. Another may call and describe an electrical issue. A third may ask whether someone can come during the weekend. Staff then write down notes, forward details to technicians, and try to remember which requests have been confirmed, visited, completed, or postponed.

The work can usually be handled, but it relies heavily on manual coordination. Sometimes a customer sends information in several messages, and the important details are scattered. Sometimes the technician needs to know the address, issue type, photos, preferred time, and urgency, but not all of those details are captured clearly.

Customers may also describe problems vaguely, such as “my aircon is leaking,” “the power keeps cutting,” or “the sink has a problem.” Staff then need to ask follow-up questions before they can create a useful job request. This back-and-forth takes time, especially when staff are handling multiple customers.

---

### 4. Notes from conversations with the customer
The owner said that the most stressful part is not always the repair work itself, but keeping track of what has been promised. They may know that “someone asked about a water leak yesterday,” but still need to search chat history to find the address, photos, or preferred visit time.

A staff member mentioned common customer questions: “Can someone come today?” “Did you receive the photo?” “Has the technician confirmed?” “How much will it cost?” “Is the job already completed?” These questions are reasonable, but they are difficult to answer quickly when request details are spread across messages and notes.

The owner is interested in whether an AI-assisted chatbot could help with the first stage of the workflow. For example, the chatbot could ask the customer for missing details, summarize the issue, and create a draft repair request for staff to review.

The owner does **not** expect the AI to perfectly diagnose the repair problem, estimate the exact price, assign technicians automatically, or make final business decisions. A basic assistant that improves request intake and reduces messy communication would already be useful.

---

### 5. Main problems observed
From the case information, your team should consider problems such as:

- repair requests arriving through multiple channels
- vague or incomplete customer descriptions
- scattered customer details, photos, notes, and preferred times
- unclear job status across request, confirmation, visit, and completion
- difficulty identifying missing information before staff can act
- slow or uncertain answers to customer follow-up questions
- limited visibility into active and pending repair jobs

These are starting points for your analysis. Your team should decide which problems matter most for the first MVP.

---

### 6. What the customer hopes will improve
The business wants a clearer way to receive repair requests, keep important details together, and track job progress. They want staff to answer customer questions more confidently and avoid losing important information in chat history.

The business also wants to explore whether an AI-assisted interaction can reduce repetitive intake work. Ideally, customers could describe their issue naturally, and the system could help convert that conversation into a structured request.

The owner is not expecting a complete AI-powered repair platform. They are looking for an MVP that shows how the business could move from scattered manual coordination toward a more reliable request-tracking workflow.

---

### 7. AI-assisted element
This case should include a small AI-assisted component as part of the MVP.

The AI assistant may help with tasks such as:

- asking customers for missing repair-request details
- summarizing a customer’s repair problem
- classifying the issue into a simple category, such as plumbing, electrical, air-conditioner, furniture, or other
- identifying whether important details are missing, such as address, preferred time, contact number, or photos
- drafting a structured repair request for staff review
- helping staff quickly understand the customer’s issue

The AI assistant should **not** be treated as a perfect expert system. It should not make final commitments, guarantee prices, diagnose dangerous problems, or assign technicians without staff review.

Important actions should remain reviewable by staff.

---

### 8. Your task
Your team must turn this case into your own project proposal and delivery plan.

In your product brief and later project documents, your team must decide and justify:

- **Stakeholders and user roles** — who the key stakeholders and user roles are
- **User needs** — what the main user needs are
- **MVP scope** — what the MVP should include
- **Out of scope** — what should be excluded from the MVP
- **Assumptions** — what assumptions your team is making
- **Constraints** — what constraints affect your project
- **Risks** — what risks may affect delivery or product usefulness
- **AI role** — what the AI assistant should and should not do
- **Human review** — where staff review or correction is required
- **Success criteria** — what success would look like for the first version
- **Usefulness evidence** — what evidence would show that the MVP is useful enough for this case

Do not simply list every possible feature. Your goal is to define a realistic first version that addresses the most important problems within the project time available.

---

### 9. Technical direction to include in your product brief
Your product brief should include an initial technical direction. Briefly state what type of system your team plans to build and what technologies you expect to use, including front end, back end, database or storage, AI/chatbot approach, and demo or hosting approach.

These choices do not need to be final at the start, but they should be realistic for your team and suitable for your proposed MVP. If your team later changes a major technical choice, record the reason in an ADR.

For the AI part, your team should explain at a high level:

- whether the AI assistant is implemented through an API, mock AI response, rule-based prototype, or another approach
- what information the AI is allowed to use
- how AI-generated outputs are stored or reviewed
- how the system handles unclear or incomplete AI responses

The AI component does not need to be commercially perfect. It should be good enough to demonstrate the intended workflow and support the MVP.

---

### 10. Expected project deliverables
Your team will still be expected to produce the course project deliverables, including:

- a product brief or kick-off document
- a backlog with user stories and acceptance criteria
- a project timeline
- high-level architecture and component diagrams
- ADRs
- a design document
- a working MVP
- handover materials as required by the course

For this AI-assisted case, your design document should also explain how the chatbot or AI assistant fits into the overall workflow.

This case brief only gives the starting situation. Your team’s job is to turn it into a clear, justified, and buildable software engineering project.

---

### 11. What a good outcome for this case looks like
A good outcome is not the largest contractor platform or a perfect AI repair assistant. A good outcome is a focused MVP that addresses the real confusion around repair request intake, job details, and job status while using AI in a controlled and useful way.

A strong MVP might show a customer describing a repair problem, the AI assistant helping gather missing information, the system creating a structured request, and staff reviewing or updating the job status.

Your team should aim to show that you understood the business problem, made disciplined scope choices, and built something practical enough to be credible.