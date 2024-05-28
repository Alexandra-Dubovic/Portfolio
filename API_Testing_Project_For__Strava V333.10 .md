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
<li><b>Request 1: Get athlete information</li></b>

HTTP method for request: **GET**<br>
Request description: **Returns the currently authenticated athlete. Tokens with profile:read_all scope will receive a detailed athlete representation; all others will receive a summary representation**<br>
Test types / techniques used: **Functional testing, positive testing**<br>
Response status code: **200**<br>

Below you can find a picture of the API request from Postman:<br>

![Postman Get Athlete information](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/ebc80ef0-3aca-41aa-813d-7c98281a06f9)

JavaScript Tests:

![JS Test Postman Get Athlete Information](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/5d7186e2-1535-4383-9853-dc5c7eca720f)

<li><b>Request 2: Get athlete activities</li></b>

HTTP method for request: **GET**<br>
Request description: **Returns the given activity that is owned by the authenticated athlete. Requires activity:read for Everyone and Followers activities. Requires activity:read_all for Only Me activities**<br>
Test types / techniques used: **Functional testing, positive testing**<br>
Response status code: **200**<br>

Below you can find a picture of the API request from Postman:<br>

![Postman Get Athlete Activities](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/8a90d757-dad8-4ddb-8f62-ae06a425107e)

JavaScript Tests:

![JS Test Postman Get Athlete Activities](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/7d36dc11-4bea-48fa-bf41-3cf79b51b6fe)


<li><b>Request 3: Create new activity</li></b>

HTTP method for request: **POST**<br>
Request description: **Creates a manual activity for an athlete, requires activity:write scope**<br>
Test types / techniques used: **Functional testing, positive testing, negative testing**<br>
Response status code: **201**<br>

Below you can find a picture of the API request from Postman:<br>

![Postman Create new Activity](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/3b970484-f344-499a-91aa-c6bcb02108e2)

JavaScript Tests:

![JS Test Postman Create new activity](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/c84384f1-5622-46ac-8fb0-8059211871f2)

<li><b>Request 4: Update athlete</li></b>

HTTP method for request: **PUT**<br>
Request description: **Update the currently authenticated athlete. Requires profile:write scope**<br>
Test types / techniques used: **Functional testing, positive testing, negative testing**<br>
Response status code: **200**<br>

Below you can find a picture of the API request from Postman:<br>

![Postman Update Athlete](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/986f4890-1663-429a-9bc5-9889f3c8fe9a)

JavaScript Tests:

![JS Test Postman Update athlete](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/4e45ddc8-a1d7-4fae-b905-b68b3ec0f0af)


</ol>

<h2>Execution report for the created API collection </h2>

Below you can find the execution report that was generated through the Postman collection runner. <br>

![Strava collection runner](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/9f41225a-9f6c-43e9-933a-886af3fb8900)



<h2>Defects found</h2>

The following issues were identified while running the postman tests:<br>
<ul> 
<li><b>Bug description</b>: Response time longer than expected</li>
<li><b>Priority</b>: Low</li>
<li><b>Severity</b>: Low</li>
<li><b>Preconditions</b>: User to be authentificated in Strava account</li>
<li><b>Steps to reproduce</b>: Create a new "GET" request using endpoint:https://www.strava.com/api/v3/athlete</li>
<li><b>Expected result</b>: Response time to be <200ms</li>
<li><b>Actual result</b>: Response time is >200ms</li>



<h2>Conclusions</h2>

The final report shows that a number of 2tests have failed of a total of 10 test

A number of 2 total bugs were found, both with low priority

To summarize the project:
<ul>
<li> All the functionalities in scope were covered by tests</li>
<li> Number of test cases planned: 10 </li>
<li> Number of test cases executed:10</li>
<li> Pass percentage: 80% of all tests are Passed</li> 
<li> Fail percentage: 20% of all tests are Failed</li>  
<li> Skipped tests percentage: 0% of all tests are Skipped</li> 
<li> Bugs found: 2</li>
<li> Critical bugs found: 0 </li> 
<li> Recommended to check if there is a possibility to improve response time for requestd</li>
</ul>


