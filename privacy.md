# Privacy Policy for Moving Average

**Effective Date: December 21, 2025**

This Privacy Policy describes user data in connection with the Moving Average Google Sheets Add-on (the "Add-on"). We are committed to protecting your privacy and ensuring a secure experience.

### 1. Data Collection and Usage
The Add-on is designed as a client-side utility. 
- **No Personal Data Collection:** We do not collect, store, or transmit any personal identifiable information (PII) to our own servers or any third parties.
- **Data Processing:** All calculations for the moving average (MA_YEAR) are performed within the Google Apps Script environment. 
- **Google User Data:** The Add-on only accesses the specific spreadsheet cells and stock symbols provided by the user as function arguments.

### 2. Use of External Services (Yahoo Finance)
To provide the core functionality, the Add-on uses the `UrlFetchApp` service to retrieve public financial data from the Yahoo Finance API.
- **Information Sent:** Only the stock symbol (e.g., "AAPL") and the time range are sent to Yahoo Finance.
- **No Account Linking:** We do not send your Google Account identity, email, or any other private spreadsheet data to Yahoo Finance.
- **Third-Party Terms:** Your use of the data fetched is subject to the [Yahoo Terms of Service](https://legal.yahoo.com/us/en/yahoo/terms/otos/index.html).

### 3. Limited Use Disclosure
The Add-on's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the **Limited Use** requirements. 

### 4. Data Security and Retention
- **No Persistence:** We do not use databases or external storage. Your data remains within your Google Spreadsheet.
- **Permissions:** The Add-on only requests the minimum scopes necessary to function:
    - `https://www.googleapis.com/auth/spreadsheets.currentonly`
    - `https://www.googleapis.com/auth/script.external_request`

### 5. Changes to This Policy
We may update this Privacy Policy from time to time. Any changes will be posted on this page with an updated effective date.

### 6. Contact Us
If you have questions or concerns regarding this policy, please contact us via email at: help.mynotifier@gmail.com.
