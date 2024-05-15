# E-commerce Website Testing
## Introduction
This document delineates the test strategy for performing manual testing on an e-commerce platform. The aim of this test strategy is to establish the approach, boundaries, goals, resources, timeline, and outcomes of the testing procedures.
## Test Objectives
The primary objective of this testing effort is to ensure the functionality, usability, and robustness of key features on the e-commerce website, including:
- User authentication (sign in, login, password reset)
- Account creation
- Product search, filtering, and sorting
- Cart operations (add, remove, update quantity)
- Checkout process (valid and invalid payment scenarios, address management)
- Order history and account management
## Scope
The scope of this test plan includes the following features:
- **User Authentication**: Sign in, login, and password reset functionalities.
- **Account Creation**: Valid and invalid account creation scenarios.
- **Product Search**: Search functionality using various criteria.
- **Product Filtering and Sorting**: Filtering and sorting products by different parameters (e.g., color, price, popularity).
- **Cart Operations**: Adding items to the cart, removing items from the cart, and updating item quantities.
- **Checkout Process**: Payment processing with valid and invalid details, address management.
- **Order History and Account Management**: Viewing order history, managing personal information, and address book.
  ## Test Strategy
The testing strategy involves:
- Designing and executing manual test cases for each feature.
- Reporting bugs and tracking issues using JIRA.
- Re-testing resolved issues to ensure fixes are effective.
## Test Environment
The testing will be conducted in a staging environment that mirrors the production environment as closely as possible. The environment will include:
- **Web browsers**: Chrome, Firefox, Edge
- **Operating systems**: Windows 10
  ## Test Deliverables
The deliverables for this testing effort include:
- Test Plan Document
- Test Cases Document

## Schedule
The testing schedule is as follows:

| Activity                   | Start Date  | End Date    |
|----------------------------|-------------|-------------|
| Test Planning              | May 3, 2024 | May 4, 2024 |
| Test Case Design           | May 5, 2024 | May 7, 2024 |
| Test Environment Setup     | May 8, 2024 | May 9, 2024 |
| Test Execution             | May 10, 2024| May 16, 2024|
| Bug Reporting and Tracking | May 17, 2024| May 17, 2024|
| Test Summary Report Creation| May 18, 2024 | June 19, 2024|

## Test Cases
The test cases will cover the following scenarios:

| Test Case ID | Test Case Title                       | Description                                             |
|--------------|---------------------------------------|---------------------------------------------------------|
| TC001        | Verify sign in and login page elements | Ensure all necessary elements are present on the sign-in and login page |
| TC002        | Create Account with invalid Email ID   | Test account creation with an invalid email ID.         |
| TC003        | Product Search                        | Verify product search functionality using different criteria |
| TC004        | Product Filtering by Color            | Test product filtering functionality by color           |
| TC005        | Product Sorting by Price              | Verify product sorting functionality by price.          |
| TC006        | Add Item to Cart                      | Test adding items to the cart                           |
| TC007        | Remove Item from Cart                 | Test removing items from the cart.                      |
| TC008        | Update Item Quantity in Cart          | Test updating item quantities in the cart.              |
| TC009        | Valid Payment Details                 | Verify checkout process with valid payment details.     |
| TC010        | Invalid Payment Details               | Verify checkout process with invalid payment details    |
| TC011        | Address Management                    | Test adding, editing, and deleting addresses.           |
| TC012        | Order History                         | Verify that users can view their order history.         |
| TC013        | View Specific Order Details           | Verify that users can view details of a specific order  |
| TC014        | Edit Personal Information             | Test editing personal information and ensure required fields validation. |
| TC015        | Logout                                | Verify successful logout and session handling.          |

## Bug Reporting
All bugs identified during testing will be reported in JIRA, following the format:
- Bug ID
- Title
- Description
- Steps to Reproduce
- Expected Result
- Actual Result
- Priority
- Status

## Resources
The resources required for this testing effort include:
- Testers: 2 manual testers
- Tools: Excel/Google Sheets (for documentation)

## Entry and Exit Criteria
**Entry Criteria:**
- Test environment is set up and stable.
- Test cases are reviewed and approved.
- Access to necessary tools and data is available.

**Exit Criteria:**
- All planned test cases are executed.
- All identified bugs are reported and tracked.
- High and medium severity bugs are resolved and re-tested.
- Test summary report is created and reviewed.

## Risk and Mitigation
**Risks:**
- Delay in environment setup.
- Incomplete test cases.

**Mitigation:**
- Ensure timely communication with the environment setup team.
- Regular reviews and updates of test cases.
