# Email Integration  
## Objective:  
Verify if the system correctly sends email notifications through the configured SMTP server.  

## Description:  
Tests the email-sending functionality of SuiteCRM to ensure message delivery.  

## Prerequisites:  
- Access to SuiteCRM at https://crm.alunostds.dev.br  
- Configured and operational SMTP server  
- Permissions to access email settings  

### Steps:  
1. Access Settings > Email  
2. Send a test email  
3. Check system logs  
4. Confirm receipt in the inbox  

### Expected Result:  
The email should be sent and delivered successfully.  

### Actual Result:  
Failure - SMTP server not configured  

### Analysis:  
The test could not be completed due to the lack of email server configuration.  

### Identified Issues:  
- SMTP server not configured  
- Email functionality inoperative  

### Recommended Actions:  
1. Configure a valid SMTP server  
2. Test the connection to the server  
3. Verify authentication credentials  

### Settings:  
OS: Windows 11 pro
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080