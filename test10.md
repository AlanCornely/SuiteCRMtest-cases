# Access Control by Role  
## Objective:  
Verify if the system properly restricts access to functionalities based on the user's role.  

## Description:  
Tests differentiated access permissions between admin and standard users in SuiteCRM.  

## Prerequisites:  
- Access to SuiteCRM at https://crm.alunostds.dev.br  
- Credentials for:  
  - Admin (username: admin, password: admin123)  
  - Standard user (username: user, password: user123)  

### Steps:  
1. Log in as an admin user  
2. Verify access to the Admin Panel  
3. Navigate through restricted modules  
4. Log out  
5. Log in as a standard user  
6. Attempt to access:  
   - Admin Panel  
   - System settings  
   - Restricted modules  

### Expected Result:  
Admin should have full access, while the standard user should have restricted access.  

### Actual Result:  
 Admin accessed all functionalities  
 Standard user had restricted access  

### Analysis:  
The system correctly implements access control by role.  

### Possible Errors:  
- Unauthorized access → Check permission settings  
- Menu visible but not accessible → Verify system ACL  

### Evidence:  
Screenshots:  
1. Admin menu view  
2. Standard user menu view  
3. Access denied message  

### Settings:  
OS: Windows 10/11  
Browser: Chrome v125+  