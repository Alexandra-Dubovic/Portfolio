<h1>Testing Project for Strava V333.10 web application</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: Strava V333.10 web application

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

Modules in scope of this project are:
<ul>
  <li>Training module</li> 
  <li>Upload module</li>
  <li>Support module</li>
</ul>  

Here are the [Stories for Strava Project](https://github.com/Alexandra-Dubovic/Portfolio/files/14817229/Jira.Stories.Strava.Project.pdf) created in Jira that describe the functional specifications of the modules in scope of this project, for which the final project is performed upon.

Also you can find the release that was created for this project:

![RElease Jira](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/3674f6e4-763d-4189-af7f-8c4add911387)
![Release jira p2](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/b42b48c2-0979-4c1d-9933-3bcf830caa88)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the Strava application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here [Strava V333.10 test plan](https://github.com/Alexandra-Dubovic/Portfolio/files/14550605/Strava.V333.10.test.plan.pdf)

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager: Ciubotarescu Alina</li> 
  <li>Product owner: Falescu Mihai</li>
  <li>Software developer: Bente Tudor</li>
  <li>QA Engineer: Dubovic Alexandra</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

<dl>
  <dd>-	Testing environment is up and running smooth</dd>
  <dd>-	Business requirements are completed by the analysis team and are delivered to the appropriate testing team for evaluation</dd>
  <dd>-	Potential project risks are detected and mitigated</dd>
  <dd>-	Roles and responsibilities are allocated/dd>
  <dd>-	Test plan should be finalized before entering the next phase of testing</dd>
  <dd>-	Define the objectives of testing and the accepted level of quality</dd> 
</dl>

<h4> 1.1.3 Exit criteria defined </h4>

<dl>
  <dd>-	90% or more of the tests are passed</dd>
  <dd>-	No critical issues have status open</dd>
  <dd>-	All detected errors have been reported and closed</dd>
  <dd>-	The budget was reached</dd>
  <dd>-	The deadline was reached</dd>
  <dd>-	The objectives were fulfilled</dd> 
  <dd>-	The product usage documentation has been finalized with the scenarios evaluated
        during the testing phase</dd> 
  <dd>-	Test completion report has been created and sent to the stakeholders</dd>
  <dd>- Product risks have been identified and mitigated</dd>
</dl>

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

Strava application is available both for web and mobile users. The objective of this project is to focus on improving the quality of the web application. The version under testing is V333.10 released in November 13, 2023.

Strava provides users with a large range of functionalities (tracking, competitions, measuring etc.). For this project the functionalities in scope of testing process are:

<dl>
  <dt>Training module</dt>
  <li>Training calendar</li>
  <li>My activities</li>
  <dt>Upload</dt>
  <li>Upload activity</li>
  <li>Add manual entry</li>
  <li>Create a route</li>
  <li>Create a post</li>
  <dt>Help</dt>
  <li>Strava support</li>
</dl>

As the application is live testing will be performed at  a system testing level. During the testing process will be performed functional testing and some types of non- functional testing (usability testing), positive and negative testing and also if needed retesting and regression testing will be performed.

Based on requirement analysis some additional testing  types and techniques may be applied.


<h5>Tests not in scope: </h5>
<dl>
  <li>Non-functional testing like stress, performance is beyond scope of this project</li>
  <li>Only web application will be tested for this project</li>
  <li>All the functionalities except the ones mentioned in chapter 1.1.4 are out of scope for this project and will be tested with next iterations.</li>
</dl>

<h4>1.1.5 Risks detected</h4>

During the planning stage of the testing process below risks were identified and mitigated:

<h5>Project risks:</h5>

<ul>
<li> The team does not have the proper knowledge or experience in order to guarantee the desired level of quality for the application </li>
<li> Not enough time has been allocated in order to properly test and cover all the functionalities in scope</li>
<li> All that the data that is going to be used will have to be created explicitly in the scope of testing, which will cut off from the time allocated for testing, generating a risk of not
reaching the deadline</li>
</ul>

Duirng the test closure stage below risks were identified:

<h5> Product risks: </h5> 

<ul>
<li> All the data that is going to be used will be test data, which will not give us an experience of the application close enough to the ones that the user will experience </li>
<li> Complex features may affect multiple areas of the existing product making it less user friendly </li>
</ul>


<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>

We will evaluate the test status reports and monitor them all throughout the testing process in order to ensure a smooth testing and team collaboration and in order to make sure that new risks are identified in time and managed accordingly

In case new risks will appear they will be mitigated or a contingency plan will be set in place to make sure that the negative effects will not stop us from fulfilling the testing objectives that were defined in the planning phase


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. 

The following test conditions were found: <br>

![Test conditions](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/b12f1709-92a6-460e-b030-6647a1d8f8a4)


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here [Test cases.xlsx](https://github.com/Alexandra-Dubovic/Portfolio/files/14842258/Test.cases.xlsx)


<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

<ul>
<li> Test data is created based on the requirements identified in previous phases </li>
<li> Test cases are prioritized based on the risk and business importance</li>
<li> Testing environment is ready, all permissions and documentation is available and ready for use</li>
</ul>

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: Strava App V333.10 Cycle summary:

![Cycle summary](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/83bf9da0-427b-499b-a257-85151958e05f)

Bug reports have been created based on the failed tests. The complete bug reports can be found here: [Bug reports ](https://github.com/Alexandra-Dubovic/Portfolio/files/14842423/Bug.reports.pdf)

The following is a summary of the bugs that have been found![Bugs priority](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/85ca7b3e-4dc4-47bd-b542-5b6372c1515f)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3>1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: ![Traceability matrix](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/39fafcbe-1cc3-4670-9931-3e245bab744f)

Test execution chart was generated and can be found below. 

![Execution report](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/609130ba-9e3b-4a1c-b205-f09e3b5ca80e)

The final report shows that a number of 3 tests have failed of a total of 10 test

A number of 5 total bugs were found, from which the priority is: 2 are high and 3 are medium.

To summarize the project:
<ul>
<li> All the functionalities in scope were covered by tests</li>
<li> Number of test cases planned: 10 </li>
<li> Number of test cases executed:10</li>
<li> Pass percentage: 70% of all tests are Passed</li> 
<li> Fail percentage: 30% of all tests are Failed</li>  
<li> Skipped tests percentage: 0% of all tests are Skipped</li> 
<li> Bugs found: 5</li>
<li> Critical bugs found: 0 </li> 
<LI> Recommended to make a regression test after fixing the bugs and to follow upLI>
</ul>
