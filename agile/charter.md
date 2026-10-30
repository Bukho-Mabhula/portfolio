---
title: Agile Team Charter
permalink: /agile/charter/
---

# Agile Team Charter

**Charter evidence:** [Open the original team charter in Google Drive](https://drive.google.com/drive/folders/1LwrzyhEGPmq-2difOdZVno3urlodXU4r)

## 1. Team purpose and vision

### Why do we exist as a team?

**Team mission:** To reduce violent crime in high-risk areas of Cape Town by equipping residents with real-time situational awareness. The app surfaces active crime hotspots so users can navigate townships and surrounding areas more safely. It also enables residents to report and stream live incidents to the nearest police station or private security company to improve response times and help communities feel safer.

### Success definition

- **User interest:** At least 30 verified users sign up to test the prototype within the first two weeks of launch. A social media campaign achieves at least 250 shares and 500 impressions across platforms.
- **Prototype usability:** At least 80% of test users complete the crime-reporting flow—record, locate, and transmit—without assistance. Average task completion time is no more than 60 seconds.
- **Community participation:** At least 10–15 participants submit incident reports or flag suspicious activity during the WhatsApp pilot. At least 50% provide structured feedback for the next iteration.

### Product or service

A mobile application that lets citizens record and stream live video of a crime in progress from a smartphone. The app captures the user's real-time GPS location and transmits the stream and location data to the nearest police station and/or private security company. The aim is to reduce police response time, improve evidence quality, and help residents report incidents safely and quickly.

## 2. Team members and roles

| Name | Role | Key responsibilities |
|---|---|---|
| Goitsemang Marokoane | Agile Lead / Designer | Plan, execute, and close projects; create an intuitive and visually appealing application. |
| Bukho Mabhula | Product Owner / Backend Developer | Build and maintain server-side logic, database, and APIs; support security, performance, and scalability; prioritize the backlog and approve completed work as Product Owner. |
| Ratiloe Mbonani | Frontend Developer | Implement the visual elements users see and interact with; translate wireframes into code. |
| Khanya Jakavula | Designer | Create an intuitive and visually appealing application. |

## 3. Ways of working

The team communicates about daily work. The charter records a video meeting every day during lunch, from 13:00 to 13:30, with a reschedule if most members are unavailable.

### 3.1 Agile framework

**Proposed framework: Scrum.** The Trello board is organized into sprints, and the charter already lists sprint planning, daily stand-ups, reviews, and retrospectives. Scrum therefore fits the working structure recorded in the project artifacts. The original Kanban checkbox remains unchecked; this proposal has not been recorded as a team decision. (Schwaber and Sutherland, 2020)

### 3.2 Proposed Scrum cadence

The source charter records daily lunch meetings from 13:00 to 13:30 and reviews during stand-ups. The cadence below is a Scrum-aligned proposal for the team to review; it does not claim that the team has already adopted these timeboxes.

| Ceremony | Frequency | Purpose |
|---|---|---|
| Daily Scrum | Daily (15 minutes) | Inspect progress toward the Sprint Goal and plan the next day's work. |
| Sprint Planning | Start of each sprint | Agree on a Sprint Goal and select work the team expects to complete. |
| Sprint Review | End of each sprint | Inspect the increment with stakeholders and discuss what to do next. |
| Sprint Retrospective | End of each sprint | Inspect how the sprint went and choose an improvement for the next sprint. |

## 4. Working agreements

- Show up prepared and on time.
- Respect timeboxes.
- Give constructive feedback.
- Raise blockers early.
- Commit to continuous improvement.
- Speak up when help is needed.
- Collaborate with one another.

## 5. Communication

- **Primary channels:** Microsoft Teams and email for formal communication and documentation; WhatsApp for quick daily communication and urgent updates.
- **Core hours:** 13:00–13:30.
- **Urgent communication:** Immediate WhatsApp call or scheduled in-person meeting.
- **Non-urgent communication:** Text or email.
- **Remote/hybrid norms:** Video or voice calls and collaboration software such as Figma.

## 6. Decision-making

The source charter leaves all listed decision methods unchecked. Its note says the team works through a problem and chooses the closest suitable solution, but it does not name a formal decision rule.

**Proposed decision rule:** seek team alignment on how to do the work. The Product Owner orders the Product Backlog and clarifies product priorities; the Developers decide how to complete selected work. If the team cannot resolve a product-priority question, the Product Owner makes that product decision after hearing the team's input. This proposal follows Scrum's distinction between product accountability and the Developers' responsibility for their plan. (Schwaber and Sutherland, 2020)

## 7. Definition of Done

Work is considered done when:

- Team members understand the problem and solution.
- Designs are approved by the team, especially developers.
- Documentation is up to date.
- The environment is configured and the project is deployed to environments.
- The backend is coded and works.
- The frontend is coded and intuitive.
- The solution is tested.
- Feedback has been considered and implemented.
- The Product Owner approves the work.

## 8. Core values and behaviours

Respect, transparency, accountability, trust, a learning mindset, patience, honesty, and calmness.

## 9. Risks and constraints

### Known risks

- Users may feel unsafe recording a crime in the moment.
- Police stations and private security companies may not accept or integrate with the initiative because of bureaucracy or lack of formal partnerships.
- There are privacy and legal concerns around recording and sharing video of people without consent.

### Dependencies

- A stable backend API before frontend integration.
- A reliable internet connection for live streaming.
- Access to police-station contacts or location data to route reports.

### Constraints

- The project deadline is fixed.
- There is no budget for paid APIs, cloud hosting, or testing devices.
- The project is limited to free service tiers such as Azure or Supabase.
- There is no dedicated QA tester, and the team is still learning React Native.

## 10. Review and improvement

**Proposed review interval:** at the end of every sprint, during the Sprint Retrospective. This matches the sprint-based board and the charter's existing improvement ceremony. (Schwaber and Sutherland, 2020)

- **Source charter last updated:** 21 April 2026
- **Portfolio page revised:** 30 October 2026

## 11. Team commitment

The charter records these names and agreement signatures:

| Name | Signature / agreement recorded |
|---|---|
| Goitsemang Marokoane | GP Marokoane |
| Bukho Mabhula | BM Mabhula |
| Khanya Jakavula | K Jakavula |
| Ratiloe Mbonani | RL Mbonani |

## Reflection

The charter gave the team a shared reason for building Pulse Guard and connected the planned features to a community safety goal. The role descriptions, meeting routine, working agreements, and Definition of Done also gave us a starting point for coordinating design and development. Reviewing the charter beside the project work showed me that a charter is useful only when the team keeps it current and uses it to make decisions.

The original charter left the framework, decision method, and review interval unselected. I drafted a Scrum-aligned proposal because the board uses sprints and the charter already names sprint ceremonies. The proposal makes responsibilities and review timing clearer, but the team still needs to agree to it before it is treated as the team's adopted working agreement. I would also turn the success measures and Definition of Done into criteria that can be checked during reviews, and revisit the privacy, integration, hosting-cost, and device-testing risks as the product changes.

## Reference

Schwaber, K. and Sutherland, J. (2020) *The Scrum Guide: The Definitive Guide to Scrum: The Rules of the Game*. Available at: [https://scrumguides.org/scrum-guide.html](https://scrumguides.org/scrum-guide.html) (Accessed: 30 October 2026).

