# Title: Creating a New Contact
Objective:
To ensure that the Contacts module allows the creation of a new record with all required information and returns a success confirmation.

Description:
This test verifies whether the SuiteCRM system correctly accepts and saves a new contact when all mandatory fields are filled with valid data.

Prerequisites:
Access to SuiteCRM at crm.alunostds.dev.br with valid credentials.

Proper permissions to create contacts.

Supported browser (Chrome, Firefox, or Edge).

Test Procedure:
Log in to the System:

Go to crm.alunostds.dev.br.

Enter a valid username and password (e.g., "admin" / "admin123").

Click "Login".

Access the Contacts Module:

In the main menu, click "Contacts".

Select "Create Contact".

Fill in Required Fields:

First Name: "João Silva"

Last Name: "Souza"

Email: "joao.souza@example.com"

Phone: "+55 (11) 98765-4321"

Company: "Tech Solutions Ltd."

Save the Contact:

Click "Save".

Expected Result:
The system should successfully register the new contact, display a confirmation message, and redirect to the contact details page.

Actual Result:
✅ Success.

Result Analysis:
The test was successful as the system accepted the valid data, saved the contact, and displayed the correct confirmation.

Possible Errors (if applicable):
Missing required fields → The system should prevent saving until all mandatory fields are filled.

Invalid format (email, phone) → The system should display a specific error message.

Evidence:
Screenshot of the filled form.

Screenshot of the success message after saving.

Video (optional) showing the complete process.

System Specifications:
OS: Windows 10

Browser: Chrome vXX

Resolution: 1920x1080
