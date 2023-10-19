# CMPG-323-Project-4-29568706

# Overview
Testing is a crucial part of any solution and can be done from many different perspectives; internal development team testing, business user acceptance testing (UAT), etc. Many different types of testing can be conducted on a solution, and user acceptance testing is usually done manually. UAT is often included in most development lifecycles as a crucial step that acts as the ‘go/no-go’ decision maker. UAT is focused on ensuring that the input entered into the solution generates the expected output. Suppose the solution does not generate the desired output. In that case, the solution needs to be amended and retested as it would generally not be published to production unless it passes all tests in UAT. 

Robotic Process Automation (RPA) refers to the use of technology to mimic human tasks in the same way that a person would execute a process. This usually refers to, what we would call, ‘front-end’ or UI (User Interface) automation. RPA is often used to automate time-consuming and highly repetitive tasks to allow people the capacity to work on more intuitive tasks.

Let’s take the web application that you worked on in Project 3 – before the solution can be deployed into production, it would need to go through UAT where a team of ‘testers’ would have a test dataset containing input data and desired output data. The testers would then insert each input data record into each web application field and test that the desired output is generated. In this case, the desired output would be a new record being displayed on the web application once the item has been added. This would result in a highly repetitive process that can and should (in this case) be automated using RPA.

# GitHub Administration
### Create and Configure GitHub Repository
- Create a repository named ‘CMPG 323 Project 4'
- Create a ReadME.md file that will be used to describe your project and how stakeholders are to use the report that you have developed
  
### Project Progress
- Ensure that the solution has been committed and pushed to source control throughout the project
- Ensure that the GitHub project has been updated iteratively throughout the project to demonstrate how progress was made

# Project Setup
### Create the Project
- Clone your GitHub repository
- Install UiPath Studio
- Create a new UiPath process named ‘Connected Office Web Application – User Acceptance Testing’

# User Acceptance Testing
### Read the input data
- Read the data from Excel into a data table in UiPath
- Ensure that the data is readable and iterated over in UiPath

### UI Automation
- For each record in the data table, navigate to the URL in the browser that allows data to be entered to create a new record
- Insert the fields from each record into the fields on the web application to create a new record on the web application
- Click the ‘submit’ button on the web application to create a new record on the web application once the data fields have been inserted
- Navigate to the URL where you can view the newly created record on the web application

### Record Results
- If the item was created successfully, update the data table record to depict that the record passed testing. If the item was not created, update the data table to depict that the record failed to test
- Update the Excel spreadsheet with the testing results (Test Results column of the Excel file provided – update with TRUE or FALSE)

# Project Close-out
### Deploy Solution
- Publish the UiPath solution to the UiPath Orchestrator

# Please make sure to refer to this README throughout the project to ensure that all tasks are completed in the correct order. If you have any questions or need assistance, don't hesitate to reach out to me

# Reference list
- (2021). YouTube. 12 January. Available at: https://www.youtube.com/watch?v=7SrdrREJtcc&amp;t=2s (Accessed: 11 October 2023). 
- (2022). YouTube. 7 June. Available at: https://www.youtube.com/watch?v=oUL9cmUHAQ4&amp;t=260s (Accessed: 19 October 2023). 
- Excel automation tutorial - datatables automation (no date) UiPath. Available at: https://www.uipath.com/learning/video-tutorials/excel-datatables-automation (Accessed: 10 October 2023). 
- Excel in Power Automate for Desktop (Full Tutorial) (2022). YouTube. 4 May. Available at: https://www.youtube.com/watch?v=zVvaRCZqZ7E&amp;list=RDCMUCPdtz4gd_iYebJFYq9N8pWA&amp;index=11 (Accessed: 12 October 2023). 
- How to do API calls in UiPath | Full Tutorial (2020). YouTube. 26 February. Available at: https://www.youtube.com/watch?v=HiS_lQ1wbD4&amp;list=RDCMUCPdtz4gd_iYebJFYq9N8pWA&amp;index=42 (Accessed: 16 October 2023). 
- How to Run Desktop Flows From Power Automate - Full Tutorial (2022). YouTube. 22 July. Available at: https://www.youtube.com/watch?v=mxfOEpTE6hw&amp;list=RDCMUCPdtz4gd_iYebJFYq9N8pWA&amp;index=23 (Accessed: 13 October 2023). 
- UI Automation (2023) Docs.uipath.com. Available at: https://docs.uipath.com/studio/standalone/2023.4/user-guide/ui-automation (Accessed: 10 October 2023). 
- UiPath - How to loop through rows and columns in Excel and pass values to web search/input (2020). YouTube. 25 March. Available at: https://www.youtube.com/watch?v=LVHwmq7QVmI&amp;list=RDCMUCPdtz4gd_iYebJFYq9N8pWA&amp;index=15 (Accessed: 12 October 2023). 
- UiPath Excel Read Range and Write Range Activity | UiPath Tutorial (2022). YouTube. 23 August. Available at: https://www.youtube.com/watch?v=BBSSle2dGiU&amp;t=282s (Accessed: 11 October 2023). 
- UiPath For Each Activity | For Each Loop in UiPath (2022). YouTube. 23 July. Available at: https://www.youtube.com/watch?v=_NwibFgDq7o (Accessed: 12 October 2023). 
- UiPath | How to Automate Excel and Work with Data Tables | Tutorial (2020). YouTube. 31 January. Available at: https://www.youtube.com/watch?v=E9GUL53V3-E (Accessed: 12 October 2023). 
- Pathak, S. et al. (2022) Intelligent system algorithms and applications in science and Technology. Palm Bay, FL, USA: Apple Academic Press. 
- 14 September weekly virtual class Automation introduction. CMPG323 - IT Developments (2023). YouTube. 23 September. Available at: https://www.youtube.com/watch?v=wi18JuLhZ74 (Accessed: 23 September 2023). 
- 03 October Project 4 Explained. CMPG323 - IT Developments (2023). YouTube. 03 October. Available at: https://www.youtube.com/watch?v=5s1-p1okZoc&t=308s (Accessed: 05 October 2023). 
- UiPath Test Suite: Automate RPA Tests (2023). YouTube. 10 August. Available at: https://www.youtube.com/watch?v=VDgUC4KSz3w (Accessed: 18 October 2023). 
- iPath Test Suite| Test Automation using UiPath |UiPath Testing Activities| Tutorial Part-1 (2022). YouTube. 1 January. Available at: https://www.youtube.com/watch?v=tQTbx62fdxc&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt (Accessed: 16 October 2023). 
- Read Excel in UiPath | Excel vs Workbook Activities - Difference | Excel Automation | UiPath | RPA (2020). YouTube. 18 October. Available at: https://www.youtube.com/watch?v=qhqBjjZmxpc&amp;list=PLEYSwx3duQ2CezNtFlhnrVfXUCI0XmcQz&amp;index=3 (Accessed: 18 October 2023). 
- UiPath - How to export build diagram to XAML in Task Capture? | Advantages of Task Capture (2022). YouTube. 2 April. Available at: https://www.youtube.com/watch?v=6MwOrmsVb7A&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=10 (Accessed: 18 October 2023). 
- UiPath - Task Capture | Start documenting your process with Task Capture | Practical demo | Part-01 (2022). YouTube. 30 March. Available at: https://www.youtube.com/watch?v=ZP-4bgmeAJw&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=9 (Accessed: 18 October 2023). 
- UiPath - Test Automation| Add Test Data file, Convert Workflow to Testcase, BDD Template| Part-2 (2022). YouTube. 3 January. Available at: https://www.youtube.com/watch?v=nOxQbXA3qD4&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=2 (Accessed: 16 October 2023). 
- UiPath Test Manager | Connect Test Manager to UiPath Studio | Start Test Automation using UiPath (2022). YouTube. 9 March. Available at: https://www.youtube.com/watch?v=5_yTPwBidlw&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=6 (Accessed: 17 October 2023). 
- UiPath- How to schedule Test Execution? |Test Schedule |Test Manager |Test Sets | Test Executions (2022). YouTube. 23 March. Available at: https://www.youtube.com/watch?v=-jEu_93eldM&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=8 (Accessed: 17 October 2023). 
- UiPath- Test Automation | Important Activities to create the test cases | Practical demo |Part 3 (2022). YouTube. 14 January. Available at: https://www.youtube.com/watch?v=o1YmS-Qp7Gs&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=3 (Accessed: 16 October 2023). 
- UiPath-Test Automation| Get Test Data Queue Item| Test Data Queue| Part-5 (2022). YouTube. 23 January. Available at: https://www.youtube.com/watch?v=6v5CqCp9tmE&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=5 (Accessed: 16 October 2023). 
- UiPath-Test Automation| Test Data Queue|Add TestData Queue Item &amp; Bulk Add Test Data Queue Items| #4 (2022). YouTube. 16 January. Available at: https://www.youtube.com/watch?v=fFmfOCenhDY&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=4 (Accessed: 16 October 2023). 
- UiPath-Test Manager detailed |Features of Test Manager explained |Manual &amp; Automation Test execution (2022). YouTube. 19 March. Available at: https://www.youtube.com/watch?v=zoQDlgouv8I&amp;list=PLgY1FEm82KyVl9aHmRMo6EQQjDA3P0dMt&amp;index=7 (Accessed: 17 October 2023). 
