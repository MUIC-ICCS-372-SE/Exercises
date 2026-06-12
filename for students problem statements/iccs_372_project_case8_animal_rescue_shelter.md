# ICCS 372 — Term Project Case Brief

## Case 8 - PawMatch Bangkok AI-Assisted Animal Rescue Foster and Adoption Tracker

---

### 1. What this case is
Your team is acting as a small software engineering team engaged by a volunteer-run animal rescue group in Bangkok. The group is not asking for a national animal shelter management system. They want a practical first version of a digital system that would make animal profiles, foster status, and adoption inquiries easier to manage.

The group is also interested in using a simple AI-assisted chatbot to answer basic questions about animals, collect foster or adoption inquiry details, and summarize inquiries for volunteers.

This document gives you the business context, the customer’s situation, and the problems they are experiencing. It is **not** a finished product brief, a completed backlog, or a final system design. Your team must still analyze the case, define the MVP, decide what is included and excluded, and justify how your solution should work.

---

### 2. Business context
PawMatch Bangkok is a small volunteer group that helps rescue cats and dogs, coordinate temporary foster homes, and respond to adoption inquiries. The group uses social media posts, chat groups, spreadsheets, and personal messages to share information about animals and coordinate next steps.

The volunteers care deeply about the animals, but the process is difficult to manage. One volunteer may know an animal’s medical status, another may know who is fostering it, and another may be handling adoption inquiries. Information changes often, especially when animals move between foster homes, receive treatment, or become ready for adoption.

The group is not asking for a complex veterinary records system, donation platform, or public adoption marketplace. They want a first step toward clearer coordination among volunteers and better handling of foster and adoption inquiries.

---

### 3. Current situation
At the moment, animal information is scattered across posts, chat messages, photo albums, and spreadsheets. A dog may be listed as needing a foster home, but someone may already be discussing a temporary placement in chat. A cat may have several interested adopters, but the group may not have a clear shared view of who has been contacted, screened, or rejected.

Volunteers also need to keep track of practical details: animal name, species, age estimate, health notes, vaccination status if known, current foster location, adoption readiness, and inquiry status. Not all of this needs to be perfect, but losing track of important information can cause delays or confusion.

People who want to help often ask similar questions: whether an animal is still available, whether fostering is possible, what care is needed, and who to contact. Volunteers may need to answer these repeatedly while also coordinating urgent cases.

The group can continue operating manually, but the process is emotionally and logistically tiring.

---

### 4. Notes from conversations with the customer
One volunteer said that the hardest part is not finding people who care, but keeping the information organized enough to act responsibly. Someone may offer to foster, another person may ask to adopt, and another volunteer may still be waiting for health updates from a clinic.

Another volunteer mentioned common questions: “Is this dog still available?” “Has this cat been vaccinated?” “Who is currently fostering this animal?” “Did anyone reply to this adopter?” “Which animals urgently need foster homes?” These questions are important, but the answers are often spread across several people.

The group is interested in whether an AI-assisted chatbot could help answer basic questions using existing animal profile information and collect inquiry details from people who want to foster or adopt. They would also like volunteers to receive cleaner summaries instead of reading through long message threads.

The group does **not** expect the AI to approve adopters, judge whether someone is suitable, provide veterinary advice, or make final decisions. Volunteers must remain responsible for important decisions.

---

### 5. Main problems observed
From the case information, your team should consider problems such as:

- animal information scattered across many communication channels
- repeated basic questions from interested fosterers or adopters
- unclear foster status or adoption readiness
- adoption inquiries being difficult to track consistently
- incomplete or outdated health and care notes
- volunteers lacking one shared view of urgent cases
- difficulty knowing which follow-ups have already happened

These are starting points for your analysis. Your team should decide which problems matter most for the first MVP.

---

### 6. What the customer hopes will improve
The group wants a clearer way to organize animal information, track foster or adoption status, and manage inquiries from interested people. They want volunteers to spend less time searching through messages and more time helping animals.

The group also wants to explore whether an AI-assisted chatbot can support first-contact conversations by answering basic questions and collecting inquiry details before a volunteer reviews them.

The group is not expecting a full rescue management platform. They are looking for an MVP that shows how volunteer coordination could become more reliable without overwhelming the team.

---

### 7. AI-assisted element
This case should include a small AI-assisted component as part of the MVP.

The AI assistant may help with tasks such as:

- answering basic questions using provided animal profile information
- helping interested people find relevant animal profiles based on simple preferences
- asking for missing foster or adoption inquiry details
- summarizing foster or adoption inquiries for volunteers
- identifying whether an inquiry needs follow-up
- helping volunteers understand recent inquiry activity

The AI assistant should **not** be treated as a final decision-maker. It should not approve adopters, reject applicants, provide veterinary advice, or make sensitive judgments about people or animals.

Important actions should remain reviewable by volunteers.

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
- **Human review** — where volunteer review or correction is required
- **Success criteria** — what success would look like for the first version
- **Usefulness evidence** — what evidence would show that the MVP is useful enough for this case

Do not simply list every possible feature. Your goal is to define a realistic first version that addresses the most important problems within the project time available.

---

### 9. Technical direction to include in your product brief
Your product brief should include an initial technical direction. Briefly state what type of system your team plans to build and what technologies you expect to use, including front end, back end, database or storage, AI/chatbot approach, and demo or hosting approach.

These choices do not need to be final at the start, but they should be realistic for your team and suitable for your proposed MVP. If your team later changes a major technical choice, record the reason in an ADR.

For the AI part, your team should explain at a high level:

- whether the AI assistant is implemented through an API, mock AI response, rule-based prototype, or another approach
- what animal profile or inquiry data the AI is allowed to use
- how AI-generated summaries or suggestions are stored
- how volunteers can review or correct AI output

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

For this AI-assisted case, your design document should also explain how the chatbot or AI assistant fits into the overall foster/adoption inquiry workflow.

This case brief only gives the starting situation. Your team’s job is to turn it into a clear, justified, and buildable software engineering project.

---

### 11. What a good outcome for this case looks like
A good outcome is not the largest animal shelter system or a perfect AI adoption matcher. A good outcome is a focused MVP that addresses the real confusion around animal profiles, foster status, adoption inquiries, and volunteer coordination while using AI in a controlled and useful way.

A strong MVP might show an interested person asking about animals, the AI assistant answering basic questions from available profiles, the system collecting inquiry details, and volunteers reviewing or updating the inquiry status.

Your team should aim to show that you understood the problem, made disciplined scope choices, and built something practical enough to be credible.