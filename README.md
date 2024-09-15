# E-commerce System Manual Testing Project

This project focuses on manually testing an **E-commerce System** to ensure the website's core functionalities work as expected. The project includes testing all major modules, such as user authentication, product search, shopping cart, and the checkout process.

## Project Objective

The main goal of this project is to perform comprehensive manual testing on the e-commerce platform, identifying any bugs and ensuring that the system operates smoothly for users. Key testing types include:

- **Functional Testing**
- **Regression Testing**
- **Smoke Testing**
- **Usability Testing**

## Scope of Testing

### Key Modules

1. **User Authentication**:
   - Testing registration, login, and logout functionality.
   - Verify password reset and email verification processes.

2. **Product Search**:
   - Search for products using keywords and categories.
   - Validate filters (price, brand, ratings, etc.) work correctly.

3. **Shopping Cart**:
   - Add/remove products to/from the shopping cart.
   - Verify cart updates (product count, total price).

4. **Checkout Process**:
   - Validate the entire checkout flow (address selection, payment options, order summary).
   - Test integration with the payment gateway.
   - Verify the receipt is generated after a successful purchase.

5. **Order History**:
   - View order history and details for past orders.
   - Ensure correct display of order status (e.g., processing, shipped, delivered).

6. **Security Testing**:
   - Check the website for vulnerabilities (SQL Injection, Cross-Site Scripting).
   - Verify secure payment handling and data encryption.

## Test Case Example

Below is a sample test case format for testing the login functionality:

| Test Case ID | Test Case Description   | Pre-condition | Test Steps                                 | Expected Result                | Actual Result                | Status |
|--------------|-------------------------|---------------|--------------------------------------------|--------------------------------|--------------------------------|--------|
| TC-001       | Verify login functionality | User is on the login page | 1. Enter valid username and password<br>2. Click the "Login" button | User is successfully logged in | As expected | Pass |
| TC-002       | Invalid login attempt    | User is on the login page | 1. Enter invalid credentials<br>2. Click the "Login" button | Error message is displayed     | As expected | Pass |

## Tools Used

- **Test Case Management**: Microsoft Excel or Google Sheets to document test cases.
- **Bug Tracking**: Jira or Bugzilla to log and track defects.
- **Documentation**: Google Docs/Word for maintaining test plans and reports.

## Reporting

At the end of testing, the following documents will be generated:
- **Test Execution Report**: Contains details on passed and failed test cases.
- **Bug Report**: Lists all identified defects with steps to reproduce, severity, and priority.

## How to Run Tests

1. **Test Execution**:
   - Open the e-commerce system in a web browser.
   - Execute test cases step by step.
   - Log any issues found during testing into the bug tracking tool.
   
2. **Test Completion**:
   - Ensure all critical test cases have been executed.
   - Re-run failed test cases after bug fixes to confirm resolution.

## How to Contribute

If you want to contribute to this project:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/manual-testing`).
3. Commit your changes (`git commit -m 'Added new test cases'`).
4. Push to the branch (`git push origin feature/manual-testing`).
5. Open a Pull Request.



---

**Happy Testing!**
