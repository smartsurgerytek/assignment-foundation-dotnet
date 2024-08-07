# Take-Home Assignment: Polly Unit Testing (.NET)

## Objective:
This assessment aims to evaluate the candidate's ability to write unit tests for a .NET application that interacts with an external RESTful API using the Polly Retry library for resilient HTTP client-side connection.

## Prerequisites

* Familiarity with C# and .NET Core
* Understanding of unit testing principles and frameworks (e.g., xUnit)
* Basic knowledge of RESTful APIs and HTTP protocols
* Experience with dependency injection and mocking frameworks (e.g., NSubstitute)

## Setup Instructions

* Fork the Polly repository on GitHub. https://github.com/App-vNext/Polly
* Clone your forked repository to your local machine.
* Open the solution in your preferred .NET IDE (e.g., Visual Studio, Visual Studio Code, or JetBrains Rider).

## Task:
Your task is to create a unit test project within the Polly solution to test the RetryPolicy class. The RetryPolicy class handles retries when making HTTP requests to an external API. Examples can be found in the repo. https://github.com/App-vNext/Polly/tree/main/test/Polly.Specs/Retry

You should write at least one unit test covering each of the scenarios below:

* Successful API Call: Test that the RetryPolicy correctly executes the provided delegate when the API call is successful without any retries.
* Retry with Exponential Backoff: Test that the RetryPolicy retries the API call with an exponential backoff strategy when the API call fails due to a transient error (e.g., network timeout, service unavailability).

Follow best practices for unit testing, including proper test naming conventions, test organization, and test isolation.

* Implement proper error handling and exception management in your tests.
* Provide clear and concise documentation for your tests, including descriptions of the scenarios being tested and any assumptions or prerequisites.
* Utilize dependency injection and mocking frameworks to isolate the RetryPolicy class from external dependencies (e.g., HTTP client, external API).
* Ensure that your tests are deterministic and can be run in any order without causing side effects.

## Evaluation Criteria: 
The candidate's submission will be evaluated based on the following criteria:

* Correctness: The unit tests accurately test the expected behavior of the RetryPolicy class.
* Code Quality: The code follows best practices for readability, maintainability, and extensibility.
* Test Coverage: The unit tests provide comprehensive coverage of the RetryPolicy class and its various scenarios.
* Error Handling: Proper error handling and exception management are implemented in the tests.
* Documentation: Clear and concise documentation is provided for the tests.

## Submission

* Deadline: Please complete the assignment and push your changes to your forked repository within 48 hours from when this assignment was given.
* Submission: Once you have completed the assignment, please send the URL of your public repository to the hiring manager: service@smartsurgerytek.com

_Good luck, and we look forward to reviewing your submission!_
