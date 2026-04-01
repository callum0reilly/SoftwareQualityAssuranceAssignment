# Task Estimation research sources

## Source 1
- Title: Why do we use Story Points for Estimating?
- Link: https://www.scrum.org/resources/blog/why-do-we-use-story-points-estimating
- Key takeaway:
    - Story points are relative effort units decided by the team, not hours or calendar time, which avoids the problem of different developers having different interpretations of what an "hours work" means.
    - Teams should estimate collaboratively so that divergent votes trigger discussion and surface missing details or hidden complexity, like one team member voting 5 points vs another voting 13.
    - The main value of story points is in tracking velocity over several sprints, once you have historical data, you can give reasonable delivery ranges rather than precise dates.
    - Mapping story points back to hours defeats the purpose because it reintroduces the same estimation bias you were trying to avoid.

## Source 2
- Title: Agile Estimating: How Teams Estimate with Story Points
- Link: https://www.mountaingoatsoftware.com/agile/agile-estimation-estimating-with-story-points
- Key takeaway:
    - Agree on one or two "anchor stories" upfront so that all future items are estimated relative to these, reducing drift and improving consistency across sprints.
    - Estimation should be time boxed, the goal is a rough band that reflects the team's understanding and risk, not agreement on an exact number.
    - Look at at least 5–8 sprints of velocity data and treat forecasts as ranges (30–50 points) rather than a single precise figure.
    - The goal of estimation is reducing risk and aligning understanding, not producing a perfect schedule.

## Source 3
- Title: A Cure for Task Estimation Obsession
- Link: https://resources.scrumalliance.org/Article/cure-task-estimation-obsession
- Key takeaway:
    - Many teams over invest in fine grained hour estimates, once you have stable velocity, you can often skip detailed task breakdowns and plan at the story point level.
    - Measuring delivery outcomes (e.g how many stories shipped, how many missed "done") is more useful than obsessing over whether a story is 2 vs 3 points.
    - Teams that transitioned from long task lists to story level estimates plus tight sprints saw improvements in both quality and predictability.
    - Treat estimation as a safety check: if the team cannot agree on size, or the story feels too big, that is a signal to split, spike, or clarify requirements before proceeding.

## Source 4
- Title: Improving Estimation with Story Points (experience report)
- Link: https://agilealliance.org/resources/experience-reports/improving-estimation-story-points/
- Key takeaway:
    - An experience report from a first time agile team that started by estimating in "ideal engineering hours" and then mapped to story points, showing how explicit calibration improved forecasts over time.
    - By tracking what actually shipped versus what was estimated and reviewing mismatches in retrospectives, estimation accuracy improved from roughly 50% to over 70% within a few iterations.
    - The team gradually stopped translating points back to hours so that points stayed relative and velocity based, rather than reverting to time based thinking.
    - Run a retro on estimation every 2–3 sprints (e.g "which stories were over or under estimated?") to build a shared team mental model of size.

## Source 5
- Title: Agile Estimation
- Link: https://www.atlassian.com/agile/project-management/estimation
- Key takeaway:
    - No single story should exceed roughly 16 hours of work, if it does, the team should split it before estimating, which keeps sprint planning manageable and forecasts more reliable.
    - Teams that track both story point velocity and time find that applying a granularity threshold plus story points yields better long term predictability than pure hour booking.
    - Planning poker is a team safety thing: when estimates differ widely, use those disagreements to surface technical risks, edge cases, or unclear acceptance criteria rather than rushing to a consensus number.
    - Treat discrepancies in votes (e.g 1, 5, 13) as a signal, not a problem. Take 5–10 minutes to sketch design options or run a spike before re-estimating.

---

## Common things we noticed
- Estimation is most valuable as a team alignment and risk reduction tool, not as a way to produce precise schedules.
- Tracking velocity over multiple sprints is more reliable than trying to estimate individual stories perfectly.
- When estimates diverge widely, that disagreement is a useful signal it usually means the story needs more discussion, splitting, or a spike.
- Retrospectives on estimation accuracy are an underused way to improve team calibration over time.

---

## Notes
- Story points should stay relative, mapping them back to hours defeats their purpose.
- Teams new to agile often go through a phase of tracking both hours and points before trusting velocity alone.
- Sprint scope control matters as much as estimation accuracy.
- Bad practices to cover in the handbook: mapping story points directly to hours, skipping estimation retrospectives, letting individual developers estimate in isolation, and treating planning poker consensus as a target rather than a discussion prompt.
