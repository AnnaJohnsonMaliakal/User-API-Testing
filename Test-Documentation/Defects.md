# Defect Documentation

## Overview

This document describes how API defects would be recorded and tracked when a test does not produce the expected result.

No defects were identified during the current test execution. All 18 automated tests passed.

## Defect Reporting Example

The following is an example of how an API defect would be documented if the response returned an incorrect status code.

### DEF-001 — Incorrect Status Code for Invalid User

**Severity:** Medium

**Priority:** Medium

**Status:** Example / Not a real defect

**Test Case:** TC006 – Get invalid user

**API Request:**

`GET /users/9999`

**Expected Result:**

The API should return HTTP status code `404 Not Found`.

**Actual Result:**

Example: The API returned HTTP status code `200 OK`.

**Steps to Reproduce:**

1. Open Postman.
2. Open the User API Testing collection.
3. Select the Get Invalid User request.
4. Send the GET request.
5. Check the HTTP response status code.

**Expected:**

`404 Not Found`

**Actual:**

`200 OK`

**Impact:**

Returning a successful status code for a non-existent user could incorrectly indicate that the requested resource exists.

**Evidence:**

Postman response and test execution results would be attached to the defect in a real project.

## Current Test Execution

The current API test execution identified:

* Total tests: 18
* Passed: 18
* Failed: 0
* Actual defects identified: 0

The defect above is included only as an example to demonstrate the defect reporting process.
