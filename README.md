# SentinelAssessment

This is solution to evaluate your current Microsoft Sentinel Installation.
This solution contains 4 tabs 

|Overview|Schema Details|Retention|Agents Info|
|---|---|---|---|
|View Permissions for the workspace|Supported Operations|Workspace Details|List of Computer checkin|
|Enabled Data Connectors|Table Details|Table based retention|Data sources for Windows Event Logs|
|Workspace Status|||Data sources for Windows Performance Counter Logs Logs|
|Alerts across Product Name & Provider Name|||Data sources for LinuxPerformanceCollection Logs|
|Created Analytic Rules|||
|Created WatchLists|||
|Saved Workbooks|||
|Workspace Functions|||
|IntelligencePacks|||

 
This Soulution is available for deployment through this page.

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fos-securityservices%2FSentinelAssessment%2Fmain%2FSentinelAssessment.json)

Please follow the below steps to complete the deployment

- Steps 1: Hold Control Button and click deploy to Azure button to observe the deployment in a new tab in browser.

- Step 2: Fill the necessary infomation as per the screenshot below and click on **Review + Create** 

![image](https://user-images.githubusercontent.com/82818599/156138557-45533559-0126-41b3-b217-3b35f83d1f2e.png)

```
/subscriptions/{SubscriptionId}/resourceGroups/{ResourceGroupName}/providers/Microsoft.OperationalInsights/workspaces/{Workspace Name}
```
- Step 3 : Click on Create to start the deployment

![image](https://user-images.githubusercontent.com/82818599/156139187-9426dc6a-810c-4b79-9b2c-0ea0ac63831d.png)

- Step 4 : Wait for the successful completion of the deployment.

- Step 5 : Post completion of the deploymemt navigate to Sentinel Workbook section and search the newly deployed workbook under My Workbooks section

![image](https://user-images.githubusercontent.com/82818599/156139585-13e178aa-c50b-40ac-b0ac-123a515e06d8.png)

- Step 6 : Click on View saved workbook to open the deployed workbook and it should open the workbook similar to the following

![image](https://user-images.githubusercontent.com/82818599/156140094-6f4b82f9-02c0-425d-83f9-7e8f8e25d4a2.png)

Please navigate to each section to get more details mentioned above.


