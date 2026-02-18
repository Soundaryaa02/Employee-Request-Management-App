# Employee-Request-Management-App
Built using PowerApps, SharePoint & Power Automate
Created by: Soundaryaa – Junior Programmer | Power Platform Developer
This is a complete employee workflow automation system where employees can submit requests (Leave, WFH, Permission, etc.) and managers can approve or reject them using an automated approval flow.

This application includes:

✔ Employee Request Submission

✔ Manager Approval System

✔ Auto Email Notifications

✔ User Profile View

✔ Request History

✔ Approval History

✔ Fully Automated Workflow



📌 Features Overview

👩‍💼 Employee Features

Submit request using “Create New Request”

Enter Request Type, Dates, Reason, Department

Auto-filled details: Employee Name, ID, Email, Manager

View personal request history in “My Profile”

Track status: Pending, Approved, Rejected

👨‍💼 Manager Features

View all requests assigned to manager in “My Approval”

Detailed form view before approval

Approve/Reject via Power Automate email

View your approval history



🛠 System Features

Automated email notifications for Pending + Approval + Rejection

SharePoint as secure backend

Power Automate Approval Flow

Clean responsive UI


🏗 System Architecture

PowerApps (UI)
      ↓
SharePoint List (EmployeeRequests)
      ↓
Power Automate Flow
      ↓
Manager Approval
      ↓
SharePoint Status Update
      ↓
Email Notifications


SharePoint Lists Used in This Application

✔ Employee Request 

✔ Employee Details

✔ Master Role


Home Screen

Shows:
My Profile
Create New Request
My Approval


🟣 Create New Request
Fields:
Employee name, ID, email, department, request type, reason, dates, manager name.

🟣 My Profile
Employee details + Request History table.

🟣 My Approval
Manager approval table with pending + approved + rejected requests.

🟣 View Forms
Used for read‑only viewing of request details.


🔁 Power Automate Approval Flow

✔ Trigger: When an item is Created
Employee submits → Status = Pending

✔ Flow Step 1: Email to Employee

✔ Flow Step 2: Email to Manager

✔ Flow Step 3: Manager Approves or Rejects

✔ Flow Step 4: Update SharePoint

✔ Flow Step 5: Email to Employee

📦 Project Files

/AppExport/Employee Request Management.msapp

/FlowExport/EmployeeRequestApprovalFlow.zip

/Documentation/Employee Request Management.docx

/Presentation/ERM-Process Flow.pptx


📥 How to Import This App (For Recruiters / Users)

1️⃣ Import PowerApps App
Go to https://make.powerapps.com
Apps → Import Canvas App → Choose .msapp

2️⃣ Create SharePoint List
Use the column structure mentioned above.

3️⃣ Import Flow (.zip)
https://make.powerautomate.com
My flows → Import → Upload file

4️⃣ Update SharePoint Connections
Re-connect the list inside PowerApps.


🧰 Technologies Used

Microsoft PowerApps

SharePoint Online

Power Automate

Outlook / Teams Notifications


👩‍💻 Author

Soundaryaa Kesavarajan

Junior Programmer

Power Platform Developer
