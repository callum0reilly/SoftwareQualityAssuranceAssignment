# Automated Testing research sources

# Source 1
## Title: 14 Test Automation Best Practices
## Link: https://medium.com/jagaad/14-test-automation-best-practices-ffd56880f20e
## Key points:
- Start with a strategy: Define clear objectives and goals (Talk to the people who know the application best)
- Group tests based on topics , functionalities or pages of the application. Example: have a set for testing login functionality and another for testing payment features.
- Describe every step and expected results of a test before writing any code.
- Keep test cases maintainable (and easy to understand)
- Use API calls to automate tasks which saves time and avoids flakiness
- Use the object pattern. With this pattern, each page of your application is represented by a separate object in your code (it keeps tests more organized)
- Apply inheritance for shared page elements
- Group shared components
- Beneficial to create helper methods for tasks that are frequently performed across different tests.
- Log details for easier debugging

# Source 2
## Title: Test Automation Best Practices
## Link: https://smartbear.com/learn/automated-testing/best-practices-for-automation/
## Key points:
- Decide what Test cases to automate
- Select the right testing tool
- Have good test data
- Usually, the creation of different tests is based on the QA engineers’ skill levels. It is important to identify the level of experience and skills for each of your team members and divide your automated testing efforts accordingly.

# Source 3
## Title: Best Practices For Writing Automation Test Code
## Link: https://dev.to/sureshayyanna/best-practices-for-writingautomation-test-code-1laa
## Key points:
- Follow OOPs Concepts if possible
- Reduce code duplicity (think before writing new code)
- Focus on making your code scalable and faster without compromising code quality
- Code should be platform and system independent
- Don't have any hardcoded data in source code
- Think for the future
- Use proper documentation
- Create code which can be easily read and modified by others

# Source 4
## Title: Automation Testing Best Practices
## Link: https://www.reddit.com/r/softwaretesting/comments/1bhpiaj/automation_testing_best_practices/
## Key points:
- Prevent flaky tests by stress testing newly created tests
- Don't be afraid to add data attributes to the codebase to make tests more robust
- Automation should be part of dev culture
- Use good names for variables
- Use comments but sparingly. The test name and variables should tell what is happening
- Don't overload the test method. Keep it neat
- Make each test modular

# Source 5
## Title: Best Practices for Test Automation : Checklist
## Link: https://www.browserstack.com/guide/test-automation-standards-and-checklist
## Key points:
- Focus on Documentation: Ensure clear documentation for test cases and frameworks.
- Keep It Simple: Write modular, atomic tests to maintain clarity and ease of updates.
- Regular Maintenance: Continuously refactor tests and remove obsolete or redundant scripts.
- No Code Duplication: Reuse code components to avoid unnecessary repetition and improve maintainability.

## Source 6
- Title:
- Link:
- Key Takeaway:

## Source 7
- Title:
- Link:
- Key Takeaway:
---

## Common things we noticed
- Keep all tests organized for maintainability and organisation
- Keep everything easy to read (logging statements could help or good variable naming standards)
- Think about the future (define goals and strategy first). Don't just think "does it work now?"
- Avoid flaky tests by stress testing new tests to ensure stability
- Use OOP concepts
- Clear documentation of test cases and expected results makes debugging and collaboration easier
- Tasks should be matched to team skill levels

---

## Notes
- Documentation will be very important
- Should avoid flaky tests
- Reuse code and avoid duplication to improve maintainability
- Tests should be designed with future changes in mind
- Good naming conventions help make tests easier to understand
- Automation has to be integrated but must be maintained well
