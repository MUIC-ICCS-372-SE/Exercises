# ICCS 372 — Term Project Case Brief

## Case 7 - LearnNest Bangkok AI-Assisted Tutoring Inquiry and Enrollment Coordination

---

### 1. What this case is
Your team is acting as a small software engineering team engaged by a tutoring and skills-learning center in Bangkok. The center is not asking for a full learning management system. They want a practical first version of a digital system that would make course inquiries, trial-class requests, and class enrollment easier to coordinate.

The center is also interested in using a simple AI-assisted chatbot to answer routine course questions, collect student inquiry details, and help staff understand which inquiries need follow-up.

This document gives you the business context, the customer’s situation, and the problems they are experiencing. It is **not** a finished product brief, a completed backlog, or a final system design. Your team must still analyze the case, define the MVP, decide what is included and excluded, and justify how your solution should work.

---

### 2. Business context
LearnNest Bangkok offers small-group tutoring and short skills courses for high-school and university students. Courses may include English communication, coding basics, mathematics support, exam preparation, and study-skills workshops. Students or parents usually ask about course schedules, levels, prices, trial classes, and available seats through chat, phone calls, or social media.

The center is small and still relies heavily on manual coordination. Staff answer questions, check class availability, collect student information, and follow up later if a student wants to join. As the number of inquiries increases, it becomes harder to know which students are only asking, which students want a trial, and which students are ready to enroll.

The owner is not asking for a full online classroom, video platform, automated payment system, or complex student management platform. They want a first step toward a clearer inquiry and enrollment workflow.

---

### 3. Current situation
At the moment, a student may ask about a course through chat, a parent may call later, and another staff member may record the same student’s details in a spreadsheet. Some inquiries are serious, while others are only asking for information. Some students need basic guidance before choosing a class. Others ask for a trial class but do not confirm immediately.

The staff can usually manage this manually, but the process is uneven. A class may appear to have seats available, but several trial requests may already be pending. A student may be interested in a course, but no one remembers to follow up. Staff may also struggle to see which classes are full, nearly full, or still open without checking multiple records.

Many questions are repeated: course level, schedule, price, trial availability, next start date, and whether a class is suitable. Answering these repeatedly takes time, especially during busy periods.

---

### 4. Notes from conversations with the customer
The owner said that the center does not lose students because of teaching quality as much as because the inquiry process is messy. Interested students sometimes disappear because no one follows up at the right time, or because staff are unsure which class to recommend.

A staff member mentioned common questions: “Which level should I join?” “Is there still a seat?” “Can I try one class first?” “When does the next group start?” “Did I already register?” These questions are normal, but they are hard to manage when inquiry notes, class lists, and follow-up reminders are scattered.

The owner is interested in whether an AI-assisted chatbot could answer simple course-related questions and collect inquiry information before staff step in. For example, the chatbot could help identify whether the person is just asking, wants a trial class, or is ready to enroll.

The owner does **not** expect the AI to fully replace staff, guarantee class placement, handle payment, or act as a complete admissions system. A simple assistant that supports inquiry handling would already be helpful.

---

### 5. Main problems observed
From the case information, your team should consider problems such as:

- course inquiries arriving through multiple channels
- repeated routine questions taking staff time
- unclear distinction between inquiry, trial request, and confirmed enrollment
- incomplete student or parent contact details
- difficulty tracking available seats or class status
- missed follow-ups with interested students
- limited visibility into which courses have strong demand

These are starting points for your analysis. Your team should decide which problems matter most for the first MVP.

---

### 6. What the customer hopes will improve
The center wants a clearer process for presenting course information, recording student interest, and tracking enrollment progress. They want staff to know which inquiries need follow-up, which classes still have space, and which students have moved from interest to trial or confirmed enrollment.

The center also wants to explore whether a chatbot can handle common first-contact questions and create cleaner inquiry records for staff.

The owner is not expecting a complete education platform. They are looking for an MVP that shows how the center could improve coordination before and during enrollment.

---

### 7. AI-assisted element
This case should include a small AI-assisted component as part of the MVP.

The AI assistant may help with tasks such as:

- answering basic course-related questions using provided course information
- asking students or parents for missing inquiry details
- summarizing a student’s inquiry for staff
- classifying an inquiry as general question, trial request, enrollment interest, or follow-up needed
- suggesting possible next steps for staff review
- helping staff see which inquiries need attention

The AI assistant should **not** be treated as a perfect academic advisor. It should not guarantee placement, make final enrollment decisions, handle payment, or provide sensitive academic counseling.

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
- what course information or inquiry data the AI is allowed to use
- how AI-generated summaries or classifications are stored
- how staff can review or correct AI output

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

For this AI-assisted case, your design document should also explain how the chatbot or AI assistant fits into the overall inquiry and enrollment workflow.

This case brief only gives the starting situation. Your team’s job is to turn it into a clear, justified, and buildable software engineering project.

---

### 11. What a good outcome for this case looks like
A good outcome is not the largest learning management system or a perfect AI academic advisor. A good outcome is a focused MVP that addresses the real confusion around course inquiries, trial requests, seat visibility, and enrollment status while using AI in a controlled and useful way.

A strong MVP might show a student or parent asking course questions, the AI assistant collecting inquiry details, the system creating an inquiry record, and staff reviewing or updating the inquiry status.

Your team should aim to show that you understood the business problem, made disciplined scope choices, and built something practical enough to be credible.