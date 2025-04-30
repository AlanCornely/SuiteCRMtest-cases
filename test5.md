# Delete Contact  
## Objective:  
Verify if the system completely removes a contact when the delete function is triggered.  

## Description:  
Tests the contact deletion functionality to ensure records are erased without leaving any residual data.  

## Prerequisites:  
- Admin credentials (user: `admin`, password: `admin123`)  
- Existing contact to delete (e.g., `TestUser Edited`)  
- Access to SuiteCRM at https://crm.alunostds.dev.br  
- Updated browser (Chrome, Firefox, or Edge)  

### Steps:  
1. Log in as admin to SuiteCRM  
2. Access the contact list  
3. Locate and open the contact to be deleted  
4. Click on Actions > Delete  
5. Confirm the deletion in the pop-up  
6. Verify the updated contact list  

Contact list URL:  
https://crm.alunostds.dev.br/#/contacts/index  

### Expected Result:  
The contact should be permanently removed from the system and disappear from the list.  

### Actual Result:  
Deletion completed successfully. The contact no longer appears in the list.  

### Analysis:  
Test approved - Deletion functionality works as expected.  

### Possible Errors:  
- Permission denied → Check user privileges  
- Contact reappears → Verify database synchronization  

### Evidence:  
Screenshot of the deletion confirmation  
Screenshot of the contact list after deletion  

### Settings:  
OS: Windows 11 pro
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080