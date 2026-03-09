# Prerequisites

Before installing WebSureQTool, make sure the target machine meets the following requirements.

---

# 1. Operating System

Supported operating systems:

- Windows 10
- Windows 11

Administrator permission may be required to install the MSI installer.

---

# 2. Supported Browsers

WebSureQTool currently supports the following browsers:

- Microsoft Edge
- Google Chrome

At least one supported browser must be installed.

---

# 3. Determine Your Browser Version

The browser driver **must match the installed browser version**.

## Microsoft Edge

1. Open **Microsoft Edge**
2. In the address bar enter:

```
edge://settings/help
```

3. Note the **Edge Version**

Example:

```
Microsoft Edge Version 123.0.2420.65
```

Record the **major version number** (example: `123`).

---

## Google Chrome

1. Open **Google Chrome**
2. In the address bar enter:

```
chrome://settings/help
```

3. Note the **Chrome Version**

Example:

```
Google Chrome Version 123.0.6312.86
```

Record the **major version number**.

---

# 4. Download the Browser Driver

Download the driver that matches your browser version.

### Microsoft Edge Driver

Download from Microsoft's official website:

```
https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
```

Select the driver version that matches your installed Edge browser.

---

### Chrome Driver

Download from:

```
https://chromedriver.chromium.org/downloads
```

Select the driver version matching your installed Chrome version.

---

# 5. Recommended Driver Location

After downloading the driver executable:

Create a drivers folder inside your workspace.

Example:

```
C:\Users\<YourUser>\Documents\WebSureQTool\workspace\drivers
```

Copy the driver executable into that folder.

Example:

```
msedgedriver.exe
```

or

```
chromedriver.exe
```

---

# 6. Verify Driver Configuration

After installing WebSureQTool:

1. Launch the application
2. Open **Workspace Settings**
3. Verify the **driver path** points to the correct executable

Example:

```
C:\Users\<YourUser>\Documents\WebSureQTool\workspace\drivers\msedgedriver.exe
```

---

# 7. Permissions

Ensure the following permissions are available:

- Permission to install desktop applications
- Permission to create a workspace directory
- Permission to execute the browser driver

---

# Summary

Before installing WebSureQTool you should have:

- Windows 10 or 11
- Microsoft Edge or Chrome installed
- Browser version identified
- Matching WebDriver downloaded
- Driver copied to your workspace drivers folder
