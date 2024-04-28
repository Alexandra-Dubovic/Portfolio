<h1>API Testing Project for Strava V333.10 web application</h1>

The scope of this project is to use all  API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: **Strava V333.10 web application**

Tools used: Postman

Collection [link](https://github.com/Alexandra-Dubovic/Portfolio/blob/main/Strava.postman_collection.json)

In order to perform tests we have to obtain authentification token. Strava API allows create, update and read existing information. For each scope it is necessary to obtain a separate authentification token. Following steps from Strava API documentation available at <a> https://developers.strava.com/docs/getting-started/</a> following HTTP requests were created:

![Strava API tokens requests](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/f6920479-5b13-4693-8c3a-d568fef04f81) 

To ensure the efficiency of testing process all obtained token were parameterized:

![Starva tokens parameterized](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/d6209450-fabf-4c6a-bdd9-cae94818c746)

Now setup is ready to perform the tests.

<h2>Tests performed</h2>

<ol>
<li>Request 1: Get athlete information</li>

HTTP method for request: **GET**<br>
Request description: **Returns the currently authenticated athlete. Tokens with profile:read_all scope will receive a detailed athlete representation; all others will receive a summary representation**<br>
Test types / techniques used: **Functional testing, positive testing**<br>
Response status code: **200**<br>

Below you can find a picture of the API request from Postman:<br>

![Postman Get Athlete information](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/ebc80ef0-3aca-41aa-813d-7c98281a06f9)

JavaScript Tests:

![JS Test Postman Get Athlete Information](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/5d7186e2-1535-4383-9853-dc5c7eca720f)

<li>**Request 2*: Get athlete activities*</li>

HTTP method for request: **GET**<br>
Request description: **Returns the given activity that is owned by the authenticated athlete. Requires activity:read for Everyone and Followers activities. Requires activity:read_all for Only Me activities**<br>
Test types / techniques used: **Functional testing, positive testing**<br>
Response status code: **200**<br>

Below you can find a picture of the API request from Postman:<br>

![Postman Get Athlete Activities](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/8a90d757-dad8-4ddb-8f62-ae06a425107e)

JavaScript Tests:

![JS Test Postman Get Athlete Activities](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/7d36dc11-4bea-48fa-bf41-3cf79b51b6fe)


<li>**Request 3: Create new activity*</li>

HTTP method for request: **POST**<br>
Request description: **Creates a manual activity for an athlete, requires activity:write scope**<br>
Test types / techniques used: **Functional testing, positive testing, negative testing**<br>
Response status code: **201**<br>

Below you can find a picture of the API request from Postman:<br>

![Postman Create new Activity](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/3b970484-f344-499a-91aa-c6bcb02108e2)

JavaScript Tests:

![JS Test Postman Create new activity](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/c84384f1-5622-46ac-8fb0-8059211871f2)

</ol>

<h2>Execution report for the created API collection </h2>

Below you can find the execution report that was generated through the Postman collection runner. <br>

**Inserati aici o poza cu raportul de executie din Postman**<br>

The collection was also run through newman directly from the terminal, and the results can be found below:<br>

**Inserati aici o poza cu raportul de executie din Newman**<br>

<h2>Defects found</h2>

The following issues were identified while running the postman tests:<br>

****Inserati aici fie un fisier pdf care sa contina raportarea tuturor bug-urilor, fie le descrieti direct in git
Bug-urile trebuie sa contina titlu, preconditii, pasi de executie, rezultate asteptate si rezultate actuale.
Optional, bug-urile pot fi raportate in jira, si apoi puteti pune poze direct din jira**

<h2>Conclusions</h2>

**Inserati aici concluziile pe care le-ati obtinut in urma executarii testelor  si introduceti informatii cum ar fi cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc**


