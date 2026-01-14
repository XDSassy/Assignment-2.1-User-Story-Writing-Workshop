# Sprint 1 Planning Session
**Date:** 14 January 2026  
**Sprint Goal:** Enable employees to successfully book and manage conference rooms with capacity and equipment considerations, while allowing cancellations to keep room availability accurate.

## Attendees
- **Product Owner:** Mapps  
- **Scrum Master:** Self  
- **Development Team:**  
  - Romeo (Frontend)  
  - Bob (Backend)  
  - Evan (Full-stack / Testing)

## Velocity Target
13 story points (based on team capacity and story estimates)

## Selected User Stories

| Story # | Title | Story Points |
|---------|-------|--------------|
| 1       | Basic room booking | 5 |
| 3       | Room capacity filtering | 3 |
| 4       | Booking cancellation | 2 |
| 5       | Room equipment requirements | 3 |

## Dependencies
- Story #3 (capacity filtering) depends on Story #1 (basic booking) being implemented first.  
- Story #4 (cancellation) depends on Story #1 (booking) for cancellation logic.  
- Story #5 (equipment requirements) depends on Story #1 (booking) to link equipment selection to available rooms.

## Risks

| Risk | Probability | Impact | Mitigation |
|------|------------|--------|-----------|
| Delays in backend availability logic | Medium | High | Prioritize API development first, allocate Bob to support Story #1 and Story #3 |
| UI integration conflicts | Medium | Medium | Daily integration checks, Romeo and Evan coordinate on frontend components |
| Insufficient test coverage causing rework | Low | Medium | Evan to focus on automated testing for each story as implemented |

## Standup Cadence
**Time:** 10:00 AM daily  
**Format:** Yesterday / Today / Blockers