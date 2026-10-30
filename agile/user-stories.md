---
title: User Stories
permalink: /agile/user-stories/
---

# Pulse Guard User Stories

The diagrams below show the citizen and admin journeys recorded on the [Trello board](https://trello.com/b/L3GWnqCP/pulse-guard-project). They are visual summaries of the stories, not substitutes for Trello acceptance criteria.

## Citizen safety and reporting journey

<img src="{{ '/assets/diagrams/citizen-flow.svg' | relative_url }}" alt="Citizen journey: new or returning user, danger-zone check, and crime reporting with video or audio and GPS location" width="100%" />

The detailed reporting story is Trello card **#8**. Cards **#93** and **#94** have no descriptions in the export, so the new-user and returning-user branches need the team's confirmation. Card **#95** says danger-zone checking is finished, while the card remains open; confirm its status and acceptance criteria.

## Admin incident workflow

<img src="{{ '/assets/diagrams/admin-flow.svg' | relative_url }}" alt="Admin journey: sign in, review and filter incidents, read a report, and optionally resolve it; optional statistics, heat-map, and scheduling views" width="100%" />

The board has titles for admin sign-in, incident overview, filtering, reading, resolving, statistics, the heat map, and scheduling. Several of these cards have no descriptions in the export. Add acceptance criteria to the Trello cards so the intended behavior is clear.

## Session security decision flow

<img src="{{ '/assets/diagrams/session-security.svg' | relative_url }}" alt="Session security journey: check the token, redirect invalid sessions to sign-in, issue a new token after successful authentication, and handle logout or timeout" width="100%" />

Trello card **#4** describes idle timeout, manual logout, sign-in after an expired or invalid token, re-authentication, and issuing a new token. It mentions considering a refresh-token strategy but does not define that behavior.

## User stories from Trello

### Reporting a crime in progress — card #8

- As a signed-in user, I want to open the app quickly so that I can report a crime without delay.
- As a user, I want to tap a clearly visible **+** button so that I can start a report in one action.
- As a user, I want the record screen to open with camera and audio ready so that I don't waste time during an emergency.
- As a user, I want to start live video or audio recording so that I can capture evidence of a crime as it happens.
- As a user, I want the app to send my recording and GPS location to the nearest police station or private security company so that help can be dispatched without manually sharing details.
- As a user, I want confirmation that my report was sent so that I know the app received it.

### Admin stories

- **#5:** Admin signs into the dashboard.
- **#13:** Admin views the incident overview.
- **#12:** Admin filters incidents by type or area.
- **#6:** Admin reads a submitted incident.
- **#7:** Admin marks an incident as resolved.
- **#107:** Admin views crime statistics and trends.
- **#110:** Admin reviews the heat map.
- **#115:** Admin creates a schedule and assigns officers to shifts. The card describes this as a Could-priority backlog item.

The new-user and returning-user cards (**#93** and **#94**) have titles but no story descriptions in the export. Confirm their story details with the team.

## Reflection

Write your reflection in your own words. Explain how the user stories informed design and development, what was unclear, and what you learned from mapping the citizen and admin journeys. Include the Trello screenshot as supporting evidence.
