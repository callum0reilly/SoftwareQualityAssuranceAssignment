# Code Reviews research sources

## Source 1

- Title: 5 code review best practices
- Link: <https://www.atlassian.com/blog/add-ons/code-review-best-practices>
- Key takeaway:
    - Use a checklist to make reviews more structured and consistent.
    - Reviewers should explain why a change is needed, not just say what is wrong.
    - Reviews should stay small because reviewing too much code at once makes it harder to find problems.
    - Code review should help developers learn and improve, not make them feel judged.

## Source 2

- Title: Best Practices for Peer Code Review
- Link: <https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/>
- Key takeaway:
    - Reviews work best when they are small, slow enough to be careful, and not too long in one sitting.
    - Teams should set goals and track simple metrics to see if reviews are actually useful, such as:
        - Inspection rate: how quickly code is reviewed
        - Defect rate: how often defects are found
        - Defect density: how many defects are found in a given amount of code
    - Authors should give context before review, and teams should have a clear process for fixing issues found.
    - A positive and non-threatening review culture is important for learning, teamwork, and better code quality.

## Source 3

- Title: How to review code effectively: A GitHub staff engineer's philosophy
- Link: <https://github.blog/developer-skills/github/how-to-review-code-effectively-a-github-staff-engineers-philosophy/>
- Key takeaway:
    - Good code reviews are clear, specific, and help move the code into a better state.
    - Review comments should explain the issue clearly and say whether something is a blocker or just a suggestion.
    - Asking questions is a useful review habit because it checks assumptions and helps people learn.
    - Small pull requests, quick feedback, and respectful communication make reviews more effective.

## Source 4

- Title: Code Review: Culture, Flow, and Practices That Drive Team Performance
- Link: <https://mergify.com/blog/code-review-culture-flow-and-practices-that-drive-team-performance>
- Key takeaway:
    - Code review is not just for catching mistakes, it also helps with knowledge sharing and team ownership of the code.
    - Pull requests should be kept small and clearly explained so they are easier to review.
    - Reviewers should focus on whether the code makes the codebase better, not whether it is perfect.
    - The human side matters a lot: respectful tone, clear communication, and positive comments help build trust and teamwork.

## Source 5

- Title: How to do a code review / The Standard of Code Review
- Link: <https://google.github.io/eng-practices/review/reviewer/>
- Key takeaway:
    - The main goal of code review is to improve the overall code health over time.
    - Reviewers should approve code when it improves the codebase and has no serious issues, even if small improvements could still be made later.
    - Reviews should be done quickly enough that they do not block the team for too long.
    - Comments should be kind, clear, and explain the reason behind the feedback.

## Source 6
- Title: Better Code Reviews in 6 SIMPLE STEPS
- Link: https://www.youtube.com/watch?v=d9_fweNDjKw
- Key Takeaway:
    - Keep reviews small (large pull requests are hard to review properly). Smaller changes lead to faster feedback
    - Think easier to understand, easier to spot problems
    - Review regularly don't let them pile up (Maybe treat them like a daily task)
    - Have clear goals for the review (Know what you're checking for such as readability, design or performance)
    - Focus on important things (Don't waste time on minor issues such as spacing or formatting mainly look at logic errors, bad design and maintainability)
    - Be constructive not critical. Don't attack the person, only the code. Explain why something should change. Suggest improvements don't just say "this is wrong".
    - Use reviews as a learning tool. Reviews help junior developers improve. Sharing knowledge across the team is one of the biggest benefits.
  
## Source 7
- Title: Eliminate These 7 Bad Habits for More Effective Peer Code Reviews
- Link: https://www.parasoft.com/blog/avoid-ineffective-code-reviews-by-eliminating-these-7-bad-habits/
- Key Takeaway:
    - Underutilizing tools in peer code reviews. You shouldn't be reviewing or looking for anything that can be done by static analysis. For example style issues like curly placement. If a tool can find it for you, let it. Free yourself to look deeper into the algorithm, security, and performance characteristics of the code. Do clever work not tedious work.
    - Reviewing unfinished code. Don't use the logic of "I’m not done yet, but we’ve already scheduled a review so let’s at least look at what we have." Make sure the code author is finished, and if they’re not ready yet, postpone until they are.
    - Overextending peer code review sessions. Lengthy code review sessions can be counterproductive. It’s important to set reasonable limits on the scope and duration of each review to maintain focus and productivity. Long, exhaustive reviews can lead to fatigue, reduced attention to detail, and a slower development process. If reviews take more than an hour, you’re probably trying to review too much at once.
    - Personalising peer code review feedback. A peer review is about the code, not the people. Make sure you’re talking about the code and not the developer. A statement like, "This code won’t scale as well as we need" is less likely to offend than, "You wrote this badly."
    - Procrastinating peer code reviews
    - Most software quality practices should be treated like exercise. If you try binge them at the last moment, they won't be effective. 
    - Inconsistent follow up in peer code review processes. How a review is followed up can greatly affect the value of the review. If you find items during a review and don’t check that they’re fixed, you’re probably wasting your time. Make sure everyone knows what is expected of them and follow up to make sure fixes are being made. 
    - If nothing is found in the review, be critical. While this can happen from time to time, it should certainly make you suspicious. It may be a sign of quid-pro-quo reviews occurring between developers, or a sign that your development doesn’t understand the value behind code reviews or how to do them properly. 
    - Inconsistent criteria for peer code reviews. If each reviewer isn’t looking for the same things, you will have no idea if your reviews are effective. Get everyone on the same page. It will improve your quality, provide the consistency necessary for assessment and improvement, and protect you if something goes wrong.
  
---

## Common things we noticed

- Good code reviews should be clear, respectful and helpful because review culture has a big impact on teamwork and confidence.
- Smaller reviews are more effective than large ones.
- Code reviews are not only for finding bugs, they also help learning and teamwork.

---

## Notes

- Reviews should explain the reason behind feedback.
- Code review should be treated as a learning process, not personal criticism.
- Teams need a balance between speed and thoroughness.
- Keeping pull requests small can make reviews easier and faster.
- Feedback should always be clear, respectful, and constructive, as this improves team collaboration and avoids tension.
- Reviews should include proper follow-up, ensuring that identified issues are actually fixed.
