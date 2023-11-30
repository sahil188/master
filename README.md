Auto Reply Gmail Bot using Node.js

Description:
This Node.js app automates email replies for your Gmail account. It responds to new emails during your vacation, adding a label and moving them.

Features:
 
Node.js clusters support.
Checks for new emails in a specified Gmail ID.
Sends replies to emails with no prior replies.
Adds a label and moves the email to it.
Checks every 45 to 120 seconds at random intervals.
Libraries:

googleapis: Interacts with various Google APIs, including Gmail API.
OAuth2: Authenticates the app and obtains an access token.
Getting Started:

Go to Google Cloud Console and create a new project.
Navigate to the project dashboard and click on "Credentials."
Create OAuth client ID with the application type as "Web application."
Enter "https://developers.google.com/oauthplayground" as the redirect URI.
Enable Gmail API and copy the client ID and client secret.
Open OAuth 2.0 Playground.
Enter client ID and client secret.
Enter https://mail.google.com in "Step 1: Select & authorize APIs."
Authorize and exchange the code for a refresh token.
Replace placeholder values in credentials.js with obtained values (CLIENT_ID, CLIENT_SECRET, REDIRECT_URI, REFRESH_TOKEN).
