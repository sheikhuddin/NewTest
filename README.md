#### NewTest
## NBCUniversal SQE Craft Demonstration Challenge
## Test Plan
### Introduction
This test plan describes strategies for testing Developer's API

### Features To Be Tested
Developer's API is a RESTful API to fetch Sound data from Sound Cloud provided by NASA. Goal is make a GET API call [Sound API](https://api.nasa.gov/planetary/sounds) with various query parameters and validate responses. This is to ensure that API provides meaningful data to Developers.

### API
Details for API can be found [here](https://api.nasa.gov/api.html#sounds).
1. For this demo, we'll use:
 ** [API End Point](https://api.nasa.gov/planetary/sounds) **

 | Parameter | Type | Default | Description |
 |-----------|------|---------|-------------|
 | q | string | None | Search text to filter results |
 | limit | int | 10 | number of tracks to return |
 | api_key | string | DEMO_KEY | api.nasa.gov key for expanded usage |

1. What is supported?
   1. GET API Call is supported
   

### Test Objectives

1. To certify this API for public consumption, with parameters q, limit & api_key. 
2. Code few key examples to demonstrate how you can automate your tests.

### Test Steps

1. Given the SOAP UI application is open.

2. Create new REST project with URL of https://api.nasa.gov/api.html#sounds

3. Use GET method with the endpoint of https://api.nasa.gov/planetary/sounds 

4. Right Click on Api.html and Select new Child Resources to provide a template

5. Parameters can be placed in the 'New Resource'.'


**Steps to Perform API Testing**
---

1. Right Click on the project and select 'New Test Suite' from the drop down menu.

2. Specify a name for the Test suite.

3. Right click on the Test Suite and add 'New Test Case' and specify a name for the case.

4. In the Test case 'Add Step' for the 'REST Request' and specify a name.

5. SOAP UI will ask option for selecting the appropriate request to test.

6. In the test case we can perform different validation for the testing purpose.

7. In the test case level it is possible to perform different kinds of assertions.


*Problems found while doing API testing*
---

1. The provided URL doesn't provide any codes in the Raw portion of SOAP.
