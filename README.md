# api-test-petstore
This example project aims to provide test coverage for the [Swagger Pet Store API](https://petstore.swagger.io/), using Postman/Newman as a test automation framework and Continuous Integration.

#Pre-requisites
- Having a www.postman.com registered user account


# Usage

## Command line
1. Clone this repository
2. Install [Newman](https://github.com/postmanlabs/newman)
3. From the project root, execute the command: `$ newman run ./tests/TestingFlowSwaggerPetStore.postman_collection.json`

## Via Postman
Clone the repository or download the `TestingFlowSwaggerPetStore.postman_collection.json` file and [import it from Postman](https://learning.postman.com/docs/getting-started/importing-and-exporting-data/).
