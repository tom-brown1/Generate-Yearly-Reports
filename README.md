# UiPath Generate Yearly Reports - Solution
This repository contains the solution for the Generate Yearly Reports exercise from UiPath Academy Automation Developer Professional Training. The project automates the process of generating and downloading monthly reports for multiple vendors, consolidating them into yearly reports, and uploading them to the UiPath Orchestrator.

# Features
- Orchestrator Integration: Automates the retrieval of vendor details from the UiPath Orchestrator Queue.
- Web Automation: Navigates through the ACME System 1 website to download monthly reports for each vendor.
- File Handling: Merges downloaded monthly reports into a comprehensive yearly report.
- Error Handling: Implements robust error handling and retry mechanisms to ensure seamless execution.
- Report Uploading: Automatically uploads the consolidated yearly reports back to the UiPath Orchestrator.
- Logging and Monitoring: Includes detailed logging for monitoring the workflow and identifying issues.
# How to Use
1. Clone this repository to your local machine.
2. Open the project in UiPath Studio.
3. Configure your Orchestrator and ACME System credentials in the config file.
4. Run the workflow to generate and upload yearly reports for each vendor.
   
# Prerequisites
1. UiPath Studio installed
2. Access to UiPath Orchestrator
3. An account on the ACME System 1 platform
4. Default Browser set to Microsoft Edge.
