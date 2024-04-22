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
Test types / techniques used: **Inserati tipurile si tehnicile de testare folosite pentru acest request**<br>
Response status code: **Inserati aici status code-ul pe care l-ati obtinut in urma executiei requestului**<br>

Below you can find a picture of the API request from Postman:<br>

**Inserati aici o poza cu requestul din postman in care sa se observe request method, endpoint, request body si response body**<br>

JavaScript Tests:

**Inserati aici o poza cu testele in java script pe care le-ati definit impreuna cu rezultatele executiei acestora**<br>


<li>**Nume Request 2**</li>

HTTP method for request: **Inserati aici metoda HTTP a requestului**<br>
Request description: **Inserati o scurta descriere a requestului, conform documentatiei de API**<br>
Test types / techniques used: **Inserati tipurile si tehnicile de testare folosite pentru acest request**<br>
Response status code: **Inserati aici status code-ul pe care l-ati obtinut in urma executiei requestului**<br>

Below you can find a picture of the API request from Postman:<br>

**Inserati aici o poza cu requestul din postman in care sa se observe request method, endpoint, request body si response body**<br>

JavaScript Tests:

**Inserati aici o poza cu testele in java script pe care le-ati definit impreuna cu rezultatele executiei acestora**<br>

.............

<li>**Nume Request n**</li>

HTTP method for request: **Inserati aici metoda HTTP a requestului**<br>
Request description: **Inserati o scurta descriere a requestului, conform documentatiei de API**<br>
Test types / techniques used: **Inserati tipurile si tehnicile de testare folosite pentru acest request**<br>
Response status code: **Inserati aici status code-ul pe care l-ati obtinut in urma executiei requestului**<br>

Below you can find a picture of the API request from Postman:<br>

**Inserati aici o poza cu requestul din postman in care sa se observe request method, endpoint, request body si response body**<br>

JavaScript Tests:

**Inserati aici o poza cu testele in java script pe care le-ati definit impreuna cu rezultatele executiei acestora**<br>

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


