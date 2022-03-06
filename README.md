# Swagger Pet Store API testing - Example test suite
This example project aims to provide test coverage for the [Swagger Pet Store API](https://petstore.swagger.io/), using Postman/Newman as a test automation framework and Continuous Integration.

# Pre-requisites
- Having a www.postman.com registered user account


# Usage

## Command line
1. Clone this repository
2. Install [Newman](https://github.com/postmanlabs/newman)
3. From the project root, execute the command: `$ newman run ./tests/TestingFlowSwaggerPetStore.postman_collection.json`

## Via Postman
Clone the repository or download the `TestingFlowSwaggerPetStore.postman_collection.json` file and [import it from Postman](https://learning.postman.com/docs/getting-started/importing-and-exporting-data/).

## Test coverage

### Data creation
Create User, Pet and Order: generates test data for the test suite execution, but also covered by tests.

### Positive tests
All endpoints contain at least two assertions, for status code and response time.

### Negative tests
Current test coverage for the following exception scenarios:
- Duplicate unique fields
- Invalid Body fields
- Missing Body fields
- Invalid Request

