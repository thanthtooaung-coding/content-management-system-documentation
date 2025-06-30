# **User Story Documentation for Learning Management System (LMS)**

This document outlines the user stories for the Learning Management System (LMS). The stories are derived from the functionalities available to the "Student," "Instructor," "Staff," "Admin," and "Owner" user roles, as detailed in the provided use case and entity-relationship diagrams.

---

### **MoSCoW Prioritization Overview**

The user stories are categorized using the MoSCoW method to guide the development lifecycle:

* **Must-Have (M):** Core functionalities essential for the LMS to be viable. The system cannot function without them.
* **Should-Have (S):** High-value features that are important but not critical for the initial launch.
* **Could-Have (C):** Desirable but less important features that can be added if time and resources allow.
* **Won't-Have (W):** Functionalities explicitly out of scope for the current development phase of the LMS.

---

### **1. Must-Have (M)**

These user stories define the fundamental operational, teaching, and learning loops of the LMS.

| ID | User Story | Role(s) | As a(n)... | I want to... | So that... |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **M1** | User Login | All Roles | user | log in to the system with my credentials | I can access my dashboard and role-specific features. |
| **M2** | Manage Profile | All Roles | user | manage my own profile information | I can keep my personal details current. |
| **M3** | Manage User Accounts | Admin, Owner | Admin/Owner | create, edit, and manage all user accounts | I can control access to the system and manage the user base. |
| **M4** | Manage Courses & Categories | Staff, Admin, Owner | Staff/Admin | create, edit, and categorize courses | I can structure and organize the educational offerings of the platform. |
| **M5** | Manage Own Courses | Instructor | Instructor | create and manage the courses that I am assigned to teach | I can build and structure my educational content. |
| **M6** | Manage Course Materials | Instructor | Instructor | upload and organize materials (like files, videos, links) | I can provide learning resources to my students. |
| **M7** | Manage Enrolled Students | Instructor | Instructor | view and manage the list of students in my courses | I can track who is participating in my course. |
| **M8** | View Course Catalog | Student | Student | view a catalog of all available courses | I can discover and choose new courses to enroll in. |
| **M9** | Enroll in Course | Student | Student | enroll in a course from the catalog | I can gain access to its materials and activities. |
| **M10** | Access Course Materials | Student | Student | view and access all materials for an enrolled course | I can study and learn the subject matter. |
| **M11** | View Grades & Progress | Student | Student | view my grades and completion progress in a course | I can track my performance and see how I am doing. |
| **M12** | User Logout | All Roles | user | log out of the system | I can securely end my session. |

---

### **2. Should-Have (S)**

These stories enhance the assessment, interactivity, and formal recognition capabilities of the LMS.

| ID | User Story | Role(s) | As a(n)... | I want to... | So that... |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **S1** | Manage Assignments | Instructor | Instructor | create and manage assignments with due dates | I can give students tasks to complete for evaluation. |
| **S2** | Submit Assignments | Student | Student | submit my work for an assignment | I can get it graded by the instructor. |
| **S3** | Manage Exams/Quizzes | Instructor | Instructor | create and manage exams or quizzes for a course | I can formally assess my students' knowledge. |
| **S4** | Take Exams/Quizzes | Student | Student | take an exam or quiz for a course I'm enrolled in | I can demonstrate my understanding and receive a grade. |
| **S5** | Grade Submissions | Instructor | Instructor | view student submissions and provide grades/feedback | I can evaluate student work and help them improve. |
| **S6** | Monitor Student Progress | Instructor | Instructor | monitor the progress and performance of individual students | I can identify who is struggling and offer support. |
| **S7** | Participate in Forums | Student, Instructor | user | participate in discussion forums for a course | I can ask questions and interact with peers and instructors. |
| **S8** | Download Certificates | Student | Student | download a certificate upon course completion | I have proof that I have successfully finished the course. |

---

### **3. Could-Have (C)**

These are desirable features that would improve user experience and provide advanced insights.

| ID | User Story | Role(s) | As a(n)... | I want to... | So that... |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **C1** | View Dashboard & Reports | Owner, Admin, Staff, Instructor | user | view a dashboard with analytics and generate reports | I can gain insights into engagement and overall system usage. |
| **C2** | Course Reviews and Ratings | Student | Student | rate and write reviews for courses I have completed | I can help other students make informed decisions. |
| **C3** | Student-to-Student Messaging | Student | Student | send direct messages to other students in my course | I can collaborate on projects or form study groups. |

---

### **4. Won't-Have (W)**

These functionalities are explicitly out of scope for this development phase.

| ID | User Story | Notes |
| :--- | :--- | :--- |
| **W1** | E-Commerce Integration | Selling courses and handling payments are outside the scope of this system. |
| **W2** | Live Video Conferencing | Real-time video-based classes or webinars are not part of the current scope. |
| **W3** | Gamification Elements | Features like badges, leaderboards, or points for course activities are not planned. |
| **W4** | Advanced Content Authoring | An integrated tool to build complex interactive content (like SCORM packages) is not included. |
