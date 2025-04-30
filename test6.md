# Search Contacts  
## Objective:  
Verify if the system can find contacts using different search criteria (name, email, phone).  

## Description:  
Tests the search functionality of SuiteCRM to confirm it returns accurate and fast results.  

## Prerequisites:  
- Admin login (user: `admin`, password: `admin123`)  
- Existing contacts with registered name, email, and phone  
- Access to SuiteCRM at https://crm.alunostds.dev.br  
- Updated browser (Chrome, Firefox, or Edge)  

### Steps:  
1. Log in to SuiteCRM  
2. Access the Contacts module  
3. In the search bar, search for:  
   - Full name of the contact  
   - Registered email address  
   - Registered phone number  
4. Verify the displayed results  

### Expected Result:  
The system should display the correct contact for each type of search performed.  

### Actual Result:  
The search worked correctly for all tested criteria.  

### Analysis:  
Test approved - The search returned the expected results in all cases.  

### Possible Errors:  
- No results found → Verify if test data is correct  
- Incorrect results → Check system indexing  

### Evidence:  
Screenshots of search results:  
1. By name  
2. By email  
3. By phone  

### Settings:  
OS: Windows 11 pro
Browser: Chrome 123.0.6312.86
Resolution: 1920x1080