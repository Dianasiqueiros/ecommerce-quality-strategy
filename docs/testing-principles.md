Setting a Foundation for Successful Test Automation

Notes from the course.

Overview

Define a goal and a strategy, make sure the organization's culture supports that strategy, develop the application in a way that makes test automation easier, choose the proper tooling based on the team and the business goal, look ahead to where you want to be and build the automation to support that vision, scale the automation beyond running locally, and set realistic expectations about the return on investment.

Chapter 1: Designing a Test Automation Strategy

When we understand our goal, and why we need test automation, we can define a better roadmap for our tests. This reduces refactoring effort later and avoids ending up with automated tests that nobody uses.

Once we understand what we need to achieve, we can move to the next phase: who will participate, who will write the code, who will maintain it, and who will monitor the results. After answering those questions we can talk about execution and implementation, such as programming language and tools.

Chapter 2: Culture

Communicating the goal of the automation, what we need in order to accomplish that goal, and the role each person plays in making it happen gives the team context and value.

Chapter 3: Developing for Test Automatability

We should automate at the lowest level that still gives us the confidence we need. The test pyramid helps here:

**UI**: slower to write and execute, so we need fewer tests at this level.
**Services**: focus on functionality without a user interface, for example API and integration tests.
 **Unit**: quick to write and execute, small modular tests that verify the logic of individual functions.

Chapter 4: Tooling for Test Automation

Choose the right tool based on the team and the time we can invest. Two options to consider: building our own automation (software development) or using code-less tools.

Chapter 5: Future-Proofing Your Test Automation Effort

Consider how we are going to run the test suite. If we plan to run tests in parallel, we need to design them with that in mind from the beginning. If we don't ask this question early, we will have to refactor later.

Other aspects to consider: setup and cleanup, avoiding tests that modify shared test data, and clean code practices.

Chapter 6: Scaling Your Test Automation

Consider whether we will run the scripts on different environments, browsers, and devices. If the answer is yes, we need to prioritize which ones come first.

Chapter 7: Measuring the Value of Your Test Automation

Define the expectations first. If we define them, we can measure them.

Decide whether the goal is to reduce the time it takes to execute the regression suite. Decide how often we need feedback and how fast we need it. And build a suite we can trust, where a failing test means there is a real problem. Other metrics we can consider is the execution time, number of defect leak to production.