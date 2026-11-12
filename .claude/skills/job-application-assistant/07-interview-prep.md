---
framework_version: 1.1.0
---

# Interview Preparation Guide

<!-- SETUP: STAR examples are personalized by running /setup based on your actual experience -->

## STAR Format

Structure answers as: **Situation** (context), **Task** (your responsibility), **Action** (what you did), **Result** (outcome).

Keep answers to 1-2 minutes. Be specific. End with what you learned or would do differently.

## Ready-Made STAR Examples

<!-- Populated by /setup from the master CV (documents/cv/master-resume.pdf).
     Every situation, action and tool below comes from the CV's project annexure.
     The percentage figures in the CV are career-wide aggregates, not per-project
     measurements - each Result below says so rather than re-attributing them. -->

### 1. Aventum Reinsurance Portal — micro-frontend architecture (Espire Infolabs)

**S:** Aventum is a global insurance and reinsurance platform covering broking, underwriting and risk advisory. The frontend was a single large application, so every team's release was coupled to every other team's, and the UI had accumulated performance debt.
**T:** As senior developer and technical leader in a five-person team (four developers plus a lead), own the frontend architecture and take the platform to a micro-frontend model without stalling feature delivery.
**A:** Designed and implemented the micro-frontend architecture so each area could be built and deployed independently. Built reusable React and TypeScript components on Redux, added Jest and Storybook coverage for the shared component library, and worked with the business stakeholders to turn underwriting and policy-management requirements into component boundaries. Ran code reviews and set the coding and architectural standards for the team, with delivery through Azure DevOps.
**R:** The platform moved to independently deployable frontends, with a reusable component library behind it. Contributed to the career-wide gains on the CV (roughly 20% faster load times and 10% less maintenance effort across modernization work) - quote those as career aggregates, not as this project's measured result.
**Use for:** "Tell me about a large-scale architecture decision", "How do you modernize a legacy frontend?", "Describe leading a team while still hands-on", "How do you handle stakeholder requirements?"

### 2. Clinical Ink — React frontend with a Python API layer (YASH Technologies)

**S:** Clinical Ink builds electronic Clinical Outcome Assessment and Direct Data Capture tools for clinical trials, where data accuracy and validated workflows decide whether the product is usable at all. The application needed scalable React screens over a Python service layer, with SSO into enterprise healthcare environments.
**T:** As tech lead, deliver the frontend for clinical trial workflows and build out the API layer behind it.
**A:** Built the React and Redux application with TypeScript, using Storybook to develop reusable components in isolation, and GraphQL services for data exchange. Developed the API on Python with FastAPI and PostgreSQL. Built SSO login for enterprise healthcare access. Covered the code with unit and integration tests in Enzyme, Mocha and Karma, with Jenkins handling deployment.
**R:** Delivered an application supporting digital clinical trial workflows and improved data accuracy through the interfaces, on an enterprise healthcare modernization program. This is the strongest single piece of evidence for React-plus-Python full-stack work - lead with it whenever a posting wants both.
**Use for:** "React plus Python full-stack?", "How do you approach regulated or high-stakes domains?", "Tell me about API design", "How do you test a frontend?"

### 3. John Deere Sales Center — three-year enterprise platform build (YASH Technologies)

**S:** John Deere's dealer network needed one platform to create quotations, configure agricultural and construction equipment, monitor orders, and run sales operations, replacing scattered dealer tooling.
**T:** Lead development on the frontend across the program (Sep 2018 - Sep 2021), with four developers in the team.
**A:** Led frontend solution design for the dealer applications, building React and GraphQL screens over a Java Spring Boot backend, with AngularJS in the older parts of the estate. Handled integration between the frontend modules and the Spring Boot services, worked on rendering efficiency and data loading, and set up automated testing with Jest, Enzyme and Puppeteer. Ran sprint planning, estimation, technical reviews and release management with architects, product owners and QA.
**R:** Centralized dealer sales management went live for a global dealer network, with quote generation and equipment configuration handled in one platform. The program ran three years, which is the honest answer to "why does that role look long?" - enterprise dealer rollout, not a stalled project.
**Use for:** "Tell me about leading a long-running program", "How do you work with backend and architects?", "How do you handle release management?", "What testing automation have you introduced?"

### 4. MyAstro — multilingual Smart TV application (Tata Consultancy Services)

**S:** A Malaysian subscription television operator needed a Smart TV application where subscribers could manage subscriptions, activate Disney and Hotstar, and subscribe to channels, across multiple languages and constrained TV hardware.
**T:** As senior developer, build the UI for the set-top box platform and integrate the subscription and content services.
**A:** Developed the interface in React, Redux and TypeScript plus vanilla JavaScript where the TV runtime demanded it. Integrated backend services through Node.js and REST APIs, used AWS Lambda for backend processing, and worked with Jenkins for build and deployment automation. Tuned rendering for TV hardware rather than desktop browsers.
**R:** Delivered a multilingual entertainment application for Malaysian customers, enabling subscription management and content activation. The transferable point is the constraint: performance work on hardware far weaker than a laptop.
**Use for:** "Tell me about performance under constraints", "Have you worked outside web browsers?", "How do you handle multilingual products?", "AWS in a delivery context?"

### 5. ChatChing — large-scale social platform, two years (CDN Software Solutions)

**S:** ChatChing was a multilingual social networking platform needing social feeds, messaging, media sharing, cloud storage, Facebook integration, contact importing, live notifications and real-time communication.
**T:** As senior developer over roughly two years, build the backend and integration layer for a platform at real consumer scale.
**A:** Built on PHP and CodeIgniter with Node.js for the real-time parts. Integrated OpenSocial applications, Amazon S3 for media storage, CloudSponge for contact importing, Facebook APIs, and Memcache for caching. Handled multilingual content and the notification pipeline.
**R:** Delivered a platform serving multilingual consumer social features end to end. It is also the evidence behind "I have worked with Node.js for a long time" - the Node work predates the current React-heavy roles.
**Use for:** "Tell me about third-party integrations", "What's the largest system you've built?", "How do you handle real-time features?", "How did you get into Node.js?"

## Common Tough Questions

### "You don't have production LLM or RAG experience."

> This one is real and should be answered straight, never bluffed. The position: I have not shipped an LLM or RAG system to production. What I have done is adopt AI-assisted engineering seriously - Claude Code, Copilot, prompt-driven workflows - and put it to work in day-to-day delivery, and I have the full-stack depth (React, Node, Python/FastAPI, AWS, REST and microservices) that an AI product team needs on the application side. Given a vector store and a retrieval pipeline, the surrounding engineering - APIs, state, deployment, performance - is work I have already done for fifteen years. If the role is building models, I am not the hire; if it is building the product around them, I am.

### "Where do you see yourself in five years?"

> Leading frontend or full-stack delivery at solution-architecture level, on products where I own the technical direction rather than only the implementation. The pattern across my last four roles is the same: I move from building the UI to defining the architecture, the component standards and the way the team works, then stay hands-on enough to keep the architecture honest. I want that to keep being the job, in a product team rather than an outsourced delivery model.

### "Why are you looking for contract or remote work?"

> Prepare this in your own words. Ground it in what is true: the target is remote-first or contract engagement from India, across India, the UAE, Saudi Arabia, the UK and the US. Do not disparage Espire, and do not overstate the reason - a short, factual answer beats a story.

### "Why did you leave [previous company]?"

> Prepare per company. Be honest and forward-looking, with no negativity about the former employer. The one that needs a real answer is TCS (Mar 2022 - Oct 2023), where the CV shows a single 16-month project between two longer tenures.

### "What's your biggest weakness?"

> Prepare in your own words, with a concrete mitigation. Do not use the "I care too much" answer.

### "Why this company specifically?"

> Customize per company. Must reference: specific projects, company values, market position, or team structure. Never give a generic answer.

### "You're a frontend lead - why should we hire you over someone with more backend depth?"

> Point at the actual evidence rather than the title: Python and FastAPI APIs at Clinical Ink, Node.js services at MyAstro and ChatChing, Java Spring Boot integration at John Deere, AWS in delivery at MyAstro and Espire. The frontend lead framing undersells the profile; the honest positioning is React-plus-Python full-stack with frontend architecture as the differentiator.

### "Fifteen years in, why aren't you at architect or principal level already?"

> Answer with the track record, not defensiveness: UI solution architecture and micro-frontend architecture at Espire, solution design and technical leadership at TCS and YASH, tech lead and team lead since 2015. In services organizations the title ladder lags the work; the scope has been architectural for years. This is precisely why solution architect is a target role rather than a stretch.

## Questions You Should Ask Interviewers

### About the Role
- "What does a typical week look like in this role?"
- "What would success look like in the first 6 months?"
- "What's the biggest challenge the team is facing right now?"

### About the Team
- "How big is the team, and how do you divide work?"
- "What does the development/project lifecycle look like, from idea to production?"
- "How do you onboard new team members?"

### About Tech & Growth
- "What's your current tech stack for [relevant area]?"
- "Is there room to grow into more architectural or strategic decisions?"
- "How does the team stay current with new tools and methods?"

### About Remote and Contract Arrangements
Use these early for overseas roles - they decide whether the engagement works at all.
- "Is the team set up for remote collaboration across time zones, and which hours overlap are expected?"
- "Is this engagement structured as a contract, and through which entity or platform?"
- "How do you handle invoicing, currency and payment terms for contractors outside your country?"
- "What does the equipment and access setup look like for a remote contractor?"

### About Culture (use these to prevent disappointment)
- "How would you describe the team culture?"
- "What does professional development look like here?"
- "Is there flexibility for remote/hybrid work?"
- "What's the balance between development/new projects and maintenance work?"
- "How would you describe the leadership style in this team?"
- "What do people who thrive here have in common?"

## Phone/Video Interview Tips
- Have STAR examples written out (use this file)
- Keep a glass of water nearby
- Smile when speaking (it changes your tone)
- Ask for clarification if a question is vague
- It's OK to take 5 seconds to think before answering
- End with: "Is there anything else you'd like to know about my background?"

## After the Application (Best Practice)

### Follow-Up Etiquette
- **Don't call to "stand out"** or to learn more about the role post-submission - this risks a negative impression
- If the employer specified a timeline, respect it and wait
- If no timeline was given and significant time has passed (2+ weeks), a brief call to ask about status is acceptable
- If you have genuinely new, relevant information to share, a short follow-up is fine

### Thank-You Notes
- When you receive any update (interview invitation, rejection, or status update), send a brief thank-you message
- Express appreciation for their time and the process
- Keep it short (2-3 sentences)

## Roleplay Guidelines
When the user asks for interview practice:
1. Ask which role/company to simulate
2. Start with easy warm-up questions ("Tell me about yourself")
3. Progress to role-specific technical questions
4. Include 1-2 behavioral questions using the competencies from the job posting
5. End with a tough question or curveball
6. After each answer, give brief feedback: what worked, what to sharpen
7. Suggest which STAR example would work best for each question

## Gap Answers to Prepare Per Market

For UAE, Saudi Arabia, UK and US roles reached as a remote contractor from India, expect these and answer them without hedging:
- **Time zone and availability:** state the actual overlap you can commit to, in their local time.
- **Contract structure:** the entity you invoice through, and whether you can work through an employer-of-record platform.
- **Payment terms:** currency, invoicing cycle, and whether you have handled cross-border payments before.
- **Onsite expectation:** say plainly that the engagement is remote. Do not let it surface at offer stage.
