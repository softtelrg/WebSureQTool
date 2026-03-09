# 🚀 WebSureQTool Quick Start Guide

This guide will walk you through setting up your first automation project using the **WebSureQTool** sample workspace.

---

### 1. Install WebSureQTool
If you have not installed the application yet, please follow our detailed installation guide:
👉 [docs/installation-windows.md](./docs/installation-windows.md)

### 2. Download the Sample Workspace
1. Navigate to the `examples` folder in this repository: [examples/sample-workspace.zip](./examples/sample-workspace.zip).
2. Download and extract the ZIP file to a local folder.
   
**Recommended location:**
`C:\Users\<YourUser>\Documents\WebSureQTool\`

*After extraction, your path should look like:*
`C:\Users\<YourUser>\Documents\WebSureQTool\sample-workspace`

### 3. Verify Browser Driver
Before running the sample, ensure the correct browser driver is available in your workspace.
**Example driver path:**
`...\sample-workspace\drivers\msedgedriver.exe`

If the driver is not ready, follow the setup guide:
👉 [docs/driver-setup.md](./docs/driver-setup.md)

### 4. Open the Sample Workspace
1. Launch **WebSureQTool**.
2. Click **Set Workspace** and select your extracted `sample-workspace` folder.
3. Confirm the workspace opens. You should see the **demoShop** project in the Project Explorer.

### 5. Open the Sample Suite
Inside the **demoShop** project, open the available test suite:
*   **Example Suite:** `home page`
*   *Note: This suite demonstrates the standard workspace and YAML suite structure.*

### 6. Run the Sample Suite
Click the **Run** button within WebSureQTool. During execution, the tool will:
*   ✅ Launch the browser automatically.
*   ✅ Execute the visual suite steps.
*   ✅ Generate real-time logs.
*   ✅ Produce report output.

### 7. Review the Results
Once the run is complete, check the following local folders in your workspace for the output:
*   📂 `sample-workspace\logs`
*   📂 `sample-workspace\reports`

### 8. Next Steps
Once the sample runs successfully, you are ready to:
*   ➕ Create your own **Projects**.
*   🧪 Build custom **Suites** using the Web Scanner.
*   📊 Add **Datasets** (CSV/JSON) for data-driven testing.
*   💻 Generate **Java/C# Code** (Pro Version).

---
**SoftTelRG Support:** If you encounter unexpected behaviors, contact us at `support@softtelrg.com`.
