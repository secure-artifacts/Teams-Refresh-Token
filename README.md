# Teams-Refresh-Token
Retrieve Teams access tokens and log them to Google Sheets. 获取Teams的访问令牌记录到 Google Sheets。

# Server-side Configuration
1. Create a Google Sheet.
2. Click **Extensions** > **Apps Script** in the menu bar.
3. Copy the code from `code.gs` into the editor.
4. Click **Deploy** > **New deployment**, select **Web app** as the type, and set the access permission to **Anyone**.
5. Copy the URL of the deployed web app.

# Installation & Usage

1.  Download the repository code to your local machine.
2.  Open the Chrome browser and navigate to `chrome://extensions/`.
3.  Enable **"Developer mode"** in the top right corner.
4.  Click **"Load unpacked"** and select the project folder.
5.  Click the plugin and paste the deployed API link. Whenever a new browser window is opened, the access token will be automatically populated into Google Sheets.
