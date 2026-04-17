# Postman API Testing Project

This repository contains curated API testing scenarios built with Postman, including functional validation, negative testing, authentication checks, CRUD operations, and response performance validation.

## Collections Included

* ReqRes API Functional Tests
* Library API Functional Tests
* Basic Response Validation Tests

## Testing Coverage

* HTTP status code validation
* Response body verification
* Response time checks
* Authentication testing
* CRUD request practice
* Edge case validation

## Tools Used

* Postman
* JavaScript test scripts
* JSON collections

## Example Validations Included

* Verify response status equals expected code
* Validate response time threshold
* Check required response fields
* Verify authentication behaviour

## Sample Test Assertion

pm.test("Response status is 200", function () {
pm.response.to.have.status(200);
});

## Purpose

This project reflects hands-on QA practice focused on API validation, functional testing, and response analysis aligned with junior software testing responsibilities.
