# Tichi Application – Manual QA Testing Project

## Project Overview

This project involves end-to-end manual testing of the Tichi web application as part of a Quality Assurance (QA) testing assignment.

The objective was to validate the application’s authentication flow, functional workflows, UI behavior, navigation flow, input validations, and identify defects through exploratory testing.

The testing process was performed using a real-world QA testing approach focusing on functionality, usability, validation checks, negative testing, and defect reporting.

---

## Application Tested

**Application Name:** Tichi Web Application  
**Testing Date:** 01-07-2026  
**Testing Type:** Manual Testing

---

## Scope of Testing

The following modules were tested:

- Login Authentication
- Signup / Registration Flow
- Search Functionality
- Job Detail Navigation
- Request Workflow
- Profile Update Module
- My Requests Section
- My Posts Section
- History Section
- Reviews Section
- Subscription Plans
- Standalone Purchase Plans
- Help & Support Section
- FAQ Expand / Collapse Functionality

---

## Testing Types Performed

### Functional Testing

Tested whether application features worked according to expected business behavior.

Examples:

- Valid login
- Successful profile update
- Job search functionality
- Navigation between modules

---

### Negative Testing

Tested invalid and unexpected inputs.

Examples:

- Empty login fields
- Invalid email format
- Wrong password
- Password mismatch
- Invalid mobile number
- Special characters in input fields

---

### Validation Testing

Verified form validation logic.

Examples:

- Empty required fields
- Password validation
- Confirm password validation
- Signup checkbox validation

---

### Exploratory Testing

Performed additional testing beyond initial requirements to evaluate application stability.

Modules explored:

- Subscription purchase workflow
- Requests
- Posts
- History
- Reviews
- Help & Support

---

## Test Cases Executed

### Login Test Cases

- Logout functionality
- Session termination after logout
- Empty field validation
- Invalid password validation
- Invalid email validation
- Password required validation
- Email required validation
- Successful login verification

Total Login Test Cases: **10**

---

### Signup Test Cases

- Empty First Name
- Mobile number validation
- Password strength validation
- Confirm password mismatch
- Checkbox validation
- Empty form validation
- Long input testing

Total Signup Test Cases: **17**

---

## Defects Identified

### BUG001 – Profile Validation Inconsistency

**Module:** Profile

Issue:

Application displayed validation message:

"First Name, About Me, and Profile Headline are required"

Even though First Name field already contained valid data.

**Severity:** Medium

---

### BUG002 – Subscription Purchase Failure

**Module:** Subscription Plans

Issue:

Clicking **Buy Now** on both Subscription Plans and Standalone Plans triggered popup error:

"Uh! oh! Something went wrong"

Purchase workflow failed for all plans.

**Severity:** Critical

---

## Exploratory Testing Summary

Total Modules Tested: **10+**

Modules Verified:

- Search
- Profile
- Requests
- Posts
- History
- Reviews
- Subscription Plans
- Help & Support
- FAQ Dropdown Functionality

---

## Test Execution Summary

Total Test Cases Designed: **27**

Passed: **25**

Failed / Defects Found: **2**

Critical Bugs: **1**

Medium Severity Bugs: **1**

---

## Skills Applied

- Manual Testing
- Functional Testing
- Validation Testing
- Exploratory Testing
- Negative Testing
- Bug Reporting
- UI Testing
- Test Case Design
- QA Documentation

---

## Deliverables

Project includes:

- Login Test Case Documentation
- Signup Test Case Documentation
- Bug Report Documentation
- Exploratory Testing Report
- Screenshots of Defects Found

---

## Conclusion

The Tichi web application was tested successfully across authentication, navigation, validation, and subscription modules.

The application core functionality was operational, however critical defects were identified in subscription purchase workflow and profile validation logic.

This testing project demonstrates practical QA engineering workflow involving test design, execution, defect identification, and professional reporting.

---
