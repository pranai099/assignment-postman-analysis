Step 1: Understand the Assignment

Your file contains:

HTML structure
CSS links
JavaScript files
API/network requests used by WhatsApp Web

Main goal of the assignment:

Inspect the webpage
Find API/network requests
Open them in Postman
Analyze request and response
Step 2: Open the HTML File
Method
Go to your Downloads folder
Double click 27 1.html
It opens in browser

OR

Open VS Code
Drag the file into VS Code
Right click
Select Open with Live Server
Step 3: Open Developer Tools

In Chrome:

Press F12

OR

Right click webpage
Click Inspect

Now Developer Tools opens.

Step 4: Open Network Tab
Click Network
Refresh the page (Ctrl + R)

Now you will see:

JS files
CSS files
API calls
WebSocket requests
Step 5: Filter API Requests

In Network tab:

Click:

Fetch/XHR

These are backend API requests.

You will see requests like:

authentication
data loading
messages syncing
Step 6: Copy Request URL
Click any request
Go to:
Headers
Copy:
Request URL
Request Method

Example:

GET
POST
Step 7: Open Postman

Use Postman

If not installed:

Postman Official Website

Step 8: Create New Request in Postman
Open Postman
Click New
Select HTTP Request
Step 9: Paste the URL

Example:

Select method:
GET / POST
Paste copied URL
Step 10: Add Headers

From browser Developer Tools:

Copy headers like:

Authorization
Content-Type
Cookie

In Postman:

Open Headers
Paste values
Step 11: Add Request Body (If POST)

If request method is POST:

Go to Body
Select:
raw
JSON
Paste request payload
Step 12: Send Request

Click:

▶ Send

Now Postman shows:

JSON response
status code
response headers
Step 13: Write Assignment Observations

Include:

Objective

To analyze webpage API requests using browser Developer Tools and Postman.

Tools Used
Chrome Browser
Developer Tools
Postman
Procedure

Write the above steps.

Output
Request URL
Request Method
Response JSON
Status Code
Conclusion

Successfully analyzed API requests using Postman.

Step 14: Sample Output Format
{
  "status": "success",
  "message": "Request completed"
}

Status Code:

200 OK
Important Note

Some WhatsApp APIs:

require login tokens
use encryption
may not work directly in Postman

For assignment/demo purpose:

analyzing requests is enough.
Simple Flow Diagram
HTML File
   ↓
Open in Browser
   ↓
Inspect → Network
   ↓
Copy API Request
   ↓
Open Postman
   ↓
Paste URL + Headers
   ↓
Send Request
   ↓
Analyze Response