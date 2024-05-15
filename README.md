<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-commerce Website Testing</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1, h2, h3 {
            color: #333;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        ul {
            list-style-type: disc;
            margin: 0;
            padding: 0;
            padding-left: 20px;
        }
    </style>
</head>
<body>

    <h1>E-commerce Website Testing</h1>

    <h2>Introduction</h2>
    <p>This document delineates the test strategy for performing manual testing on an e-commerce platform. The aim of this test strategy is to establish the approach, boundaries, goals, resources, timeline, and outcomes of the testing procedures.</p>

    <h2>Test Objectives</h2>
    <p>The primary objective of this testing effort is to ensure the functionality, usability, and robustness of key features on the e-commerce website, including:</p>
    <ul>
        <li>User authentication (sign in, login, password reset)</li>
        <li>Account creation</li>
        <li>Product search, filtering, and sorting</li>
        <li>Cart operations (add, remove, update quantity)</li>
        <li>Checkout process (valid and invalid payment scenarios, address management)</li>
        <li>Order history and account management</li>
    </ul>

    <h2>Scope</h2>
    <p>The scope of this test plan includes the following features:</p>
    <ul>
        <li><strong>User Authentication:</strong> Sign in, login, and password reset functionalities.</li>
        <li><strong>Account Creation:</strong> Valid and invalid account creation scenarios.</li>
        <li><strong>Product Search:</strong> Search functionality using various criteria.</li>
        <li><strong>Product Filtering and Sorting:</strong> Filtering and sorting products by different parameters (e.g., color, price, popularity).</li>
        <li><strong>Cart Operations:</strong> Adding items to the cart, removing items from the cart, and updating item quantities.</li>
        <li><strong>Checkout Process:</strong> Payment processing with valid and invalid details, address management.</li>
        <li><strong>Order History and Account Management:</strong> Viewing order history, managing personal information, and address book.</li>
    </ul>

    <h2>Test Strategy</h2>
    <p>The testing strategy involves:</p>
    <ul>
        <li>Designing and executing manual test cases for each feature.</li>
        <li>Reporting bugs and tracking issues using JIRA.</li>
        <li>Re-testing resolved issues to ensure fixes are effective.</li>
    </ul>

    <h2>Test Environment</h2>
    <p>The testing will be conducted in a staging environment that mirrors the production environment as closely as possible. The environment will include:</p>
    <ul>
        <li><strong>Web browsers:</strong> Chrome, Firefox, Edge</li>
        <li><strong>Operating systems:</strong> Windows 10</li>
    </ul>

    <h2>Test Deliverables</h2>
    <p>The deliverables for this testing effort include:</p>
    <ul>
        <li>Test Plan Document</li>
        <li>Test Cases Document</li>
    </ul>

    <h2>Schedule</h2>
    <p>The testing schedule is as follows:</p>
    <table>
        <thead>
            <tr>
                <th>Activity</th>
                <th>Start Date</th>
                <th>End Date</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Test Planning</td>
                <td>May 3, 2024</td>
                <td>May 4, 2024</td>
            </tr>
            <tr>
                <td>Test Case Design</td>
                <td>May 5, 2024</td>
                <td>May 7, 2024</td>
            </tr>
            <tr>
                <td>Test Environment Setup</td>
                <td>May 8, 2024</td>
                <td>May 9, 2024</td>
            </tr>
            <tr>
                <td>Test Execution</td>
                <td>May 10, 2024</td>
                <td>May 16, 2024</td>
            </tr>
            <tr>
                <td>Bug Reporting and Tracking</td>
                <td>May 17, 2024</td>
                <td>May 17, 2024</td>
            </tr>
            <tr>
                <td>Test Summary Report Creation</td>
                <td>May 18, 2024</td>
                <td>June 19, 2024</td>
            </tr>
        </tbody>
    </table>

    <h2>Test Cases</h2>
    <p>The test cases will cover the following scenarios:</p>
    <table>
        <thead>
            <tr>
                <th>Test Case ID</th>
                <th>Test Case Title</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>TC001</td>
                <td>Verify sign in and login page elements</td>
                <td>Ensure all necessary elements are present on the sign-in and login page</td>
            </tr>
            <tr>
                <td>TC002</td>
                <td>Create Account with invalid Email ID</td>
                <td>Test account creation with an invalid email ID.</td>
            </tr>
            <tr>
                <td>TC003</td>
                <td>Product Search</td>
                <td>Verify product search functionality using different criteria</td>
            </tr>
            <tr>
                <td>TC004</td>
                <td>Product Filtering by Color</td>
                <td>Test product filtering functionality by color</td>
            </tr>
            <tr>
                <td>TC005</td>
                <td>Product Sorting by Price</td>
                <td>Verify product sorting functionality by price.</td>
            </tr>
            <tr>
                <td>TC006</td>
                <td>Add Item to Cart</td>
                <td>Test adding items to the cart</td>
            </tr>
            <tr>
                <td>TC007</td>
                <td>Remove Item from Cart</td>
                <td>Test removing items from the cart.</td>
            </tr>
            <tr>
                <td>TC008</td>
                <td>Update Item Quantity in Cart</td>
                <td>Test updating item quantities in the cart.</td>
            </tr>
            <tr>
                <td>TC009</td>
                <td>Valid Payment Details</td>
                <td>Verify checkout process with valid payment details.</td>
            </tr>
            <tr>
                <td>TC010</td>
                <td>Invalid Payment Details</td>
                <td>Verify checkout process with invalid payment details</td>
            </tr>
            <tr>
                <td>TC011</td>
                <td>Address Management</td>
                <td>Test adding, editing, and deleting addresses.</td>
            </tr>
            <tr>
                <td>TC012</td>
                <td>Order History</td>
                <td>Verify that users can view their order history.</td>
            </tr>
            <tr>
                <td>TC013</td>
                <td>View Specific Order Details</td>
                <td>Verify that users can view details of a specific order</td>
            </tr>
            <tr>
                <td>TC014</td>
                <td>Edit Personal Information</td>
                <td>Test editing personal information and ensure required fields validation.</td>
            </tr>
            <tr>
                <td>TC015</td>
                <td>Logout</td>
                <td>Verify successful logout and session handling.</td>
            </tr>
        </tbody>
    </table>

    <h2>Bug Reporting</h2>
    <p>All bugs identified during testing will be reported in JIRA, following the format:</p>
    <ul>
        <li>Bug ID</li>
        <li>Title</li>
        <li>Description</li>
        <li>Steps to Reproduce</li>
        <li>Expected Result</li>
        <
