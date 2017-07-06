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
