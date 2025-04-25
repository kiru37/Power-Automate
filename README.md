# Power-Automate
<details>
<summary>
  
## Scheduled Export & SFTP Transfer
</summary>

### Summary
This flow automates the scheduled generation and distribution of Power BI paginated reports, ensuring they're saved both internally (SharePoint) and externally (SFTP). It has robust error handling to notify users of success or failure, which is key for enterprise or compliance-driven environments.

### Scope
This flow is built for automated scheduled execution of a Power BI paginated report export, followed by:
* Storing the file in SharePoint
* Uploading it to an SFTP server
* Sending notifications on success or failure

### Process flow
<img src="https://github.com/kiru37/Power-Automate/blob/main/SFTP%20file%20creation.jpg" alt="Flow" width="640"/>
</details>
<details>
<Summary>
  
## Trigger the flow from PBI
</Summary>

### Summary
This flow supports automated report generation and distribution using Power BI paginated reports and SharePoint integration. It reduces manual effort in:
* Navigating structured data sources
* Exporting reports
* Distributing them via storage and email notifications

### Scope
This Power Automate flow is built to:
* Traverse through a SharePoint folder hierarchy.
* Generate Power BI paginated reports based on folder structure.
* Export and store reports in SharePoint.
* Notify stakeholders upon completion.

### Process flow
<img src="https://github.com/kiru37/Power-Automate/blob/main/Trigger%20from%20PBI.jpg" alt="Flow" width="270"/>
</details>

<details>
<summary>
  
## Trigger the flow from Excel
</summary>

### Summary
This flow is a conditional report generator using Power BI paginated reports and SharePoint integration. Based on a manually entered report name, it navigates through a series of logical checks to determine which report to generate and save. It allows centralized report management and dynamic control with minimal manual effort.

### Highlights
* Highly customizable: Easily extendable to more conditions/reports.
* Efficient branching logic ensures only the matching report is processed.
* Dynamic and manual inputs make this versatile for users to run ad hoc reports.

### Scope
This flow is designed to:
* Take manual input and report names.
* Traverse SharePoint folder(s).
* Based on specific conditions, generate and store corresponding paginated reports.
* Dynamically handle multiple report variations using nested conditionals.

### Process flow
<img src="https://github.com/kiru37/Power-Automate/blob/main/Trigger%20from%20Excel.jpg" alt="Flow" width="640"/>
</details>
