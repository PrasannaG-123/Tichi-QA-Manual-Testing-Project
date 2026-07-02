# Tichi QA Testing Project

## Project Overview

This project was completed as part of the QA Testing assignment for the Tichi Web Application.

The objective of this project was to perform complete manual testing of the application, identify functional defects, document test cases professionally, perform exploratory testing across multiple modules, and implement basic automation testing using Selenium.

The project demonstrates practical software testing skills including test case design, bug reporting, exploratory testing, documentation, automation testing, and version control using GitHub.

---

## Project Objectives

The main objectives of this project were:

- Perform Manual Testing on major application modules
- Design and execute Login and Signup test cases
- Perform Exploratory Testing on multiple application workflows
- Identify real application bugs and document them professionally
- Capture screenshots as testing evidence
- Implement Selenium Automation Testing (Optional Task)
- Organize all documentation in a professional GitHub repository

---

## Modules Tested

The following modules were tested during the project:

### Authentication Module

- Login Page Testing
- Signup Page Testing
- Logout Testing
- Session Termination Testing
- Invalid Credentials Validation
- Empty Field Validation
- Email Validation
- Password Validation

### Search Module

Tested application search functionality with multiple inputs:

- Normal keyword search
- Empty search input
- Special character search
- Long text input testing
- Sorting functionality validation

### Job Request Workflow

- Opening job cards
- Navigating to job detail page
- Request button workflow
- Profile completion requirement validation

### Profile Module

- Profile update validation testing
- Mandatory field validation checking
- Save button behavior testing

### User Activity Modules

- My Requests
- My Posts
- History
- Reviews

### Subscription Module

- Subscription page loading
- Standalone Plan testing
- Subscription Plan testing
- Buy Now purchase workflow testing

### Help & Support Module

- Help & Support page validation
- FAQ dropdown functionality testing

---

## Manual Testing Performed

### Login Test Cases

Executed test cases including:

- Valid Login
- Invalid Password
- Invalid Email
- Invalid Credentials
- Empty Fields Validation
- Password Required Validation
- Email Required Validation
- Logout Functionality
- Session Termination Validation

### Signup Test Cases

Executed test cases including:

- Empty First Name
- Long First Name Validation
- Empty Mobile Number
- Invalid Mobile Number
- Less Than 10 Digits
- More Than 10 Digits
- Special Characters in Mobile Number
- Empty Password
- Weak Password
- Long Password
- Password Mismatch
- Matching Password Validation
- Checkbox Validation
- Submit Empty Form Validation

---

## Exploratory Testing

A complete exploratory testing session was performed on the Tichi Application.

Total exploratory scenarios executed:

- Search functionality testing
- Profile workflow testing
- Requests and Posts testing
- History and Reviews testing
- Subscription workflow testing
- Help & Support testing

Total exploratory test scenarios executed:

**17 Test Scenarios**

---

## Bugs Identified

During testing, real defects were discovered.

### BUG001 — Profile Validation Inconsistency

Description:

While saving profile details, the application displayed validation message stating First Name is required even though the First Name field already contained valid data.

Expected Result:

Only empty fields should be shown in validation.

Actual Result:

System incorrectly marked First Name as required.

Severity:

Medium

Status:

Open

---

### BUG002 — Subscription Purchase Workflow Failure

Description:

When clicking Buy Now on all available subscription plans, the application displayed an error popup.

Error Message:

"Uh! oh! Something went wrong"

Expected Result:

Payment or subscription purchase workflow should open successfully.

Actual Result:

Purchase workflow failed for every available plan.

Severity:

Critical

Status:

Open

---

## Automation Testing

Basic Selenium Automation Testing was implemented using Python.

Automated Scenario:

### Invalid Login Workflow Automation

Automation Flow:

1. Open Tichi Application
2. Navigate to Sign In page
3. Enter invalid email
4. Click Continue button
5. Validate login workflow response

---

## Tools & Technologies Used

### Manual Testing

- Functional Testing
- Exploratory Testing
- Validation Testing
- Defect Identification

### Documentation

- Microsoft Excel
- Test Case Documentation
- Bug Report Documentation

### Automation Testing

- Python
- Selenium WebDriver
- Chrome Browser

### Version Control

- Git
- GitHub

---

## Project Folder Structure

```text
Tichi-QA-Testing-Project
│
├── README.md
│
├── Testcases
│   ├── TestCases.xlsx
│   ├── Exploratory_Testing.xlsx
│   └── Bug_Report.xlsx
│
├── Screenshots
│   ├── Login Screenshots
│   ├── Signup Screenshots
│   ├── Bug Evidence Screenshots
│   └── Automation Execution Screenshot
│
└── Automation
    ├── test_login.py
    ├── requirements.txt
    └── README_Automation.md
```

---

## Skills Demonstrated

This project demonstrates practical understanding of:

- Software Testing Life Cycle (STLC)
- Manual Testing
- Functional Testing
- Exploratory Testing
- Test Case Design
- Bug Reporting
- Selenium Automation Testing
- GitHub Repository Management
- QA Documentation Standards

---

## Project Status

Project Completion Status:

**Completed Successfully**

Coverage Achieved:

- Manual Testing — Completed
- Test Case Documentation — Completed
- Bug Reporting — Completed
- Exploratory Testing — Completed
- Automation Testing — Completed
- GitHub Documentation — Completed

---

## Final Outcome

Successfully completed end-to-end QA testing of Tichi Web Application including manual testing, exploratory testing, bug identification, documentation, and automation testing.

This project reflects real-world software testing workflow followed in QA Engineering.

---

## Author

Prasanna G

QA Testing Project Submission