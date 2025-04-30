# title: Edit Existing Contact  
## Objective:  
Verify if editing existing contacts in SuiteCRM correctly saves changes.  

## Description:  
Tests the contact editing functionality to ensure modifications are saved and displayed properly.  

## Prerequisites:  
- Admin login in SuiteCRM (user: `admin`, password: `admin123`)  
- Existing registered contact (e.g., `TestUser`)  
- Access to the URL https://crm.alunostds.dev.br  
- Updated browser (Chrome, Firefox, or Edge)  

### Steps:  
1. Log in to SuiteCRM with admin credentials  
2. Navigate to Contacts > Contact List  
3. Select an existing contact (e.g., `TestUser`)  
4. Click on Edit  
5. Change the Name field to `TestUser Edited`  
6. Click Save  
7. Verify the updated contact details  

Edit URL:  
https://crm.alunostds.dev.br/index.php?module=Contacts&action=EditView  

### Expected Result:  
The system should save the changes and display the new name on the details page.  

### Actual Result:  
Changes saved successfully. Edited name displayed correctly.  

### Analysis:  
Test approved - Editing functionality works as expected.  

### Possible Errors:  
- Edited fields do not save → Check permissions or connection  
- Data does not update → Reload the page or clear the cache  

### Evidence:  
Screenshot of the edit (contact_edit_testuser_edited.png)  
Screenshot of the updated details page  

### Settings:  
OS: Windows 11 Pro  
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080