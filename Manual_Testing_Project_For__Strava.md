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

Here are the [Stories for Strava Project](https://github.com/Alexandra-Dubovic/Portfolio/files/14817229/Jira.Stories.Strava.Project.pdf) created in Jira and describe the functional specifications of the modules in scope of this project, for which the final project is performed upon.

Also you can find the release that was created for this project:

![RElease Jira](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/3674f6e4-763d-4189-af7f-8c4add911387)
![Release jira p2](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/b42b48c2-0979-4c1d-9933-3bcf830caa88)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the Strava application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here [Strava V333.10 test plan.pdf](https://github.com/Alexandra-Dubovic/Portfolio/files/14550605/Strava.V333.10.test.plan.pdf)

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

<h5>Project risks:</h5>

**(enumerati aici toate riscurile de proiect pe care le-ati identificat pentru proiectul vostru)**

<h5> Product risks: </h5>

**(enumerati aici toate riscurile de produs pe care le-ati identificat pentru proiectul vostru)**

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>

We will evaluate the test status reports and monitor them all throughout the testing process in order to ensure a smooth testing and team collaboration and in order to make sure that new risks are identified in time and managed accordingly

In case new risks will appear they will be mitigated or a contingency plan will be set in place to make sure that the negative effects will not stop us from fulfilling the testing objectives that were defined in the planning phase


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

**(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)**

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**
