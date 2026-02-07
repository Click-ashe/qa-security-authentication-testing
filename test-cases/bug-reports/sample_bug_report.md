# Bug Report: Login Error Message Reveals Too Much Information

## Summary
When a user enters an incorrect password, the application displays a detailed error message indicating that the username exists but the password is incorrect.

## Environment
- Browser: Chrome
- Operating System: Windows
- Test Type: Manual Testing

## Steps to Reproduce
1. Navigate to the login page
2. Enter a valid username
3. Enter an incorrect password
4. Click the login button

## Expected Result
The application should display a generic error message such as "Invalid username or password."

## Actual Result
The application displays a specific message indicating that the username exists but the password is incorrect.

## Severity
Medium

## Impact
This behavior can help attackers confirm valid usernames, increasing the risk of brute-force or credential-stuffing attacks.
