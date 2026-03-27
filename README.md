# XLSX FILE CONVERT TO CSV FILE WORKFLOW AUTOMATION
"This workflow will automatically convert your XLSX file into CSV file"

## Steps

### Step 1: Open n8n
Go to your local n8n instance:
http://localhost:5678

Log in to your account.

### Step 2: Import the Workflow
- In the top-right corner, click the **three dots (⋮)** menu  
- Select **"Import from file"**

### Step 3: Select the JSON File
- Navigate to the folder where you extracted the ZIP file  
- Select the `.json` workflow file  
- Click **Open / OK**

---
## Workflow Purpose

- Download a file from Google Drive  
- Extract data from an Excel file  
- Loop through each record  
- Check existing data in Google Sheets  
- Process and transform data using JavaScript  
- Upload the updated file back to Google Drive  
---

## Workflow Structure

1. Trigger (Manual)
2. Download File (Google Drive)
3. Extract Data (XLSX)
4. Loop Over Items
5. Get Rows from Google Sheets
6. Data Processing (JavaScript)
7. Data Transformation (JavaScript)
8. Final Formatting (JavaScript)
9. Upload File (Google Drive)
---

## 💡 Notes
- Make sure your n8n server is running before importing  
- If the workflow uses external services (e.g., Google APIs), reconnect credentials after importing  
