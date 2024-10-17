<h1>API Testing Project for Restful-Booker API</h1>

The scope of this project is to use all  API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: **Restful-Booker**

Tools used: **Postman, Newman**

Collection link: **[Postman Collection](https://www.postman.com/tiby/workspace/proiect-final)**

<h2>Tests performed</h2>

<ol>
<li>API Status Check</li>

HTTP method for request: **GET**<br>
Request description: **A simple health check endpoint to confirm whether the API is up and running**<br>
Test types / techniques used: **Functional Testing, Positive Testing & Performance Testing to check API's response time**<br>
Response status code: **201 Created**<br>

Below you can find a picture of the API request from Postman:<br>

![RSoERLdW7e](https://github.com/user-attachments/assets/f926a2a1-4bd2-409a-95ce-94d7babe840d) <br>


JavaScript Tests:

![vecsQXxRJu](https://github.com/user-attachments/assets/998c09d9-e011-4f91-a376-6cfb2f16fe6a) <br>


<li>Create Token</li>

HTTP method for request: **POST**<br>
Request description: **Creates a new auth token to use for access to PUT/PATCH/DELETE requests**<br>
Test types / techniques used: **Functional Testing, Security Testing, Positive/Negative Testing & Performance Testing to check API's response time**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

![Mrq3eGWMTq](https://github.com/user-attachments/assets/38d6ec98-d970-44b7-9f7e-fbcd4e1509cc) <br>

JavaScript Tests:

![qWwC3Oqizb](https://github.com/user-attachments/assets/93f191e9-2fb0-4ac1-82f6-867d821cb136) <br>


<li>Get Booking IDs</li>

HTTP method for request: **GET**<br>
Request description: **Returns the ids of all the bookings that exist within the API. Can take optional query strings to search and return a subset of booking ids.**<br>
Test types / techniques used: **Functional Testing, Positive/Negative Testing & Performance Testing to check API's response time**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

![yy50NypJ00](https://github.com/user-attachments/assets/f5e57be4-ffbb-4d00-b274-f7e5d199e3be) <br>

JavaScript Tests:

![oAYn52n1bU](https://github.com/user-attachments/assets/393d1c89-8974-40a1-b881-0e3cac3a274e) <br>

<li>Get Specific Booking</li>

HTTP method for request: **GET**<br>
Request description: **Returns a specific booking based upon the booking id provided**<br>
Test types / techniques used: **Functional Testing, Positive/Negative Testing & Performance Testing to check API's response time**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

![A5WNlJ1iQL](https://github.com/user-attachments/assets/8c2bd140-2b35-4259-8f46-d6ace371c268) <br>

JavaScript Tests:

![lYPLCjrRAx](https://github.com/user-attachments/assets/e4eea9d3-5d07-4b4d-9973-ef785fee5063) <br>

<li>Create Booking</li>

HTTP method for request: **POST**<br>
Request description: **Creates a new booking in the API**<br>
Test types / techniques used: **Functional Testing, Positive/Negative Testing & Performance Testing to check API's response time**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

![qEnsRE5PGM](https://github.com/user-attachments/assets/0f7f3c5e-c682-4218-baad-0cc9e07cabad) <br>

JavaScript Tests:

![ongIOj8zZz](https://github.com/user-attachments/assets/4bdc70e9-56de-4925-a8cc-67231ab11a86) <br>

<li>Delete Booking</li>

HTTP method for request: **DELETE**<br>
Request description: **Deletes a booking based upon the booking id provided**<br>
Test types / techniques used: **Functional Testing, Security Testing, Positive/Negative Testing & Performance Testing to check API's response time**<br>
Response status code: **201 Created**<br>

Below you can find a picture of the API request from Postman:<br>

![ueQMuXjrp0](https://github.com/user-attachments/assets/453b1b13-aa35-417c-b913-06d9c0568f49) <br>

JavaScript Tests:

![4zoZV1w1JX](https://github.com/user-attachments/assets/0cfc5d4c-c3ea-40a5-8968-a15c3c8dd36d) <br>

<li>Partial Update Booking</li>

HTTP method for request: **PATCH**<br>
Request description: **Updates a current booking with a partial payload**<br>
Test types / techniques used: **Functional Testing, Security Testing, Positive/Negative Testing & Performance Testing to check API's response time**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

![eM1NfZBi13](https://github.com/user-attachments/assets/a85d9e99-fe9a-4d14-8861-825d14a94862) <br>

JavaScript Tests:

![gP47LDBwcz](https://github.com/user-attachments/assets/9393a812-c5f5-48de-a791-2a8affcc059b) <br>

<li>Update Booking</li>

HTTP method for request: **PUT**<br>
Request description: **Updates a current booking**<br>
Test types / techniques used: **Functional Testing, Security Testing, Positive/Negative Testing & Performance Testing to check API's response time**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

![G78T9dHByb](https://github.com/user-attachments/assets/0003aa2f-c0de-4d50-96bd-292f3ac12972) <br>

JavaScript Tests:

![JvTHWQPDAO](https://github.com/user-attachments/assets/badbbe5e-c662-41dc-8397-eacba597c0ce) <br>

</ol>

<h2>Execution report for the created API collection </h2>

Below you can find the execution report that was generated through the Postman collection runner. <br>

![iBhVV94Td2](https://github.com/user-attachments/assets/094076fb-fd57-461e-b57c-1529ca651e14)
![poPojihY0t](https://github.com/user-attachments/assets/f8e84739-5c8d-4c9d-bd3c-d487887b6327) <br>

The collection was also run through newman directly from the terminal, and the results can be found below:<br>

![6aD51sxDw3](https://github.com/user-attachments/assets/4f657c67-bbc9-4dd5-b91c-7a9d3be6616e)
![EHrFSipOYO](https://github.com/user-attachments/assets/f1bbed2b-eeb1-4eb1-a549-39bfd87c91f2) <br>

<h2>Defects found</h2>

The following issues were identified while running the postman tests:<br>

<li> API Status Check:</li>

    - Returned status code should be code 200 "OK", but it's code 201 "Created"

<li> Create Token: </li>

    - Returned status code when trying to create a token with invalid data should be code 401 "Unauthorised" but is code 200 "OK"

![hg87dXUbCw](https://github.com/user-attachments/assets/8d5015fc-2602-4fd6-99fd-a84ef42fad77)

<li>Booking IDs:</li>

    - The "checkout" parameter doesn't work, it returns random results instead of bookings with greater or equal checkout date
    - In a search with/without parameters where we have no results, the API returns status code 200 "OK". I think either code 404 "Not Found" or code 204 "No Content" would be more intuitive
    
![anq3vmNnNQ](https://github.com/user-attachments/assets/286827f4-8ccd-4968-870a-6a42451c70d1)

<li>Create Booking</li>

    - Upon successfully creating a booking, returned status code is code 200 "OK", I think code 201 "Created" would be more intuitive
    - The total price value cannot be a floating number. If we try to input the value "199.99" in the "totalprice" field and create a booking, only "199" would be saved
    - A booking can be created even if checkin and checkout dates aren't valid, and in the created booking the invalid dates will show up as "0NaN-aN-aN", the API returning status code 200 "OK". It should return code 400 "Bad Request" and not allow the request

![HSFY95W9gY](https://github.com/user-attachments/assets/14683cb8-4c0c-4d04-9ead-b150b645d618)

<li>Delete Booking</li>

    - Returned status code after successfully deleting a booking should be code 204 "No Content", but is 201 "Created"
    - Returned status code for trying to delete an inexistent booking should be code 404 "Not Found", but is code 405 "Method not Allowed"

![opPoY5SO2S](https://github.com/user-attachments/assets/9264420d-65b5-462c-95b2-e8737450fa45)
![2UnozNBdNy](https://github.com/user-attachments/assets/369b9748-4a90-4334-a553-2137b14601b5)

<li>Partial Update Booking</li>

    - Returned status code for trying to update an inexistent booking should be code 404 "Not Found", but is code 405 "Method not Allowed"
    - A booking can be updated with invalid checkin and checkout dates, the updated booking showing the invalid dates as "0NaN-aN-aN", the API returning status code 200 "OK". It should return code 400 "Bad Request" and not allow the request

<li>Update Booking</li>

    - Returned status code for trying to update an inexistent booking should be code 404 "Not Found", but is code 405 "Method not Allowed"
    - A booking can be updated with invalid checkin and checkout dates, the updated booking showing the invalid dates as "0NaN-aN-aN" and the API returning status code 200 "OK". It should return code 400 "Bad Request" and not allow the request

<li>API Bugs</li>

    - The API has inconsistent response times. It can go from 100-200ms response time to as long as 1000ms, which can impact user experience drastically
    - The token created with the provided information in the documentation doesn't work as intended. It's supposed to allow you to use the POST/PATCH/DELETE requests, but if you try to use the request with the token for authorization the API will return code 403 "Unauthorized" for all 3 requests. To use the requests you'll have to use "Basic Auth", using the credentials used to generate the token initially
    
<h2>Conclusions</h2>

**To test the Restful Booker API I wrote and executed 25 tests in Postman, testing its functionality according to the API Documentation, to make sure it's behaving as intended and I managed to cover every request the API has to offer. The bugs I found could impact the launch of the product, especially the ones that affect the proper functionality of the API. For example, the inconsistent response time of the API can lead to a bad experience for users, leading them to lose interest in the product fairly quickly. The base of the product has been established, so I would recommend focusing on fixing the major bugs, making sure every module and its features work correctly.


