# 🧩 Test Cases – Login Page

| TC ID | Test Scenario | Preconditions | Test Steps | Expected Result | Status |
|-------|----------------|----------------|-------------|-----------------|---------|
| TC001 | Verify login with valid credentials | User is registered | 1. Open login page<br>2. Enter valid email<br>3. Enter valid password<br>4. Click Login | User is redirected to dashboard | ⬜ Not Executed |
| TC002 | Verify login with invalid password | User exists | Enter correct email and wrong password | Error message "Invalid credentials" is displayed | ⬜ Not Executed |
| TC003 | Check “Forgot Password” link | User is on login page | Click on "Forgot Password" link | Redirects to password recovery page | ⬜ Not Executed |
| TC004 | Check “Remember Me” function | User is on login page | Check “Remember Me” and login | User stays logged in after browser restart | ⬜ Not Executed |

