# -Postman-API-Testing-Pet-Store-API-Playground

This document serves as a short guide to my Postman collection designed for testing the Swagger Pet Store API playground. The goal of this project was to ensure the reliability of various API endpoints, which enable the following key functionalities:
- Creation of new pet profiles;
- Updating existing pet profiles;
- Retrieving all existing profiles based on a specific tag;
- Deletion of pet profiles.

To guarantee the accuracy of the results, I have incorporated a series of tests with each request. These tests are designed to confirm the following:
- The API returns the correct HTTP status code for each call, indicating either successful execution or an error, as applicable.
- The response time for each request is within acceptable limits (in case of this collection, defined as 800ms), ensuring the efficient performance of the API.
- The response body contains the expected data, validating that the API's output aligns with the expected results.

For the purpose of these tests, I have assumed that the 'petID' parameter is a unique identifier that is automatically generated for each pet profile. This allowed me to incorporate the use of a dynamic variable to capture and handle this 'petID' in my collection of calls.
