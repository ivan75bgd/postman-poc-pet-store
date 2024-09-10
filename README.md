# postman-poc-pet-store

This repository serves as a Proof of Concept (POC) to demonstrate my proficiency in writing Postman tests, managing Postman collections, and using GitHub for version control. It contains a Postman collection and environment JSON files, which can be used for API testing and automation.

## Purpose
The primary goal of this repository is to showcase my knowledge and skills in:

- Writing and structuring Postman API tests.
- Managing Postman collections and environments.
- Version control and collaboration using GitHub.
- Best practices in organizing and maintaining API tests.

## Repository Contents
- **Postman Collection**: The JSON file containing the API requests, test scripts, and pre-request scripts for the POC.
- **Postman Environment**: The environment JSON file used to store variable values for different environments (e.g., development, staging, production).

## Getting Started
To use the Postman collection and environment from this repository, follow these steps:

1. **Clone the Repository**:

```git clone https://github.com/yourusername/postman-poc.git```

2. **Import into Postman**:

- Open Postman.
- Click on "Import" at the top left of Postman.
- Select the collection and environment JSON files from the cloned repository.

3. **Set Up Environment Variables**:

- Load the environment JSON into Postman to configure environment-specific variables (e.g., base URL, tokens).
- Update any necessary values depending on the environment you're testing against.

4. **Run the Collection**:

- After importing the collection, select the environment you want to use.
- Run the collection using the Postman Collection Runner or Newman for CLI-based execution.

## Scripts and Tests
Each request within the Postman collection contains test scripts to validate API responses. These tests include:

- Status code validation.
- Schema validation.
- Response data checks.
- Custom test cases using JavaScript.
  
The collection is designed to be modular and reusable, allowing for easy modification and scaling of tests.
