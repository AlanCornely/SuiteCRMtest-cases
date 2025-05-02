# Task Creation  
## Objective:  
Verify if the system allows task creation correctly, validating required fields.  

## Description:  
Tests the task creation functionality in the SuiteCRM Calendar module.  

## Prerequisites:  
- Access to SuiteCRM at https://crm.alunostds.dev.br  
- Valid user credentials  
- Permissions to create tasks  

### Steps:  
1. Access the Calendar module  
2. Click on "Create Task"  
3. Fill in the required fields:  
   - Subject  
   - Status  
   - Priority  
4. Click "Save"  
5. Verify redirection to the summary view  

### Expected Result:  
The system should create the task and display the summary page after saving.  

### Actual Result:  
✅ Task created successfully  
✅ Required fields validated correctly  

### Analysis:  
Functionality is operating as specified.  

### Possible Issues:  
- Required fields not marked → Check form settings  
- Error while saving → Verify user permissions  

### Evidence:  
Screenshot:  
1. Creation form  
2. Task displayed in the calendar  

### Settings:  
OS: Windows 11 pro
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080