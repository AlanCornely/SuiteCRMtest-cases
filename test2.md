# Title: Login Attempt with Invalid Credentials
* Description: This test verifies the behavior of the SuiteCRM login process when invalid credentials are provided.
* Objective: Confirm that the system rejects authentication of a user with invalid credentials and displays the appropriate message.
* What is being tested: The login functionality and authentication flow of the SuiteCRM system.
## Prerequisites:
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox or Edge).
## Test Procedure:
1. Access crm.alunostds.dev.br.
2. Enter the username "admin" and the password "usuario123".
3. Click the "Login" button.
4. Observe the system response.

### Expected Result:
The system should deny access, displaying an error message stating that the credentials are invalid.

### Current Result:
Denied.

### Result Analysis:
The test is considered successful if the system blocks the login and displays an appropriate error message.

### Error Description (if applicable):
N/A – Test executed successfully.

## Evidence:
Screenshot of the login page with the credentials entered.

Short video demonstrating the login attempt (if applicable).

System Specifications: Windows 10, Chrome Version XX, Screen Resolution 1920x1080.
