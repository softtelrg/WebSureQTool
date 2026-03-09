# Troubleshooting

## Browser does not launch

Check:

- Edge or Chrome is installed
- The selected browser is actually installed on the machine
- If you use manual setup, the configured driver path points to the correct `.exe`
- Security software is not blocking the driver executable

## Driver mismatch error

Typical cause:

- The browser updated
- The saved driver did not

Fix:

1. Check the installed browser version again
2. Download the matching driver again
3. Update the configured path
4. Run the sample again

## Automatic driver resolution fails

Possible causes:

- The machine has no internet access
- Corporate security blocks download or execution
- The browser install is nonstandard

Fix:

- Switch to manual driver setup
- Save the driver under `workspace\drivers`
- Point WebSureQTool to that executable

## Example project does not appear

Check:

- The project was extracted under `workspace\projects`
- `project.json` exists inside the project folder
- The workspace path in the app points to the correct root folder

## Reports are not created

Check:

- The workspace path is valid
- The `reports` folder exists
- The user account has write access to the workspace

## Still stuck?

Contact: support@SoftTelRG.com
