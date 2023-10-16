# Restful Booker API Testing with Postman, Newman, and Jenkins CI/CD

![Postman](https://img.shields.io/badge/Postman-Collection-brightgreen)
![Newman](https://img.shields.io/badge/Newman-Command_Line-brightgreen)
![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-brightgreen)

This repository contains automated API tests for the Restful Booker API, utilizing Postman collections and Newman for test execution. Additionally, it incorporates Jenkins for continuous integration and continuous delivery (CI/CD) to automate the testing process. The Restful Booker API is a sample API for testing and learning purposes. The test suite covers a variety of endpoints and scenarios to ensure the API's functionality and reliability.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Test Suites](#test-suites)
- [Generating HTML Reports](#generating-html-reports)
- [Jenkins CI/CD](#jenkins-ci-cd)
- [Contributing](#contributing)
- [License](#license)

## Features
- Detailed and organized API test suites.
- Test cases covering various endpoints, HTTP methods, and scenarios using Google sheets.
- Exported Postman collection for manual testing and integration into CI/CD pipelines.
- Automation of API testing through cmd and Jenkins.
- Continuous integration (CI) and continuous delivery (CD) setup instructions.

## Prerequisites
Before you begin, ensure you have met the following requirements:

- **Postman**: You need to have Postman installed. If you don't have it, you can download it from [Postman Downloads](https://www.postman.com/downloads/).

- **Newman**: You can install Newman using Node.js. Make sure you have Node.js installed, and then run the following command:

  ```bash
  npm install -g newman

- **Jenkins**: You will need a Jenkins server set up for CI/CD automation. You can install Jenkins following the instructions on the Jenkins website.

## Installation

- Clone this repository to your local machine:

  ```bash
  git clone https://github.com/Mochxd/Restful-Booker-APIS.git

- Navigate to the project directory:

  ```bash
  cd Restful-Booker-APIS

- Install the project dependencies:

  ```bash
  npm install


## Usage

**Running Tests in Postman**
1. Open Postman.
2. Import the Postman collection located in the api-tests/collections directory.
3. Configure the environment variables using the Postman environment files in the api-tests/environments directory or create your own environment file.
4. Run the API tests using Postman's collection runner.

**Running Tests via Command Line using Newman**

- You can also run the tests via the command line using Newman. Use the following command to run a specific test suite, specifying the environment:
  
  ```bash
  newman run BookingAPIS.json -e Bookingenvironment.json -r htmlextra

## Test Suites
**The tests are organized into collections within Postman, each focusing on specific API tasks:**

- CREATE Token: Test suite for creating an authentication token.

- GET ALL Booking ID: Test suite for retrieving all booking IDs.

- CREATE Booking: Test suite for creating a new booking.

- GET Details For Booking ID: Test suite for retrieving details of a specific booking ID.

- UPDATE Booking: Test suite for updating an existing booking.

- UPDATE Booking Partially: Test suite for partially updating an existing booking.

- DELETE Booking: Test suite for deleting a booking.

- Ping - HealthCheck: Test suite for checking the API's health status.

- For more details on the test scenarios, expected outcomes, and specific requests, refer to the descriptions and comments provided within the Postman collections.
