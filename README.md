## Send google sheet in email attachment using python with gmail api without downloading

#### Prerequisites
To run this script, you'll require:
 - Python 2.7.
 - The pip package management tool.
 - Download Client secret json <br>
   a. Visit [Google Cloud API Console](https://console.cloud.google.com).<br>
   b. Select the project associated with your application. Create a project if you do not have one already.<br>
   c. Open the [Credentials page](https://console.developers.google.com/apis/credentials) in the API Console.<br>
   d. Click Create credentials > OAuth client ID.<br>
   e. Complete the form. Set the application type to other.<br>
   f. Click the download icon (Download JSON) button to the right of the client ID.<br>
   g. Move this file to your working directory and rename it client_secret.json.<br>
 - Download send_email_attachment.py from current github repository.
  
#### Step 1 : Turn on the Gmail & Drive Api
 - Visit [Google Cloud API Console](https://console.cloud.google.com)
 - This opens a new dialog. In the dialog, do the following:<br>
    a. Click on ENABLE API.<br>
    b. Now search for Google Sheets API, click on Google Sheets API.<br>
    c. Check Google Sheets API, Drive API & Gmail API are ENABLE or DISABLE if ENABLE then click on label.In below screenshot API is already enabled<br>
    
#### Step 2 : Run the following command to install the library using pip:
`pip install --upgrade google-api-python-client oauth2client`

