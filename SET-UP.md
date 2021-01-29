# Issues, Wikis, & Templates
Copiable issues, wikis, & templates for new project setup

## Instructions
Copy each item into its own issue, wiki, or template appropriately at the beginning of project.  
 **-** To copy click on raw on the top right corner of this document. 

## Current Copiables
1. New Project Setup Steps  
2. Continuous Testing Checklist

<h2>Set up for new project</h2>

1. - [ ] Create Kanban Columns -Funnel->Analysis & Exploration->Backlog->In Progress->Review & Test->Done->Closed

2. - [ ] Create Workspace

3. - [ ] Set up the project in Zenhub

4. - [ ] Set up milestones in Zenhub

5. - [ ] Copy over wiki template

<h2> End of Set up.</h2>

<h2> Continuous Testing Checklist </h2> 
    
## Assess

### Capacity 
- [ ] available time?

### Capability
- [ ] who can work on testing? 

### Groundwork
- [ ] any continuous testing already in place?

### Resources
- [ ]  **What tools are available or preferred?**

1. - [ ] The option to run the same sets of tests with different provisioning (i.e. a developer can run a module test from behind the firewall with local resources, and the same test can run in production from multiple geographical locations on the public cloud)
2. - [ ] The ability to easily adopt a new provisioning scheme when a test configuration is executed in a different environment (e.g. Dev, CI, Pre-Prod, Post-Prod). These schemes should include:
1. - [ ] A private cloud of resources available on-premise and protected behind the firewall
2. - [ ] A public cloud of unlimited resources available on multiple geographical locations
3. - [ ] Sufficient resources in the public and private cloud, enabling organizations to run multiple tests in parallel with zero time to test
4. - [ ] The option for users to define which OS and Browser combinations they want to execute the test against
5. - [ ] The ability to start testing as part of the CI process (i.e. Jenkins, Travis, TeamCity, CircleCI, etc.)

### Identify the 80/20
- [ ] Which continuous test will give the biggest return?

## Roadmap & Plan
- [ ] **identify tools**

1. - [ ] Support for both manual and automated testing
2. - [ ] The provision of libraries and APIs to create “homegrown” tests using common DSLs.
3. - [ ] Ability to activate commercial tools (such as Perfecto Mobile)
4. - [ ] Support of JMeter and API tests (BlazeMeter)
5. - [ ] The ability to create browser-based tests (Selenium Builder, BlazeMeter Chrome Plugin)
6. - [ ] Support of Selenium and Appium tests (Sauce Labs)

- [ ] **define version control**
1. - [ ] The ability to support version control, incremental testing, and associate test configurations, sets of tests, and tests with versions (e.g code, build, RC, releases).

- [ ] **define continuous integration**
- [ ] **validate current manual & automated tests**
- [ ] **delegate**
- [ ] **document continuous testing system**
- [ ] **define continuous testing SOP**
- [ ] **define new tests, data, mocks, works items**

## Develop and Install
### Acquire & Setup Tools
- [ ] **setup continuous integration tools (Jenkins, circle ci, etc)**
1. - [ ] The ability to run any test configuration, a test, or a set of tests using simple API calls
2. - [ ] The option to run as many tests as required in parallel
3. - [ ] Availability of all test data via a REST API

### Repair & Code New Tests
- [ ] **create new tests and mechanisms to monitor the continuous testing process**
1. - [ ] Automatic indications of failures, with an alerting scheme per developer, module, and project
2. - [ ] The ability to gather all test artifacts and immediately send to relevant people
3. - [ ] The option to run the failed tests again to identify the root cause
4. - [ ] The ability to run any type of test on-demand. This is critical for test development, debugging, troubleshooting, and identifying the root cause of a failure
5. - [ ] The option to automate test executions and run the same test on-demand


### Document & Train
- [ ] **document the process** 
1. - [ ] Seamless integration with existing reporting solutions (e.g. Jenkins Performance Trend)
2. - [ ] The option to group tests by builds
3. - [ ] The ability to give jobs a ‘pass’ or ‘fail’ status and group accordingly
4. - [ ] Pass/fail trend reports
5. - [ ] “Deep dive” reports for diagnostics and analysis, which can overlay data from third-party systems (e.g. NewRelic, CloudWatch) for a comprehensive picture.

- [ ] **train staff on CTF**

## Monitor & Maintain
### Reassess
- [ ] **schedule reviews to reassess the current situation**

### Replan
- [ ] **define and plan to complete any new items found**
1. -[ ] The ability to combine different configuration fragments into one test configuration in order to comprehensively test build, release, and production snapshots.

### Develop
- [ ] **develop items according to plan, as part of your normal process**

<h2> End of Continuous Testing Checklist </h2> 

Links work like this [markdown reference](https://commonmark.org/help/)
