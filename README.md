# API_Testing
will do API testing (Restful,Soap and automate those calls with Playwright, javascript and Postman
10/08
—----
CRUD operations or API methods:’
Get, post, delete, puut, aptch
Request payload
Response payload
API—-Application programming interface, it will deliver the request fr client to server and response fro server to client.

Check these URLS for API knowledge:

API methods

https://developer.mozilla.org/en-US/docs/Web/API

API status code:
1xx–positive
2XX–positive
3XX–positive
4XX–client side error
5XX–server side error

Query param:   ?demo=value&dev=123
Path param: en-US/docs/Web/API
Endpoint:  https://www.airbnb.se/ —Prod
Endpoint : https://www.airbnb.se/stage— Stage

20-08-24:
Restful-booker

Create a complete collection to RestFul-booker and if possible create for perstStore site as well. 
If you curl command in postman request, automatically the API method will appear,and URL will be shown converted from Curl command.

Body: will send query part
Script: Write a script to validate or assert the Postman values.

Postbot is similar to Copilot same as in Vss code.
Click on ‘Postpot’, then click on ‘Add some test to this request’



Click on that button, it will open the curl command, then select any kind of code snipper, and it will display that particular code.
This option is  to automate the Postman requests. Just drag this code to the VSS code editor and update it accordingly.



Collection variables,
Environment variables.

If you set a collection variable in scripts, then run this script, automatically the value will update in the collection variable tab.

22-08:

Wherever we have environment-specific to UAT, PROD, SIT, Dev then use environment variables.
If you access baseURL from the same present value in both collection and environment variables, the priority is always for environment variables rather than collection variables.

The priority from highest to lowest is:
Local (Highest Priority)
Data
Environment
Collection
Global (Lowest Priority)
1. Local Variables 🥇
Scope: These are temporary variables that exist only within the context of a single request or collection run.
Where to use: They're defined in a pre-request or test script using pm.variables.set().
Purpose: Use these to temporarily override values for a specific run without affecting any other variables. Their value is not saved after the run is complete.
2. Data Variables
Scope: These are variables loaded from external files (CSV or JSON) when using the Collection Runner.
Where to use: They're only available during a collection run and are used for data-driven testing.
Purpose: To run the same request multiple times with different sets of data. For example, testing an endpoint with a list of various users from a CSV file.



