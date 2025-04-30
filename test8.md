# Export Contacts  
## Objective:  
Verify if the system correctly exports contact data to a file.  

## Description:  
Tests the SuiteCRM export functionality to ensure data is generated completely and accurately.  

## Prerequisites:  
- Admin login (user: `admin`, password: `admin123`)  
- At least one contact registered in the system  
- Access to SuiteCRM at https://crm.alunostds.dev.br  
- Updated browser (Chrome, Firefox, or Edge)  

### Steps:  
1. Log in to SuiteCRM  
2. Navigate to Contacts > Contact List  
3. Select contact(s) for export  
4. Click on Actions > Export  
5. Download and open the generated file  

### Expected Result:  
The file should contain all data of the selected contacts.  

### Actual Result:  
Export completed successfully. Data is complete in the file.  

### Analysis:  
Functionality is operating correctly without errors.  

### Possible Errors:  
- Empty fields → Verify original data  
- Invalid format → Check file extension  

### Evidence:  
- Screenshot of the export option  
- Example of the exported file (CSV)  

### Settings:  
OS: Windows 11 pro
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080