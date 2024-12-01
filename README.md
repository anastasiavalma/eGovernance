# Dialog System for  Certification Issuance

## Overview
This project focuses on developing a web-based dialog system that facilitates communication between public services and citizens. It informs citizens about their eligibility for a specific public service and provides details about the required documentation.
## Features
### 1. Interactive Dialog Flow
A questionnaire consisting of 5 questions to assess the citizen's eligibility for public services and identify the necessary documents to complete the process.
### 2. FAQ Section
A comprehensive FAQ section offering additional details about the public service.
### 3. Eligibility Information
The system verifies if users meet the necessary requirements to receive the certificate.
### 4. Multilingual Support
The system supports multiple languages, including English and Greek, for broader accessibility.
### 5.  User Privacy Assurance
User responses are not stored or shared, ensuring full privacy and security.
### 6. Ease of Use
Designed for simplicity, the user interface allows quick and efficient interaction, with most tasks completed in under 10 minutes.
### 7. Online Deployment
The service is deployed online for easy and widespread access.

### 8. Source Code Availability
The source code is available under an open-source license and can be accessed through this repository.
## How to use the Service
### 1. Online Service
The dialog system is deployed online. Access it [here](https://anastasiavalma.github.io/eGovernance/).

### 2. GitHub Repository
You can view and contribute to the source code in the repository: [Repository Link](https://github.com/govgr-mobility-card/ps-info-template/).

## Navigating the Project

The project structure is as follows:

```sh
project
│
├── index.html # Main HTML file
├── styles.css # Custom CSS styles
├── js/
│ ├── jquery-functions.js # Custom jQuery functions to fetch Questions, Evidences, FAQs and to handle answers in the questionnaire
│ └── change-language-functions.js # Language switch functions
├── questions-utils/
│ ├── all-questions-en.json # has all questions&answers in english
│ ├── all-questions.json # has all questions&answers in greek
│ ├── cpsv-en.json # has all Evidences in english
│ ├── cpsv.json # has all Evidences in greek
│ ├── faq-en.json # has all FAQs questions&answers in english
│ ├── faq.json # has all FAQs questions&answers in greek
└── README.md # Project documentation
```
### Template Reference:
The system's design draws inspiration from a case study example, which you can explore [here](https://govgr-mobility-card.github.io/info-for-mobility-card-gr/).

