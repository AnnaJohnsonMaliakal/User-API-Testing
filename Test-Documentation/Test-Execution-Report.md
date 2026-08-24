# Test Execution Report

## Overview

The User API collection was executed in Postman to verify the API requests and response validations.

## Test Environment

* Tool: Postman
* API: JSONPlaceholder
* Test Type: API Testing
* Execution: Collection Runner

## Execution Summary

* Total requests: 6
* Total automated tests: 18
* Passed: 18
* Failed: 0
* Pass rate: 100%

## Execution Results

| Test Case ID | Test Scenario     | Method | Status Code | Tests Passed | Result |
| ------------ | ----------------- | ------ | ----------: | -----------: | ------ |
| TC001        | Get all users     | GET    |         200 |          4/4 | PASS   |
| TC002        | Get user by ID    | GET    |         200 |          2/2 | PASS   |
| TC003        | Create a new user | POST   |         201 |          3/3 | PASS   |
| TC004        | Update a user     | PUT    |         200 |          5/5 | PASS   |
| TC005        | Delete a user     | DELETE |         200 |          2/2 | PASS   |
| TC006        | Get invalid user  | GET    |         404 |          2/2 | PASS   |

## Validations Performed

* HTTP status code validation
* Response body validation
* Response time validation
* Content-Type validation
* User data validation
* JSON response validation
* Negative testing using an invalid user ID

## Overall Result

All six API requests were successfully executed in Postman.

All 18 automated tests passed with a 100% pass rate.

No test failures were observed during this execution.

