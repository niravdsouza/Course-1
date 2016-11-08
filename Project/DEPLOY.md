# Milestone: DEPLOYMENT

In the previous milestone, we implemented the services required for 3 use cases and implemented interaction with a bot. In this milestone, you will be demonstrating a fully deployed version of your bot for use in a Slack/Github/etc team.

### Deployment

Using configuring management tools, you must fully provision and configure a remote environment for your bot. You should largely be able to reuse homework materials but adopted for your bot.

In your README.md, document how these configuration management tools and deployment scripts should be run and make sure to include demonstrate running them in your screencast.

### Acceptance Testing

For Slack bots, create a slack team and a TA user account, which TAs will be using for testing your deployed bot. For github bots, grant the necessary permissions for performing tasks on a demo repository.

Provide **acceptance test instructions** for TAs to evaluate your three use cases using the TA user account.

The acceptance tests should provide concrete instructions on what to actions to perform and verify on each step.

##### Uptime Penalaties

Your bot should remain running in your deployed environment and be available for acceptance testing at any time after this deadline and final exam.

A non-running or crashing bot that requires a manual restart will incur a -10 penalty (Using automatic process restart tools such as forever should help avoid this).

If acceptance testing cannot be performed on a deployed manner and needs to be manually demoed during a scheduled TA office hours visit will incur a -40 penalty.

### Exploratory Testing and Code Inspection

You must not hard-code interaction/mock data for your bots. TAs will perform additional exploratory testing and code inspection to verify bots perform as expected and handle edge cases and error in inputs. Failure to adhere to these instructions will result in a 0 for this milestone.

### Task Tracking and Screencasts

As before, you will be tracking your tasks and recording a screencast that demonstrates the deployment process and functioning use cases.

### Evaluation

Submit repo [here](https://goo.gl/forms/bb7W1a09OrDMWTPA3)

* Deployment scripts (25%)
* Passing acceptance testing (40%)
* Exploratory Testing and Code Inspection (25%)
* Task Tracking and Screencasts (10%)

Due Tuesday, November 29th, midnight.
