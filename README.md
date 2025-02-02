# Unqork Corporate Vehicle Request Tracker 🚗
**Novice Badge Certification Project**</br>
This repository contains the Corporate Vehicle Request Tracker, an application built in Unqork as part of the Novice Badge Certification Exam. The application is designed to manage corporate vehicle requests submitted by employees, with an approval process managed by operations.


# 📌 Project Overview
**The Corporate Vehicle Request Tracker allows:**</br>
• Employees to submit vehicle requests by providing trip details.</br>
• The system to validate the request and ensure compliance.</br>
• Operations Managers to review, approve, or reject requests.</br>
• A dashboard to track submitted requests with key performance indicators.</br>


# 🏗 Application Structure
This project was built using Unqork **Workflow Builder** and consists of five modules:
| **Module**             | **Purpose**                                                              |
|------------------------|------------------------------------------------------------------------|
| **Employee Information** | Captures employee details, including role, driving history, and trip purpose. |
| **Validation Module**   | Ensures the request is valid (e.g., rejecting Clients from proceeding). |
| **Trip Information**    | Collects trip details, such as origin, destination, and vehicle type.  |
| **Manager Review**      | Allows Operations Manager to approve or reject the request.           |
| **Dashboard**           | Displays submitted requests and KPI metrics for tracking.            |


# ⚙️ Workflow Implementation
The project workflow consists of:</br>

• **Three Swimlanes:** RelationshipManager, Automated, OperationsManager</br>
• **Decision Gateways** for validation</br>
• **Message Nodes** for email notifications</br>
• **Signal Nodes** for request closure</br>


<details> <summary>📸 Workflow Diagram</summary> <img src="./workflow/workflow-diagram.png" width="600"/> </details>


# ✅ Certification & Grading</br>
This project meets all Novice Badge Exam grading criteria, as confirmed by the rubric.</br>

✔ Component IDs follow camelCase</br>
✔ Correct field types and property IDs used</br>
✔ Workflow structure meets specifications</br>
✔ Dashboard includes required fields and KPI widget</br>


# 🚀 How to Run</br>
1. Import the JSON files into an Unqork workspace.</br>
2. Verify the Workflow & Modules in Unqork Designer.</br>
3. Test Submissions using the Employee and Operations Manager roles.</br>
4. Validate Email Notifications (ensure correct email configurations).</br>
5. Check the Dashboard for submitted requests.</br>





