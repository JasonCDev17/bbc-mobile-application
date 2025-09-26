 BBC Mobile Application Project

This repository contains all deliverables for the BBC Mobile Application testing project.

 Overview of Files

| Category       | File(s) | Description |
|----------------|---------|-------------|
| RTM            | `BBC Mobile RTM.xlsx` | Requirement Traceability Matrix linking requirements to test cases. |
| Test Plans     | `BBC Mobile TP.docx` | Detailed Test Plan for the project. |
| Test Scripts   | `BBC Mobile TS.xlsx` | Test scripts and scenarios to be executed. |
| Bugs           | `BUG-001.png`, `BUG-002.png` | Screenshots of identified bugs. |
| Sprint Reports | `Sprint1.png`, `Sprint2.png` | Sprint completion reports. |
| Workflow       | `Mobile-Workflow.png` | Workflow diagram of the testing process. |


BBC News Mobile App – Manual Testing Project

 Project Overview
This project demonstrates **manual mobile testing** of the **BBC News App** on both **iOS and Android** platforms.  
It covers app launch, navigation, media content validation, stability checks, and notification handling.  

The purpose is to showcase **mobile QA skills** including test planning, defect reporting, and requirements traceability.



 Tools & Technologies Used
- **Test Case Management**: Excel / Google Sheets  
- **Bug Tracking**: Jira (screenshots included)  
- **Devices Tested**: iPhone, Android phone (real + emulators)  
- **Browsers/Platforms**: Native iOS & Android apps  
- **Additional Checks**: Battery usage monitoring, offline mode testing  



Project Deliverables
1. **Test Plan** – Scope, objectives, and testing approach for the app  
2. **Test Cases** – 10 designed test cases across 4 epics  
3. **RTM (Requirements Traceability Matrix)** – Mapping stories to test cases & results  
4. **Bug Reports** – Logged in Jira with screenshots and details  
5. **Test Summary Report** – Overall execution results  



 Repository Contents
- `/TestPlan` → Mobile Test Plan document  
- `/TestCases` → Test cases in Excel/CSV  
- `/RTM` → Requirements Traceability Matrix  
- `/BugReports` → Logged bugs (Markdown + Jira screenshots)  
- `/TestSummary` → Final execution summary  



 Sample Bugs Logged
- **BUG-MOB-001**: Video restarts after device rotation  
- **BUG-MOB-002**: UI overlap after orientation change  
- **BUG-MOB-003**: Push notification opens home page instead of article  

(See `/BugReports` for full details with Jira screenshots)



Test Execution Summary
- Total Test Cases: **10**  
- Passed: **7**  
- Failed: **3** (bugs logged in Jira)  



 What I Learned
- Testing **iOS and Android mobile apps** on real and virtual devices  
- Designing functional, UI/UX, and performance-related test cases  
- Reporting defects in **Jira** with reproducible steps and priority/severity  
- Handling **device-specific issues** (rotation, offline mode, push notifications)  
- Using battery/performance monitoring for mobile QA  



 Areas for Improvement
- Expand testing to include **API-level checks** with Postman  
- Automate regression scenarios using **Appium**  
- Explore device farm testing (e.g., BrowserStack, Sauce Labs).
