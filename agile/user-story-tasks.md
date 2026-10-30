---
title: User Story Tasks
permalink: /agile/user-story-tasks/
---

# User Story Tasks

The task breakdown below summarizes checklist items from the [Pulse Guard Trello board](https://trello.com/b/L3GWnqCP/pulse-guard-project). It makes the work under the user stories visible without adding tasks that are not in the board export.

## Citizen app

### [New user](https://trello.com/c/tjHW9g0N)

- Open the app and view the onboarding screen.
- Read the privacy policy.
- Select **Register**.
- Enter a name, email, and password.
- Create the account and reach the home screen.

### [Returning user](https://trello.com/c/59I7BAqK)

- Open the app and view the onboarding screen.
- Continue past the policy screen.
- Select **Sign In**.
- Enter an email and password.
- Authenticate and reach the home screen.

### [Checking danger zones before leaving home](https://trello.com/c/vNznvXtL)

- Open the app while signed in.
- Select the **Heatmaps** tab.
- View colour-coded danger zones on the map.
- Zoom into the neighbourhood.
- Avoid high-risk areas and plan a safer route.

### [Reporting a crime in progress](https://trello.com/c/nJvVUjMJ)

- Open the app while signed in.
- Tap the **+** button.
- Open the recording screen with camera and audio ready.
- Start a live video or audio recording.
- Send the recording and GPS location to the nearest police station or private security company.
- Show confirmation that the report was sent.

### [Session security and token handling](https://trello.com/c/GcWRnXuO)

- Expire the JWT token after idle time or logout.
- Redirect the user to sign-in.
- Re-authenticate with the user's credentials.
- Issue a new token and restore access.

## Admin dashboard

### [Admin signs into the dashboard](https://trello.com/c/KPWIbi9v)

- Open the dashboard URL in a browser.
- Enter an email and password.
- Issue a JWT token and begin a secure session.
- Load the dashboard and incident overview.

### [Admin views the incident overview](https://trello.com/c/TinbDlTB)

- Load the dashboard after sign-in.
- List incidents with the most recent first.
- Highlight unread reports with a badge count.
- Scan the list to assess the current situation.
- Filter incidents by date or location.

### [Admin reads a submitted incident](https://trello.com/c/kFlbPVQe)

- Select an incident from the list.
- Open its detail view.
- Read the crime type, description, and timestamp.
- View the reporter's GPS location on a map.
- Play the attached video or audio recording.

### [Admin filters incidents by type or area](https://trello.com/c/hU4uYAvk)

- Start from the dashboard incident list.
- Filter by crime type, neighbourhood, or status.
- Show only matching incidents.
- Review the filtered reports.

### [Admin marks an incident as resolved](https://trello.com/c/mU8ohGsG)

- Review the full incident report.
- Select the acknowledge action.
- Change the incident status from **New** to **Acknowledged**, as written in the checklist.
- Notify the reporter that the report was seen.
- Dispatch a response team to the location.

### [Admin views crime statistics and trends](https://trello.com/c/Wvz94T9B)

- Open the Reports tab.
- Select a date range.
- Load charts showing crime by type and area.
- Identify recurring hotspots to support resource allocation.

### [Admin reviews the heat map](https://trello.com/c/vY4gCKeG)

- Open the dashboard heat map.
- Review crime hotspots.
- Check incident locations on the map.
- Verify crime-type and risk-level filters.
- Validate high-risk areas and recent incident data.
- Test map zoom and navigation.
- Record incorrect or missing data and required improvements.

### [Admin creates a schedule](https://trello.com/c/zixpGjY1)

- Start a new schedule and choose its type.
- Select the date range.
- View available officers and filter by relevant details.
- Check for leave, assignment, and overtime conflicts.
- Assign officers, shifts, duty types, and locations.
- Optionally assign a supervisor or team lead.
- Save a draft or publish the schedule.
- Notify assigned officers.

## Reading the Trello snapshot

The export marks its checklist items complete, but some parent cards remain open and some card descriptions have unresolved wording. For example, the danger-zone description says the feature is finished while its card remains open. The schedule card has an unfilled status prompt in its description, although its checklist lists the workflow. The checklist for resolving an incident uses **acknowledge** language while the card title says **resolved**. These differences are preserved as board-record issues; this task breakdown does not decide the feature status.
