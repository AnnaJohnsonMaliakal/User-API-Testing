# Test Execution Report

## Overview

The User API collection was executed in Postman to verify the API requests and response validations.

## Test Environment

* Tool: Postman
* API: JSONPlaceholder
* Environment: Test
* Test Type: API Testing

## Execution Results

| Test Case ID | Test Scenario     | Method | Expected Result | Result |
| ------------ | ----------------- | ------ | --------------- | ------ |
| TC001        | Get all users     | GET    | Status code 200 | PASS   |
| TC002        | Get user by ID    | GET    | Status code 200 | PASS   |
| TC003        | Create a new user | POST   | Status code 201 | PASS   |
| TC004        | Update a user     | PUT    | Status code 200 | PASS   |
| TC005        | Delete a user     | DELETE | Status code 200 | PASS   |
| TC006        | Get invalid user  | GET    | Status code 404 | PASS   |

## Validations Performed

* HTTP status code validation
* Response body validation
* Response time validation
* Content-Type validation
* User data validation
* Negative testing for an invalid user

## Overall Result

All planned test scenarios passed successfully during execution.
