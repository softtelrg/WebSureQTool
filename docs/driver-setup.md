# Browser Driver Setup

WebSureQTool requires a compatible browser driver to automate browsers.
A browser driver must match the installed browser version.
This guide explains how to download and configure the correct driver.

---

# 1. Check Your Browser Version
Before downloading a driver, identify your browser version.

## Microsoft Edge
1. Open Microsoft Edge
2. Enter the following in the address bar:
edge://settings/help
3. Note the **version number**
Example:
Microsoft Edge Version 123.0.2420.65
Record the **major version** (example: `123`).

---

## Google Chrome
1. Open Google Chrome
2. Enter in the address bar:
chrome://settings/help
3. Note the **version number**
Example:
Google Chrome Version 123.0.6312.86
Record the **major version**.

---

# 2. Download the Matching Driver

## Edge WebDriver
Download from Microsoft:
https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
Select the driver version matching your installed Edge browser.
Example:
Edge version: 123.x
Download: Edge WebDriver 123.x

---

## Chrome Driver
Download from:
https://chromedriver.chromium.org/downloads
Choose the version matching your installed Chrome browser.

---

# 3. Create Drivers Folder
Inside your workspace create a folder for drivers.
Example:
C:\Users<YourUser>\Documents\WebSureQTool\workspace\drivers

---

# 4. Copy Driver Executable
Place the driver executable inside the drivers folder.
Examples:
msedgedriver.exe
or
chromedriver.exe
Example final path:
C:\Users<YourUser>\Documents\WebSureQTool\workspace\drivers\msedgedriver.exe

---

# 5. Verify Driver Setup
After launching WebSureQTool:

1. Open the application
2. Select your workspace
3. Verify the driver path if required
4. Run a sample test

If the browser opens successfully, the driver is configured correctly.

---

# 6. Common Issue

If the browser fails to start:

✔ Check the browser version  
✔ Verify the driver version matches the browser  
✔ Replace the driver with the correct version
