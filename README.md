>[!IMPORTANT] 
>**Disclaimer:** VoltSea Ferries is a fictional organisation created for portfolio and demonstration purposes. All data, users, and scenarios in this project are entirely simulated.


## Overview


A full-stack, mobile-first Leave Management System built on the Microsoft 365 Power Platform for VoltSea Ferries - a fictional Auckland-based ferry operator. The system digitises and automates the entire leave request lifecycle, from employee submission through to manager approval and payroll notification, replacing a manual email-based process with a structured, auditable, and automated workflow.

&nbsp; 

**About VoltSea Ferries**

VoltSea Ferries is Auckland's fictional premium passenger ferry operator, connecting commuters and visitors across the Hauraki Gulf since 2008. Operating a fleet of nine fully electric and hybrid-electric vessels, VoltSea serves six routes across the Gulf - including the high-frequency Auckland CBD to Devonport corridor (departing every 30 minutes) and the scenic Auckland CBD to Waiheke Island service.

With a workforce of 350+ staff spanning vessel crew, terminal operations, logistics, finance, and corporate functions, VoltSea prides itself on sustainability, community connection, and operational excellence. The company operates Auckland's first fully electric bus fleet through its subsidiary Waiheke Bus Company and is currently project-managing the build of Auckland's first hybrid-electric fast ferries.

Fleet: Hiko Moana - Volt Mabuhay · Koru Wave · Eclipse · Aurora · Neon Wave · Seabreeze · Tidal Voyager · Coastal Runner

&nbsp;

**Business Problem**

Prior to this system, VoltSea Ferries managed employee leave through a combination of email requests, spreadsheet tracking, and manual payroll updates. This created several operational problems:
- Leave requests were submitted via email with no standardised format, making them difficult to track and audit
- Managers had no visibility of an employee's remaining leave balance at the time of approval
- Finance and Payroll received inconsistent or delayed notifications, causing payroll processing errors
- There was no centralised record of leave history, making HR reporting time-consuming
- Vessel crew and operational staff without regular computer access had no mobile-friendly way to submit requests
- No validation existed to prevent employees from requesting more leave than their entitlement allowed
- The approval process had no defined SLA - requests could go unanswered for days with no automated follow-up

&nbsp; 

**Solution**

A five-screen mobile-first Power Apps canvas application connected to SharePoint as the data layer, with two Power Automate flows handling the complete approval and notification workflow. The system serves two user roles - employees and managers - with role-based access controlled through a SharePoint reference list.

**Employees can:**

- View their real-time leave balances across Annual, Sick, and Personal leave types
- Submit leave requests with automatic duration calculation and balance validation
- Track the status of all their previous and current requests
- View full request details including manager comments on approval or decline
  
**Managers can:**

- View all pending approval requests across their team
- See the employee's current balance and projected impact before deciding
- Approve or decline with comments in a single tap
- Receive notifications via email and Microsoft Teams

&nbsp;

**Features**

- Leave Request Submission
- Manager Approval Workflow
- Leave Balance Tracking
- Automated Notifications

&nbsp;

> [!NOTE]
> **Project Artefacts**\
Source files are not included in this repository. Documentation is provided 
via screenshots and UAT samples located in the `/screenshots` and `/uat` 
folders respectively. These demonstrate solution functionality, flow logic, 
and test coverage without exposing proprietary configuration.

&nbsp;

🙋Created by Mark Thomas Bundang| | https://github.com/tab8
