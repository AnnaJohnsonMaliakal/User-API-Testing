# User API Testing

## Overview

This project demonstrates API testing using Postman and a REST API. The project covers basic CRUD operations and includes both positive and negative test scenarios.

## Tools Used

* Postman
* GitHub
* REST API
* JSON
* JavaScript for Postman test scripts

## API Operations Tested

| Method | Test              |
| ------ | ----------------- |
| GET    | Get all users     |
| GET    | Get user by ID    |
| POST   | Create a new user |
| PUT    | Update a user     |
| DELETE | Delete a user     |

## Testing Performed

* Status code validation
* Response body validation
* Response time validation
* Content-Type validation
* Positive testing
* Negative testing
* JSON response validation

## Test Scenarios

The project includes the following test cases:

* TC001 – Get all users
* TC002 – Get user by ID
* TC003 – Create a new user
* TC004 – Update a user
* TC005 – Delete a user
* TC006 – Get invalid user

## Project Structure

```text
User-API-Testing
│
├── Test-Documentation
│   └── Test-Cases.md
│
├── README.md
│
└── User API Testing.postman_collection.json
```

## API Used

JSONPlaceholder was used as a public API for learning and testing purposes.

## Purpose

The purpose of this project is to demonstrate basic API testing skills, including creating API requests, validating responses, writing Postman test scripts, and documenting test cases.
