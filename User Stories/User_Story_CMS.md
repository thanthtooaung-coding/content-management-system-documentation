# User Story Documentation for Content Management System (CMS)

This document outlines the user stories for the core Content Management System. These stories are derived from the functionalities available to "Admin," "Staff," and "Owner" user roles as depicted in the provided diagrams.

---

### **MoSCoW Prioritization Overview**

The user stories are categorized using the MoSCoW method to guide development efforts:

* **Must-Have (M):** Critical functionalities without which the system is not viable. These represent the core purpose of the CMS.
* **Should-Have (S):** Important functionalities that are not critical for launch but are of high value. The system will work without them, but they are significant.
* **Could-Have (C):** Desirable but less important functionalities. These can be considered "nice-to-haves" if time and resources permit.
* **Won't-Have (W):** Functionalities that will not be included in the current development phase.

---

### **1. Must-Have (M)**

These user stories represent the absolute essentials of the CMS.

| ID | User Story | Role(s) | As a(n)... | I want to... | So that... |
| :-- | :--- | :--- | :--- | :--- | :--- |
| **M1** | User Registration | Owner | Owner | register for an account | I can access the system and request to create my page. |
| **M2** | User Login | Admin, Staff, Owner | user | log in to the system with my credentials | I can access my role-specific dashboard and functionalities. |
| **M3** | User Logout | Admin, Staff, Owner | user | log out of the system | I can securely end my session. |
| **M4** | Page Creation Request | Owner | Owner | contact the admin to request the creation of a new page | my dedicated page can be set up by the administration. |
| **M5** | View Page Requests | Admin | Admin | view all page creation requests from owners | I can process and approve or deny new page requests. |
| **M6** | Manage Pages (by Admin) | Admin | Admin | create, edit, and manage all pages in the system | I have full control over the content and structure of the website. |
| **M7** | Manage Own Page | Owner | Owner | manage the content (title, text, images) of my own page | I can keep my page information current and relevant. |
| **M8** | Manage Staff Accounts | Admin | Admin | create, view, and manage staff accounts | I can delegate content management responsibilities. |
| **M9** | Profile Management | Admin, Staff, Owner | user | manage my own profile information (e.g., name, password) | I can keep my personal details up to date. |

---

### **2. Should-Have (S)**

These user stories are of high importance and should be included if possible.

| ID | User Story | Role(s) | As a(n)... | I want to... | So that... |
| :-- | :--- | :--- | :--- | :--- | :--- |
| **S1** | View Dashboard & Reports | Admin, Owner | Admin/Owner | view a dashboard with key metrics and generate reports | I can get an overview of system activity and performance. |
| **S2** | Process Page Requests | Admin | Admin | update the status of a page request (e.g., approved, rejected) and assign a processor | the owner is informed about their request's progress and there is a clear audit trail. |
| **S3** | Assign Page to Staff | Admin | Admin | assign a staff member to publish or manage a specific page | I can delegate the final review and publishing tasks. |
| **S4** | View Assigned Pages | Staff | Staff | see the pages that have been assigned to me for management | I know which content I am responsible for. |
| **S5** | Manage Staff Roles | Admin | Admin | assign specific roles and permissions to different users (based on the `Role` table) | I can control access levels within the system effectively. |

---

### **3. Could-Have (C)**

These user stories are considered "nice-to-haves" and can be implemented if time and resources allow.

| ID | User Story | Role(s) | As a(n)... | I want to... | So that... |
| :-- | :--- | :--- | :--- | :--- | :--- |
| **C1** | Advanced Reporting | Admin | Admin | generate detailed reports with filtering and sorting options (e.g., by date, by user) | I can gain deeper insights into content performance and user engagement. |
| **C2** | Page Version History | Owner, Admin | Owner/Admin | view the history of changes made to a page | I can revert to a previous version if needed. |
| **C3** | Notification System | Owner, Admin | Owner/Admin | receive notifications for key events (e.g., page request status change, new page published) | I am kept informed about important activities in the system. |
| **C4** | Detailed User Profiles | Admin, Staff, Owner | user | add more detailed information to my profile, such as an address and phone number | my contact information is complete within the system. |

---

### **4. Won't-Have (W)**

These functionalities are explicitly out of scope for the current development focus on the core CMS.

| ID | User Story | Notes |
| :-- | :--- | :--- |
| **W1** | E-commerce Functionality | This belongs to the "E-commerce System" subsystem and is not part of the core CMS. |
| **W2** | Learning Management Features | This belongs to the "Learning Management System" subsystem and is not part of the core CMS. |
| **W3** | Public-Facing Website | While the CMS manages the content, the user stories here focus on the backend management interface, not the public-facing site's user experience. |
| **W4** | Self-Registration for Staff | Based on the use cases, only the Admin can create Staff accounts. Staff cannot self-register. |
