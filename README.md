# Restful Booker API Testing with Postman, Newman, and Jenkins CI/CD

![Postman]([https://img.shields.io/badge/Postman-Collection-brightgreen](https://user-images.githubusercontent.com/25181517/192109061-e138ca71-337c-4019-8d42-4792fdaa7128.png))
![Newman](https://img.shields.io/badge/Newman-Command_Line-brightgreen)
![Jenkins]([https://img.shields.io/badge/Jenkins-CI/CD-brightgreen](https://user-images.githubusercontent.com/25181517/179090274-733373ef-3b59-4f28-9ecb-244bea700932.png))

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
- Test cases covering various endpoints, HTTP methods, and scenarios.
- Exported Postman collection for manual testing and integration into CI/CD pipelines.
- Automation of API testing through Jenkins.
- Continuous integration (CI) and continuous delivery (CD) setup instructions.

## Prerequisites
Before you begin, ensure you have met the following requirements:

- **Postman**: You need to have Postman installed. If you don't have it, you can download it from [Postman Downloads](https://www.postman.com/downloads/).

- **Newman**: You can install Newman using Node.js. Make sure you have Node.js installed, and then run the following command:

  ```bash
  npm install -g newman
