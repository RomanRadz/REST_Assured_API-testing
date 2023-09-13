# Online Store API Testing with Rest Assured

## Overview

Welcome to the repository for API testing of an online store using Rest Assured. This project is dedicated to ensuring the quality and reliability of various e-commerce functionalities through automated API testing.

## Project Structure

The project structure is organized as follows:

- `src/main/java`: Contains the main source code for the API testing framework.
  - `models`: Includes model classes such as `Product.java`.
  - `trainingxyz`: Holds the main test class `ApiTests.java`.
- `src/test/resources`: Contains testing-related resource files.
  - `.classpath` and `.project`: Project configuration files.
  - `pom.xml`: Maven configuration file.

## Test Cases

Here are some of the test cases included in the project:

1. `getCategories`: Tests the endpoint for retrieving product categories and validates the response.
2. `getProduct`: Tests the endpoint for retrieving a product by ID and validates the response.
3. `createProduct`: Tests the endpoint for creating a new product and logs the response.
4. `updateProduct`: Tests the endpoint for updating a product and logs the response.
5. `deleteProduct`: Tests the endpoint for deleting a product and logs the response.
6. `createSerializedProduct`: Tests the endpoint for creating a new product using a serialized object.
7. `createSweatband`: Tests the endpoint for creating a sweatband product and logs the response.
8. `updateSweatBand`: Tests the endpoint for updating a sweatband product and logs the response.
9. `getSweatband`: Tests the endpoint for retrieving a sweatband product by ID and logs the response.
10. `deleteSweatband`: Tests the endpoint for deleting a sweatband product and logs the response.
11. `getProducts`: Tests the endpoint for retrieving all products and validates the response.
12. `getDeserializedProduct`: Tests the endpoint for retrieving a product and deserializes the response into an object.
13. `getMultiVitamins`: Tests the endpoint for retrieving multi-vitamins product and validates the response.

## Getting Started

To get started with this API testing framework:

1. Clone this repository to your local machine.
2. Configure the project based on your testing environment and requirements.
3. Install the necessary dependencies specified in `pom.xml` using Maven.
4. Run the desired test cases to perform API testing of the online store using Rest Assured.

## Dependencies

This project relies on the following dependencies:

- Rest Assured
- JUnit
- Gson (for deserialization)
- Maven

## Contributing

Contributions to enhance the framework and test coverage are highly encouraged. If you have improvements or bug fixes to contribute, please fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.
