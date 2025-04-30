# Import Contacts via CSV  
## Objective:  

Verify if the system correctly imports contact data from CSV files.  

## Description:  

Tests the SuiteCRM import functionality to ensure data is validated and registered as expected.  

## Prerequisites:  
- Admin login (user: `admin`, password: `admin123`)  
- Properly formatted CSV file with contact data  
- Access to SuiteCRM at https://crm.alunostds.dev.br  
- Updated browser (Chrome, Firefox, or Edge)  

### Steps:  
1. Log in to SuiteCRM  
2. Navigate to Contacts > Import Contacts  
3. Select the CSV file for upload  
4. Validate automatic field mapping  
5. Confirm the import  
6. Verify the created contacts in the list  

### Expected Result:  

The system should import all records from the CSV and display a confirmation message.  

### Actual Result:  

Data imported successfully  

Usability issue: the screen does not automatically scroll back to the top  

### Analysis:  

The import worked correctly, but the interface has a minor visual defect.  

### Possible Errors:  
- Unmapped fields → Check the CSV header  
- Invalid data → Verify the formatting of values  
- Scrolling issue → Navigate manually  

### Evidence:  
- Screenshot of the import process  
- Example of the CSV used:  
```
    "First Name","Last Name","ID","Salutation","Job Title","Department","Account Name","Email Address","Non Primary E-mails","Mobile","Office Phone","Home","Other Phone","Fax","Primary Address Street","Primary Address City","Primary Address State","Primary Address Postal Code","Primary Address Country","Alternate Address Street","Alternate Address City","Alternate Address State","Alternate Address Postal Code","Alternate Address Country","Description","Birthdate","Lead Source","Campaign ID","Do Not Call","Reports to ID","Assistant","Assistant Phone","Assigned to","Assigned User","Date Created","Date Modified","Modified By","Created By","Deleted","Photo","Lawful Basis","Lawful Basis Date Reviewed","Lawful Basis Source","Joomla Account ID","Account Disabled","Portal User Type","Address","Geocode Status","Longitude","Latitude"
    "Marcela","Santos","b2345678-c01d-51e2-b567-667753550001","Dr.","Marketing Manager","Marketing","Global Tech Solutions","m.santos@globaltech.com","marcela.personal@outlook.com","21987654321","2133445566","2122334455","2144556677","2144667788","Avenida Paulista, 1001","São Paulo","SP","01311-200","Brazil","Rua Oscar Freire, 500","São Paulo","SP","01426-001","Brazil","Premium client since 2020","1985-07-22","Referral","camp-2020","1","dir-123","Ana Beatriz","2199887766","marketing","8b8574b7-d961-e14f-681e-78g575g1ed0c","2024-11-15 14:30","2025-03-10 09:15","8b8574b7-d961-e14f-681e-78g575g1ed0c","7c6452a5-c840-c02d-460c-56e353e0cb0a","0","profile.jpg","Contract","2025-01-15","Email","joomla-245","1","Portal admin","","Approximate","-46.6556","-23.5629"
```
### Settings:  
OS: Windows 11 pro
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080