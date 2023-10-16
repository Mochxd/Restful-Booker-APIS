# Restful Booker API Testing with Postman, Newman, and Jenkins CI/CD

![Postman](https://img.shields.io/badge/Postman-Collection-brightgreen)
![Newman](https://img.shields.io/badge/Newman-Command_Line-brightgreen)
![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-brightgreen)

This repository contains automated API tests for the Restful Booker API, utilizing Postman collections and Newman for test execution. Additionally, it incorporates Jenkins for continuous integration and continuous delivery (CI/CD) to automate the testing process. The Restful Booker API is a sample API for testing and learning purposes. The test Modules covers a variety of endpoints and tests to ensure the API's functionality and reliability.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Test Tasks](#test-Tasks)
- [Generating HTML Reports](#generating-html-reports)
- [Jenkins CI/CD](#jenkins-ci-cd)
- [Project Structure](#Project-Structure)
- [Contact](#Contact)

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
2. Import the Postman collection.
3. Configure the environment variables using the Postman environment "Bookingenvironment" directory or create your own environment file.
4. Run the API tests using Postman's collection runner.

**Running Tests via Command Line using Newman**

- You can also run the tests via the command line using Newman. Use the following command to run a specific test suite, specifying the environment:
  
  ```bash
  newman run BookingAPIS.json -e Bookingenvironment.json -r htmlextra

## Test Tasks
**The tests are organized into collections within Postman, each focusing on specific API tasks:**

**- CREATE Token:** Test Task for creating an authentication token.

**- GET ALL Booking ID:** Test Task for retrieving all booking IDs.

**- CREATE Booking:** Test Task for creating a new booking.

**- GET Details For Booking ID:** **Test Task for retrieving details of a specific booking ID.

**- UPDATE Booking**: Test Task for updating an existing booking.

**- UPDATE Booking Partially:** Test Task for partially updating an existing booking.

**- DELETE Booking:** Test Task for deleting a booking.

**- Ping - HealthCheck:** Test Task for checking the API's health status.

- For more details on the test scenarios, expected outcomes, and specific requests you will find it in the Google sheets.

## Generating HTML Reports
Newman supports multiple reporters, including htmlextra, which generates detailed HTML reports for your API test runs. To generate HTML reports, simply specify the -r htmlextra option when running Newman, as shown in the example above.

The HTML reports will be available in the reports directory of this repository.

## Jenkins CI/CD
The repository is configured to automate the API testing process using Jenkins for CI/CD. Jenkins pipelines are set up to trigger API tests when changes are pushed to the repository. Jenkins will run the tests, generate HTML reports, and provide feedback on the test results.

## Project Structure

- 📦 Restful Booker API
- ├── 📂 api-tests in Postman
- │   ├── 📜 CreateToken
- │   ├── 📜 GetAllBookingID
- │   ├── 📜 CreateBooking
- │   ├── 📜 GetDetailsForBookingID
- │   ├── 📜 UpdateBooking
- │   ├── 📜 UpdateBookingPartially
- │   └── 📜 DeleteBooking
- ├── 📂 environments
- │   └── 📜 Bookingenvironment.json
- ├── 📂 Tests
- │   └── 📜 Manual Test Cases
- ├── 📂 reports
- │   ├── 📜 Newman HTMLEXTRA.html
- │   └── 📜 Newman HTML.html

## Contact

If you have any questions, suggestions, or issues related to this project, please feel free to contact us. We welcome your feedback and contributions.
- **Email**: Mohamedbadrxd@email.com

Feel free to open an issue in this repository or reach out to me directly. I appreciate your interest and support!
