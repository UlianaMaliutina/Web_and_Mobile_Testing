# Urban Scooter Web & Mobile App Testing

## Project Description
This project focuses on testing both the **Urban Scooter Web App** and **Urban Scooter Mobile App** to ensure that their functionalities meet the specified requirements. The testing covers form validation, mobile app authentication, API interactions, and backend functionalities.

## Technologies and Tools Used
- **Browsers**: Google Chrome (85+) and Opera (71+)  
- **Android Emulator**: Android 31  
- **Android Studio**: For installing and running the mobile application  
- **Postman**: For API testing and sending JSON-based requests  
- **Figma**: For UI/UX validation  
- **Google Sheets**: For documenting test cases and results  
- **Jira**: For logging and tracking bugs  
---

## Tasks & Testing Process  

### Task 1: Web App Testing (About Customer Form)  
#### **Scope**
- Validate the "About Customer" form, which includes customer name and phone number fields.  
- Test form behavior across different browsers and resolutions.  

#### **Process**
1. **Requirement Analysis**:  
   - Study the provided specifications and compare them with Figma designs.  
   
2. **Test Case Design**:  
   - Create positive test cases (valid inputs).  
   - Create negative test cases (invalid inputs, missing data, incorrect formats).  

3. **Execution**:  
   - Run test cases on **Google Chrome (85+)** and **Opera (71+)** at **1280x720** resolution.  
   - Document results in Google Sheets.  

4. **Bug Reporting**:  
   - Record any issues in Jira and insert bug report links into the test case sheet.  
---

### Task 2: Mobile App Testing  
#### **Scope**
- Install and configure the **Urban Scooter Mobile App** in an emulator.  
- Create and authenticate a courier using the API.  
- Validate layout and design consistency.  

#### **Process**
1. **Setup**:  
   - Install the **Urban Scooter APK** in **Android Studio Emulator (Android 31)**.  
   - Configure backend interaction via API settings in the app.  

2. **API Interaction**:  
   - Create a courier account using API requests in Postman.  
   - Ensure the API request follows the required **JSON format**.  

3. **Test Execution**:  
   - Perform test cases related to UI layouts, interactions, and API responses.  
   - Document test results in Google Sheets.  

4. **Bug Reporting**:  
   - Log any bugs in Jira and attach relevant test results.  
---

### Task 3: Backend API Testing  
#### **Scope**
- Test the **Add Courier** and **Delete Courier** API functionalities.  

#### **Process**
1. **Requirement Analysis**:  
   - Examine the API documentation and backend requirements.  

2. **Test Case Design**:  
   - Develop positive test cases (successful creation/deletion).  
   - Develop negative test cases (invalid requests, missing parameters).  

3. **Execution & Validation**:  
   - Run API tests in Postman.  
   - Verify expected responses (e.g., **201 Created**, **400 Bad Request**, **404 Not Found**).  
   - Record results in Google Sheets.  

4. **Bug Reporting**:  
   - Log errors in Jira with request details and server responses.  
