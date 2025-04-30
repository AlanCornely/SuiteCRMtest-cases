# Title: Creating a New Contact
## Objective:
To ensure that the Contacts module allows the creation of a new record with all required information and returns a success confirmation.

## Description:
This test verifies whether the SuiteCRM system correctly accepts and saves a new contact when all mandatory fields are filled with valid data.

## Prerequisites:
Access to SuiteCRM at crm.alunostds.dev.br with valid credentials.

Proper permissions to create contacts.

Supported browser (Chrome, Firefox, or Edge).

### Test Procedure:
1. Log in to SuiteCRM.
2. From the top navigation menu, go to Contacts and Create Contact.
3. The app redirects to the URL: https://crm.alunostds.dev.br/#/contacts/edit?return_module=Contacts&return_action=DetailView
4. Fill in the necessary details for the new contact.
5. Only the Last Name field is required; other fields may be left blank.
6. Click the Save button to create the contact.
7. Verify if the contact was created and appears in the contacts list or details view.

### Expected Result:
 The system should successfully register the new contact, display a confirmation message, and redirect to the contact details page.

### Actual Result:
 Success.

### Result Analysis:
The test was successful as the system accepted the valid data, saved the contact, and displayed the correct confirmation.

## Possible Errors (if applicable):
Missing required fields → The system should prevent saving until all mandatory fields are filled.

Invalid format (email, phone) → The system should display a specific error message.

# Evidence:
Screenshot of the filled form.

Screenshot of the success message after saving.

Video (optional) showing the complete process.

System Specifications:
OS: Windows 10

Browser: Chrome vXX

Resolution: 1920x1080
