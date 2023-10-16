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

1- Clone this repository to your local machine:

  bash
  git clone https://github.com/Mochxd/Restful-Booker-APIS.git

2- Navigate to the project directory:

  `bash
  cd Restful-Booker-APIS

3- Install the project dependencies:

  `bash
  npm install

