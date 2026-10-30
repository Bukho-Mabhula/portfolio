---
title: User Stories
permalink: /agile/user-stories/
---

# Pulse Guard User Stories

The diagrams below show the citizen and admin journeys recorded on the [Trello board](https://trello.com/b/L3GWnqCP/pulse-guard-project). The board uses checklists to break many stories into tasks; the [user story task breakdown]({{ '/agile/user-story-tasks/' | relative_url }}) transcribes those checklist items.

## Citizen safety and reporting journey

<img src="{{ '/assets/diagrams/citizen-flow.svg' | relative_url }}" alt="Citizen journey: new or returning user, danger-zone check, and crime reporting with video or audio and GPS location" width="100%" />

The [Reporting a crime in progress](https://trello.com/c/nJvVUjMJ), [New user](https://trello.com/c/tjHW9g0N), and [Returning user](https://trello.com/c/59I7BAqK) cards have checklist steps even where the card description is blank. The [Checking danger zones before leaving home](https://trello.com/c/vNznvXtL) card also has a checklist; its description says the feature is finished and mentions waiting for the server, while the parent card remains open in the export.

## Admin incident workflow

<img src="{{ '/assets/diagrams/admin-flow.svg' | relative_url }}" alt="Admin journey: sign in, review and filter incidents, read a report, and optionally resolve it; optional statistics, heat-map, and scheduling views" width="100%" />

The admin cards use checklists to record concrete actions for sign-in, the incident overview, filtering, reading, resolving, statistics, the heat map, and scheduling. Some parent-card descriptions are blank or brief; their checklist steps are transcribed on the task breakdown page.

## Session security decision flow

<img src="{{ '/assets/diagrams/session-security.svg' | relative_url }}" alt="Session security journey: check the token, redirect invalid sessions to sign-in, issue a new token after successful authentication, and handle logout or timeout" width="100%" />

The [Session security and token handling](https://trello.com/c/GcWRnXuO) card describes idle timeout, manual logout, sign-in after an expired or invalid token, re-authentication, and issuing a new token. It mentions considering a refresh-token strategy but does not define that behavior.

## User stories from Trello

### [Reporting a crime in progress](https://trello.com/c/nJvVUjMJ)

- As a signed-in user, I want to open the app quickly so that I can report a crime without delay.
- As a user, I want to tap a clearly visible **+** button so that I can start a report in one action.
- As a user, I want the record screen to open with camera and audio ready so that I don't waste time during an emergency.
- As a user, I want to start live video or audio recording so that I can capture evidence of a crime as it happens.
- As a user, I want the app to send my recording and GPS location to the nearest police station or private security company so that help can be dispatched without manually sharing details.
- As a user, I want confirmation that my report was sent so that I know the app received it.

### Admin stories

- [Admin signs into the dashboard](https://trello.com/c/KPWIbi9v).
- [Admin views the incident overview](https://trello.com/c/TinbDlTB).
- [Admin filters incidents by type or area](https://trello.com/c/hU4uYAvk).
- [Admin reads a submitted incident](https://trello.com/c/kFlbPVQe).
- [Admin marks an incident as resolved](https://trello.com/c/mU8ohGsG).
- [Admin views crime statistics and trends](https://trello.com/c/Wvz94T9B).
- [Admin reviews the heat map](https://trello.com/c/vY4gCKeG).
- [Admin creates a schedule](https://trello.com/c/zixpGjY1). The card describes this as a Could-priority backlog item.

The new-user and returning-user cards have blank descriptions, but their checklists record onboarding and sign-in steps.

## Reflection

Mapping the user stories helped me see how the citizen reporting flow and the admin incident workflow depend on one another. A report needs to be captured and sent with its location before an administrator can review and resolve it. The session-security flow also reminded me that reporting features need a clear sign-in and timeout path.

The Trello cards use a mix of descriptions and checklists. Reading both helped me see that the new-user and returning-user steps are recorded in checklists even though their descriptions are blank. I also noticed status wording that does not align: the danger-zone card says the feature is finished but remains open, and the resolve checklist uses acknowledge language. I learned to distinguish task detail from a card's completion status. The diagrams and task breakdown make the recorded work easier to follow while preserving those board inconsistencies.
