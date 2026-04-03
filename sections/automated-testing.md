# Automated Testing

## Why This Matters

- Automated testing helps teams catch bugs quickly without having to manually check everything after each change. It gives developers confidence to make updates without breaking existing features. This allows teams to work faster while keeping the system stable.

## What Good Automated Testing Looks Like

- Start with a clear testing strategy
    - Define what should be automated and why, rather than automating everything blindly. Focus on high-value and frequently used features.
- Keep tests small, modular, and focused
    - Each test should cover one behaviour only. This makes failures easier to understand and fix.
- Organise tests clearly
    - Group tests by feature or functionality (e.g. login, payments). This improves navigation and maintainability.
- Write readable and maintainable test code
    - Use clear naming, simple structure, and avoid complexity so other developers can understand tests easily.
- Avoid code duplication
    - Reuse helper methods and shared components to keep the test suite clean and scalable.
- Design tests for the future
    - Avoid hardcoded values and write flexible tests that can handle changes in the system.
- Prevent flaky tests
    - Ensure tests are stable by stress testing and avoiding unreliable dependencies (e.g. timing issues or unstable UI elements).
- Use API-level testing where possible
    - API tests are faster and more reliable than UI tests, reducing overall test execution time.
- Document tests and expected outcomes clearly
    - Good documentation helps debugging and allows new team members to understand the system faster.
- Align testing with team skills
    - Assign testing tasks based on experience levels to maintain quality and efficiency.

## Common Testing Traps

- Trying to automate everything
    - Not all tests should be automated. Low-value or rarely used features can waste time and effort.
- Overly complex tests
    - Large, complicated tests are hard to debug and maintain.
- Hardcoded data in tests
    - This makes tests brittle and prone to breaking when data changes.
- Poor organisation of test files
    - Leads to confusion, duplication, and difficulty maintaining the test suite.
- Lack of documentation
    - Makes it harder for new developers to understand what tests are doing or why they exist.
- Ignoring test maintenance
    - Outdated or broken tests pile up and slow down development.
- Duplicated test logic
    - Increases maintenance effort and creates inconsistencies.

## Key Takeaways

- Automated testing should be strategic, not excessive
- Tests must be stable, readable, and maintainable
- Avoid flaky tests
- Focus on long-term scalability, not just short-term success
- Good testing is part of team culture, not just a QA task

## Further Reading

- 14 Test Automation Best Practices
    - [https://medium.com/jagaad/14-test-automation-best-practices-ffd56880f20e](https://medium.com/jagaad/14-test-automation-best-practices-ffd56880f20e)
- Test Automation Best Practices
    - [https://smartbear.com/learn/automated-testing/best-practices-for-automation/](https://smartbear.com/learn/automated-testing/best-practices-for-automation/)
- Best Practices For Writing Automation Test Code
    - [https://dev.to/sureshayyanna/best-practices-for-writingautomation-test-code-1laa](https://dev.to/sureshayyanna/best-practices-for-writingautomation-test-code-1laa)
- Automation Testing Best Practices
    - [https://www.reddit.com/r/softwaretesting/comments/1bhpiaj/automation_testing_best_practices/](https://www.reddit.com/r/softwaretesting/comments/1bhpiaj/automation_testing_best_practices/)
- Best Practices for Test Automation: Checklist
    - [https://www.browserstack.com/guide/test-automation-standards-and-checklist](https://www.browserstack.com/guide/test-automation-standards-and-checklist)

## Diagrams
