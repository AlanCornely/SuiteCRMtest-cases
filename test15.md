# Task Assignment  
## Objective:  
Verify if the system allows assigning tasks to users correctly and triggers notifications.  

## Description:  
Tests the process of assigning tasks to users and the corresponding notification system.  

## Prerequisites:  
- Access to SuiteCRM at https://crm.alunostds.dev.br  
- At least 2 registered users  
- Permissions to create/edit tasks  

### Steps:  
1. Create a new task or edit an existing one  
2. Fill in the required fields:  
   - Subject  
   - Status  
   - Priority  
3. Select a user in the "Assigned to" field  
4. Save changes  
5. Verify notification for the assigned user  

### Expected Result:  
- Task successfully assigned  
- Notification received by the assigned user  

### Actual Result:  
✅ Assignment worked  
⚠️ Notification not verified (unclear configuration)  
⚠️ Confusing interface for locating tasks  

### Analysis:  
Basic functionality operates, but there are usability and configuration issues.  

### Identified Issues:  
- Task menu is not intuitive  
- Notification configuration is unclear  
- Workflow is not optimized  

### Recommended Actions:  
1. Redesign the task interface  
2. Document notification configuration  
3. Simplify the assignment process  

### Evidence:  
- Screenshot of the assigned task  
- Screenshot of the confusing interface  

### Settings:  
OS: Windows 11 pro
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080