# Testing Project for **JIRA**

The scope of the final project for the ITF Manual Testing Course is to use all the knowledge gained throughout the course and apply it in practice, using a live application.

**Application under test**: SPOTIFY

**Tools used**: Jira, Zephyr Squad

## Functional specifications

The below story was created in Jira and describes the functional specifications of the "**User experience and profile security**" module, for which the final project is performed upon.

**Insert the image of the story/stories here (if you have more than two stories, it is recommended to download the stories from Jira and upload them as a file).**

Here you can find the release that was created for this project:

**Insert the image of the release created in Jira. Note: The release should only contain epics, stories, tasks, subtasks, and bugs, but not tests.**

## Testing process

The test process was performed based on the standard test process as described below.

### 1.1 Test planning

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here: **Insert the link to the test plan document**

#### 1.1.1 Roles assigned to the project and persons allocated

* Project Manager: [Mark Hamlin]
* Product Owner: [George Marian]
* Software Developer: [Puscas Tiberiu]
* QA Engineer: [Puscas Tiberiu]

#### 1.1.2 Entry criteria defined

* Requirements have been defined and approved.
* Test environment is set up and stable.
* Test data is available and prepared.
* Access to necessary tools and resources.
* Development is complete and code is deployed to test environment.

#### 1.1.3 Exit criteria defined

* All planned test cases have been executed.
* All critical and major bugs have been fixed or have acceptable workarounds.
* Test summary report is prepared and reviewed.
* No open critical defects.
* Acceptance criteria met as defined in the test plan.

#### 1.1.4 Test scope

**Tests in scope:**

* Functional testing of user login and registration.
* Testing playlist creation and management.
* Verifying search functionality.
* Ensuring song playback works as expected.
* Security testing for profile updates, password changes, and two-factor authentication.
* Testing account deletion and privacy settings.
* Testing session management and notifications.

**Tests not in scope:**

* Load and performance testing.
* Testing on legacy or unsupported browsers/devices.
* End-to-end testing with external integrations.
* UI/UX design assessments not related to functionality.

#### 1.1.5 Risks detected

**Project risks:**

* Delays in test environment setup.
* Insufficient test data availability.
* Changes in requirements during testing phase.

**Product risks:**

* Potential security vulnerabilities in profile management.
* Functional bugs affecting user experience.
* Performance issues under high load conditions.

#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control

**Insert the reason for the monitoring and control stage and how it was conducted. Include the test status report from Zephyr - test metrics reflecting the activity and progress of the testing.**

### 1.3 Test Analysis

The testing process will be executed based on the application requirements. **(The requirements analysis has been done in order to implement the early testing test principle and the results can be found here - insert the link to the review document if applicable.)**

The following test conditions were found:

**(![test cases](https://github.com/Tiberiu33/Proiect-final-puscas-tiberiu-jira/assets/167067779/228d807f-58f7-4152-b808-d588c38c9907)
)**

### 1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here: **Insert the link to the test cases document in PDF, Word, or CSV format.**

### 1.5 Test Implementation

The following elements need to be ready before the test execution phase begins:

* Test environment setup.
* Test data preparation.
* Test scripts reviewed and approved.
* Test tools configured and validated.
* Access to necessary resources ensured.

### 1.6 Test Execution

Test cases are executed on the created test Cycle summary: **Insert the name of the created test cycle.**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **Insert the link to the document with the identified bugs.**

The following is a summary of the bugs that have been found:

**(Failure to change gender priority medium
Login functionality rejects valid credentials priority medium

Account deletion functionality is not working properly priority medium.)**

Full regression testing is needed on the impacted areas after the bugs are fixed, and retesting will be done for every functionality that previously failed.

### 1.7 Test Completion

As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.

The traceability matrix was generated and can be found here: **Insert either a screenshot of the traceability matrix from Jira or a link to the exported Excel file with the traceability matrix. Ensure filtering by type = story.**

Test execution chart was generated and can be found below:

**Insert the test execution report generated from Jira from the dashboards section.**

The final report shows that a number **(5)** tests have failed out of a total of **(Insert the number of tests)** tests.

A total of **(Insert the number of bugs)** bugs were found, from which **(Insert the number of high-priority bugs)** are high and **(Insert the number of medium-priority bugs)** are medium.

**General conclusion of the testing**:

* **Total tests created and executed**: (5)
* **Percentage of requirements in scope covered**: (100)
* **Impact of identified bugs on product launch**: (Bugs have been fixed and do not impact the launch of the product)
* **Identified product risks and mitigation**: (The risks have been solved)
* **Recommendations for product launch**: (It is recomended to do more black box testing on the user functionality part)
* **Lessons learned for future projects**: (We learned that more attention to detail is necessary for future projects)
