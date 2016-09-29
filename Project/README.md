# Projects

This semester you will build a bot that provides a service in support of a software engineering task. There are many ways to design and interact with a bot -- but the main constraint is that it has to deal with as a primary concern something that is a software development concern, like testing software, and not a general one, like ordering takeout.

### Teams

Students shall form teams of size 4-5. No more, no less without instructor approval.

### Milestones

You will deliver your project in 5 milestones, which will include a design, a bot component, a service component, a deployment component, and a final report and video demo.

Milestones generally prescribe a set of high-level design goals, giving much freedom in how you satisfy the goals as long as the meet the required criteria.

Details will emerge throughout the semester, but the following will give you a rough outline of the expected work.

##### Design

The design phase is about thinking through what you want to build. There will be design materials that will help you reason about your idea. Although your implementation may stray from your design, you'll to have stay within the parameters of your original idea. So make sure you get this right.

##### Bot

A primary mechanism for interaction with a service will be through a bot. How will that work? Figure out the home platform for the bot (slack, facebook messenger, kik, github webhooks, etc.). How do you get it to do what you want.

##### Service

What does your bot help you do? What's a common pain point of a software developer?

Some areas that could be of interest:

* Configuration management
* Unit tests
* Test coverage
* Build server
* Static analysis tools
* Parsing code
* Collecting metrics
* Interactions with runtime operations, infrastructure (feature flags)
* Monitoring, analysis

##### Deployment

You must be able to deploy your code to some hosted service, using configuration management, and orchestration of services.

##### Report

You must create a report that describes your entire project from design to implementation and a demo video demostrating your bot in action.

## Deliverables

Starting with your Bot milestone, you must deliver your iteration worksheets.

### Iteration Worksheet


At the end of each iteration, you will submit a completed iteration worksheet at the end of the iteration (include in WORKSHEET.md). This will describe the tasks completed for your use case and scenarios.

An example sheet follows:

### Week 1

| Deliverable   | Item/Status   |  Issues/Tasks
| ------------- | ------------  |  ------------
| Use Case      | Get Meeting Availability          | &nbsp;
| Scenario      | 1             |  #33, #38, #78
| Scenario      | 2             |  [Pivotal Task](https://www.pivotaltracker.com/story/show/114636091)
| Scenario      | 3             |  [Trello Card](https://trello.com/c/diA1DaMw)
| Scenario      | &nbsp;        | &nbsp;
| Unit Tests    | Complete      | testGetMeetingDataFromUser, testFindAvailability, ...
| Selenium Tests| Incomplete    | scenario1, error1,...

* Github issues in a markdown referred to as `#33` will automatically turn into links when in same repo.
* You can link to trello cards by click on share inside a card to get a link.
* You can link to pivotal stories by clicking on the first button left of ID in detail view.
* You reuse the markdown of the above table for your worksheet.

### Stories and Tasks

You should practice agile by breaking scenarios down into smaller stories and tasks and plan how to test, implement, and deliver those changes in a week. Because you need to deliver a use case almost every week, you might consider having tasks that separately handle different layers of system. You will find this is a common situation in an agile team. Some suggested breakdowns include:

* Design
* Reports, scrum master, planning
* Creating database tables
* Creating mocking data
* Scripting selenium
* Bot interaction
* Slack intergration
* Message conversation
* Service connections 

Finally, you may find the [SMART](https://www.mindtools.com/pages/article/smart-goals.htm) method a good way plan tasks.
