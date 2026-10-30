---
title: Pulse Guard Agile Logbook
permalink: /agile/logbook/
---

# Pulse Guard Agile Logbook

This logbook is arranged chronologically. The April source files were exact duplicates. The August files contained two text versions: the plain-name files were duplicates of each other, and the files marked `CORRECTED` and `_06` were duplicates of each other. These entries use the corrected version, which is more careful about what the records actually confirm.

## April 2026 — discovery and planning

- [Friday, 17 April](entries/2026-04-17.md)
- [Monday, 20 April](entries/2026-04-20.md)
- [Tuesday, 21 April](entries/2026-04-21.md)
- [Wednesday, 22 April](entries/2026-04-22.md)

## August 2026 — deployment and integration

- [Tuesday, 4 August](entries/2026-08-04.md)
- [Wednesday, 5 August](entries/2026-08-05.md)
- [Thursday, 6 August](entries/2026-08-06.md)
- [Friday, 7 August](entries/2026-08-07.md)

## Supporting records

- [Project walkthrough and taskboard inventory](project-walkthrough.md)
- [Entry template](entry-template.md)
- [Trello screenshot evidence](../evidence/README.md)
- [Original logbook documents on Google Drive](https://drive.google.com/drive/folders/15pWhN-yAavtKGWiAop_FtVsFqUDiR16h)

The entries retain the recorded completed work, next steps, and impediments. The source documents do not provide sprint numbers, participant lists, session durations, or measured outcomes for each date, so those have not been inferred. Add those details to future entries when they are available, along with links to the relevant Trello cards or other evidence.

The 4 August entry records that the backend and Go video-processing worker were deployed to AKS and the dashboard was published on Netlify. The Trello export has a deployment backlog card whose description says “completed” while the card remains open, plus a separate deployment card in Sprint 25. Confirm the live board status when presenting these records together.

## Logbook reflection

Reading the entries in date order shows the work moving from backlog cleanup and team roles, into personas and design assets, then into deployment and integration. The blockers changed as the project progressed: early entries mention role confirmation, limited research, tool costs, and protecting environment keys; the August entries focus on service connectivity, cloud configuration, and completing push notifications.

The logbook helped me distinguish work that was completed from work that was only planned. For example, deploying the backend and dashboard was recorded on 4 August, while the following entries still listed integration checks and notification delivery as future work. I learned that a useful logbook needs a specific outcome as well as a next step. Some original entries do not include sprint numbers, attendees, measurements, or detailed test results. In future entries I would record those details, identify the related Trello card or commit, and note whether each follow-up was completed. That would make progress easier to verify and hand over.
