Final Project Report for ITF Manual Testing Course
Introduction

The scope of the final project for the ITF Manual Testing Course is to use all the knowledge gained throughout the course and apply it in practice using a live application.

Application under test: Spotify

Tools used: Jira, Zephyr Squad

Functional specifications:
The below story describes the functional specifications of the "User Module," for which the final project is performed upon.

Story and Release Details:
![Story and Release Details]![screenshot of story and epic and all the elements in the project](https://github.com/user-attachments/assets/dd2d4836-dabb-4ec1-9d20-ff99c1ab859b)


Testing Process

The test process was performed based on the standard test process as described below.
1.1 Test Planning

The Test Plan is designed to describe all details of testing for all the modules from the Spotify application. The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

Test Plan Document: (https://filebin.net/unzrqz3onxjd2stp)
1.1.1 Roles Assigned to the Project and Persons Allocated

    Project Manager: John Doe
    Product Owner: Jane Smith
    Software Developer: Bob Brown
    QA Engineer: [Puscas Tiberiu]

1.1.2 Entry Criteria Defined

    Functional specifications are complete and approved.
    Test environment is set up and accessible.
    Test data is prepared.
    Necessary tools (Jira, Zephyr Squad) are configured.
    All dependencies are resolved.

1.1.3 Exit Criteria Defined

    All planned test cases are executed.
    All critical and high-severity bugs are resolved or mitigated.
    Test coverage meets the required standards.
    All test results are documented.
    Sign-off from the QA team and stakeholders.

1.1.4 Test Scope

Tests in Scope:

    Functional testing of user registration, authentication, profile management, social interactions, and preferences/settings.
    Regression testing.
    Usability testing on web and mobile devices.

Tests Not in Scope:

    Performance testing.
    Load testing.
    Security testing beyond basic authentication and authorization.

1.1.5 Risks Detected

Project Risks:

    Delays in test environment setup.
    Limited availability of test data.

Product Risks:

    Potential security vulnerabilities in the authentication module.
    Inconsistent behavior across different devices.

1.1.6 Evaluating Entry Criteria

The entry criteria defined in the Test Planning phase have been achieved, and the test process can continue.
1.2 Test Monitoring and Control

The monitoring and control phase ensures the test process is on track and any deviations are addressed promptly. The status report reflects the activity and progress of testing.

Test Status Report: (https://github.com/user-attachments/assets/43b15eef-e19a-46fe-93cf-fedf2b07e91f)

1.3 Test Analysis


The testing process was executed based on the application requirements. The requirements analysis was done to implement early testing principles.

Test Conditions Found:

    Verify user can duplicate Playlist (PT-37)
    Verify user can remove Songs from Playlist (PT-36)
    Verify user can reorder songs in Playlist (PT-35)
    Verify user can rename Playlist (PT-34)
    Verify user can edit and save profile name (PT-32)
    Verify user can edit profile information (PT-30)
    Verify user can change profile gender and save settings (PT-26)
    Verify user can create a new Playlist (PT-25)
    Verify user can change language from settings (PT-24)
    Verify users can customize notification preferences (PT-23)

1.4 Test Design

Functional test cases were created in Zephyr Squad based on the specifications analysis.

Test Cases Document: 
1.5 Test Implementation

The following elements need to be ready before the test execution phase begins:

    Test environment setup.
    Test data preparation.
    Access to necessary tools (Jira, Zephyr Squad).
    Assignment of test cases to testers.


1.6 Test Execution (https://github.com/user-attachments/files/16404553/PDF.Jira.pdf)

Test cases were executed in the created test cycle summary: "Spotify User Module Cycle"

Bugs have been created based on the failed tests.

Bug Reports Document: [PT-27-1.pdf](https://github.com/user-attachments/files/16404569/PT-27-1.pdf)
[PT-28.pdf](https://github.com/user-attachments/files/16404570/PT-28.pdf)


Summary of Bugs Found:

    PT-26: Failure to change gender and save profile settings (Priority: High, Severity: Critical)
        Bug: Failure to change gender
        Bug: Failure to save profile settings

Full regression testing is needed on the impacted areas after the bugs are fixed, and retesting will be done for every functionality that was previously failed.
1.7 Test Completion

As the exit criteria were met and satisfied, the feature is suggested to 'Go Live' by the Testing team.

Traceability Matrix: [Forward Traceability_28_7_2024.xlsx](https://github.com/user-attachments/files/16404536/Forward.Traceability_28_7_2024.xlsx)


Test Execution Chart: ![test status](https://github.com/user-attachments/assets/7ee13eaa-a007-497d-b841-814bb4fbea31)

The final report shows that 1 test has failed out of a total of 10 tests.

A total of 2 bugs were found, with 1 being high priority and 1 being critical severity.

General Conclusion:

    A total of 10 test cases were created and executed.
    Approximately 90% of the requirements in scope were covered.
    The failed test case (PT-26) needs immediate attention due to its critical nature.
    The identified bugs do not prevent the product from going live, but they must be fixed in subsequent releases.
    Recommendations include ongoing monitoring and regular regression testing.
    Lessons learned include the importance of thorough test environment setup and ensuring comprehensive test data availability.

Overall, the project demonstrated effective application of manual testing principles and tools, ensuring that the Spotify user module meets the required standards for user engagement, security, and experience.
