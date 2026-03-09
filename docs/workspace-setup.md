# Workspace Setup

WebSureQTool uses a workspace directory to organize projects, logs, reports, and browser drivers.

A workspace is simply a folder on your machine that contains all files related to your automation projects.

---

## Recommended Workspace Location

Example location:

C:\Users\<YourUser>\Documents\WebSureQTool\workspace

You may choose any location, but it is recommended to keep the workspace inside your user documents folder.

---

## Example Workspace Structure

A typical workspace may look like this:

workspace/

├── projects/

│   └── demoShop/            # Your automation project

│       ├── project.json     # Project configuration

│       ├── suites/          # YAML test suites

│       └── data/            # CSV/JSON datasets

├── drivers/

│   └── msedgedriver.exe     # Browser automation drivers

├── logs/                    # Real-time execution logs

└── reports/                 # HTML & JUnit test reports

---


---

## Selecting a Workspace

When WebSureQTool starts for the first time:

1. Launch the application
2. Select or create a workspace directory
3. Confirm the workspace loads successfully

Once selected, WebSureQTool will remember the workspace location.

---

## Using the Sample Workspace

If you downloaded the sample workspace from the repository:

examples/sample-workspace.zip

Extract it and select that folder as your workspace.

This allows you to immediately explore the example project and test suite.

---

## Tips

• Keep one workspace per automation environment  
• Store drivers inside the workspace drivers folder  
• Regularly review logs and reports after test runs  
• Back up your workspace if it contains important automation projects
