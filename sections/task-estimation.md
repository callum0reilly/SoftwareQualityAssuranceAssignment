# Task Estimation in Scrum

## Why This Matters

- Estimation is how a Scrum team figures out what fits in a sprint and when something might actually ship. If you mess this up, people either burn out chasing unrealistic targets or sit idle because nobody committed to enough work.
- When you've got 20 engineers and no room for wasted sprints, getting this wrong costs money.

## What Good Estimation Looks Like

- **Why not hours? Because your hour isn't the same as mine**

  Ask two developers how long a task will take and you'll get two different answers. That's not a problem with the developers. They just bring different skills and experience. But ask both of them whether task A is roughly twice as hard as task B, and they'll probably agree. That agreement on relative effort is what story points capture. Jeff Sutherland, co-author of the Scrum Guide, called them "faster, better and cheaper than hours" because they avoid time-based bias entirely.

- **Anchor your scale with real stories**

  Find a story everyone thinks is small and call it a 2. Find one that feels about twice the effort and call it a 5. Now you've got anchors. Every future estimate gets compared against these two, which stops the scale from drifting as sprints go by and gives new team members something concrete to point at.

- **Three things push an estimate up**

  Amount of work, complexity and risk. A task might be straightforward but large. Another might be small but involve crossing a tricky integration boundary. A third might depend on an external API nobody has touched before. When any of these are present, the number should go up.

- **Planning poker works because of the arguments**

  Everyone picks a number independently, then reveals at the same time. If the estimates match, move on. When they don't (say one person votes 2 and another votes 8), that gap is the whole point. The discussion usually finds unclear requirements or assumptions only one person was making. Five to ten minutes of that conversation is worth more than an hour of solo guessing.

- **Velocity needs time to mean anything**

  Velocity (points shipped per sprint) only tells you something useful after several iterations. Promising delivery dates off two sprints of data is guesswork dressed up as planning. Wait until you have a stable average across at least five sprints, then express forecasts as a range (e.g. 30 to 50 points). Never a single number.

- **Why the numbers look weird**

  Teams use scales like 1, 2, 3, 5, 8, 13, 20 because humans can't reliably tell the difference between, say, 19 and 21. But they can tell 13 from 20. Psychologists call this Weber's Law. The Fibonacci sequence bakes this in by keeping gaps just wide enough to be meaningful. A story estimated at 21 looks worryingly precise to stakeholders. Calling it 20 avoids that false impression.

- **Check your past estimates, not just your future ones**

  Pull up the last batch of stories estimated as 5 points. Did they all feel like similar effort? If not, figure out why. This is how teams build a shared sense of what each number actually means. Most teams skip this step entirely. The ones that don't get noticeably better at forecasting within a few iterations.

## Common Estimation Traps

- **Converting story points back to hours**

  This defeats the entire purpose. The moment a manager says "so an 8 is about two days, right?", the team is back to time-based thinking and all the bias that comes with it.

- **Letting one or two people estimate for the team**

  Estimation works because it forces the whole team to think about the work. When only the tech lead estimates, everyone else loses context and commitment to what was planned.

- **Obsessing over the exact number**

  Estimation is a rough band, not a contract. Two days of sprint planning for a two week sprint? Something has gone wrong. If the team has stable velocity, the exact number on any individual story matters far less than the overall average across many stories.

- **Skipping the split conversation**

  If the team can't agree on a story's size, that almost always means it's too big or too vague. Wide disagreement is a signal to split the story, run a spike or go back to the product owner for clearer acceptance criteria.

- **Never looking back at what you got wrong**

  Teams that skip retros keep making the same mistakes. A quick look at which stories were over or underestimated teaches you more than any estimation framework ever will.

- **Treating story points as the only option**

  They're popular, but some mature teams move to flow metrics (cycle time, throughput) or drop estimation entirely. If your method isn't helping the team plan better, try something else.

## Key Takeaways

- Estimation is a team alignment tool, not a way to make precise schedules.
- Story points work because they measure relative effort and remove individual skill bias.
- Disagreements during planning poker are features, not bugs. They surface hidden risk.
- Velocity only becomes useful after several sprints of data. Don't promise off early numbers.
- Look back at what you got wrong. That's where the real improvement comes from.

## Diagram

<!-- TODO: Add mermaid diagram showing: Story -> Planning Poker -> Discuss Divergence -> Re-estimate -> Consensus -> Track Velocity -->

## Further Reading

- Scrum.org: *Why do we use Story Points for Estimating?*
    - Explains why story points beat hours and why divergent votes are a useful signal.
    - [https://www.scrum.org/resources/blog/why-do-we-use-story-points-estimating](https://www.scrum.org/resources/blog/why-do-we-use-story-points-estimating)

- Mountain Goat Software: *Agile Estimating: How Teams Estimate with Story Points*
    - Covers baseline stories, planning poker, the three factors of effort and the modified Fibonacci scale.
    - [https://www.mountaingoatsoftware.com/agile/agile-estimation-estimating-with-story-points](https://www.mountaingoatsoftware.com/agile/agile-estimation-estimating-with-story-points)

- Scrum Alliance: *A Cure for Task Estimation Obsession*
    - Makes the case for dropping task-level estimation once a team has stable velocity.
    - [https://resources.scrumalliance.org/Article/cure-task-estimation-obsession](https://resources.scrumalliance.org/Article/cure-task-estimation-obsession)

- Agile Alliance: *Improving Estimation with Story Points*
    - Experience report from a first-time agile team showing how calibration improved over time.
    - [https://agilealliance.org/resources/experience-reports/improving-estimation-story-points/](https://agilealliance.org/resources/experience-reports/improving-estimation-story-points/)

- Atlassian: *Agile Estimation*
    - Practical guide to story point estimation, splitting stories and using planning poker.
    - [https://www.atlassian.com/agile/project-management/estimation](https://www.atlassian.com/agile/project-management/estimation)

- Scrum.org: *Exploring Estimation Approaches*
    - Compares story points, hourly estimates, flow metrics and no-estimation approaches.
    - [https://www.scrum.org/resources/blog/exploring-estimation-approaches-what-right-fit-scrum-teams](https://www.scrum.org/resources/blog/exploring-estimation-approaches-what-right-fit-scrum-teams)

- Beyond Lean Agile: *Metrics*
    - Covers velocity, cycle time and how metrics should guide useful discussion rather than become a distraction.
    - [https://beyondleanagile.com/tag/metrics/](https://beyondleanagile.com/tag/metrics/)
