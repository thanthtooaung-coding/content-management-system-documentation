# User Story Documentation for Learning Management System (LMS)

This document outlines the user stories for the Learning Management System (LMS) subsystem. The stories are derived from the functionalities available to "Student," "Instructor," "Admin," "Owner," and "Staff" user roles, as detailed in the provided use case and entity-relationship diagrams.

---

### **MoSCoW Prioritization Overview**

The user stories are categorized using the MoSCoW method to guide the development lifecycle:

* **Must-Have (M):** Core functionalities essential for the LMS to be viable. The system cannot function without them.
* **Should-Have (S):** High-value features that are important but not critical for the initial launch.
* **Could-Have (C):** Desirable but less important features that can be added if time and resources allow.
* **Won't-Have (W):** Functionalities explicitly out of scope for the current development phase of the LMS.

---

### **1. Must-Have (M)**

These user stories define the fundamental learning and teaching loop of the LMS.

| ID     | User Story                   | Role(s)                | As a(n)...  | I want to...                                          | So that...                                               |
| :----- | :--------------------------- | :--------------------- | :---------- | :---------------------------------------------------- | :------------------------------------------------------- |
| **M1** | User Login                   | All Roles              | user        | log in to the system with my credentials              | I can access my dashboard and role-specific features.    |
| **M2** | Manage Courses (Admin)       | Admin, Owner           | Admin/Owner | create, edit, and manage all courses in the system    | I can oversee the educational offerings of the platform. |
| **M3** | Manage Own Courses           | Instructor             | Instructor  | create and manage the courses that I am assigned to   | I can build and structure my educational content.        |
| **M4** | Manage Course Materials      | Instructor             | Instructor  | upload and organize course materials (like files, links) | I can provide learning resources to my students.         |
| **M5** | View Course Catalog          | Student                | Student     | view a catalog of all available courses               | I can discover and choose courses to enroll in.          |
| **M6** | Enroll in Course             | Student                | Student     | enroll in a course from the catalog                   | I can gain access to its materials and activities.       |
| **M7** | View Course Materials        | Student                | Student     | view and access all materials for a course I'm enrolled in | I can study and learn the subject matter.              |
| **M8** | Manage Enrolled Students     | Instructor             | Instructor  | view a list of students enrolled in my courses        | I can see who is taking my course.                       |
| **M9**| View Progress                 | Student                | Student     | view my progress for my enrolled courses              | I can see how I am doing.                                |
| **M10**| User Logout                  | All Roles              | user        | log out of the system                                 | I can securely end my session.                           |

---

### **2. Should-Have (S)**

These stories enhance the interactivity, assessment, and administrative capabilities of the LMS.

| ID     | User Story                   | Role(s)                | As a(n)...  | I want to...                                          | So that...                                               |
| :----- | :--------------------------- | :--------------------- | :---------- | :---------------------------------------------------- | :------------------------------------------------------- |
| **S1** | Manage Assignments           | Instructor             | Instructor  | create and manage assignments with due dates          | I can give students tasks to complete for evaluation.    |
| **S2** | Submit Assignments           | Student                | Student     | submit my work for an assignment                      | I can get it graded by the instructor.                   |
| **S3** | Manage Exams/Quizzes         | Instructor             | Instructor  | create, manage, and schedule exams or quizzes for a course | I can assess my students' knowledge.                     |
| **S4**| Take Exams/Quizzes            | Student                | Student     | take an exam or quiz for a course I'm enrolled in     | I can demonstrate my understanding and get a grade.      |
| **S5**| View Grades                   | Student                | Student     | view my grades for my enrolled courses                | I can track my performance how I am doing.               |
| **S6** | Grade Submissions            | Instructor             | Instructor  | view student submissions and provide grades/feedback  | I can evaluate student work and help them improve.       |
| **S7** | Monitor Student Progress     | Instructor             | Instructor  | monitor the progress and performance of my students   | I can identify who is struggling and offer help.         |
| **S8** | Participate in Forums        | Student, Instructor    | user        | participate in discussion forums for a course         | I can ask questions and interact with peers and instructors.|
| **S9** | Manage Course Categories     | Admin, Owner           | Admin/Owner | create and manage course categories                   | I can organize the course catalog for easy navigation.   |
| **S10** | Manage User Accounts         | Admin                  | Admin       | create, edit, and manage all user accounts (Students, Instructors) | I can control access to the system and manage the user base. |
| **S11** | Download Certificates        | Student                | Student     | download a certificate upon course completion         | I have proof that I have successfully finished the course. |
| **S12** | Manage Profile               | All Roles              | user        | manage my own profile information                     | I can keep my personal details current.                  |

---

### **3. Could-Have (C)**

These are desirable features that would improve the user experience and provide more advanced analytics.

| ID     | User Story                   | Role(s)                | As a(n)...  | I want to...                                          | So that...                                               |
| :----- | :--------------------------- | :--------------------- | :---------- | :---------------------------------------------------- | :------------------------------------------------------- |
| **C1** | View Dashboard & Reports     | Admin, Owner, Instructor | Admin/Owner/Instructor | view a dashboard with analytics and generate reports | I can gain insights into course popularity, student engagement, and overall system usage. |
| **C2** | Student-to-Student Messaging | Student                | Student     | send direct messages to other students in my course   | I can collaborate on projects or form study groups.      |
| **C3** | Course Reviews and Ratings   | Student                | Student     | rate and write reviews for courses I have completed   | I can help other students make informed decisions about which courses to take. |

---

### **4. Won't-Have (W)**

These functionalities are explicitly out of scope for the LMS subsystem.

| ID     | User Story                  | Notes                                                                                             |
| :----- | :-------------------------- | :------------------------------------------------------------------------------------------------ |
| **W1** | E-Commerce Integration      | Selling courses, handling payments, and other e-commerce functions belong to the ECS subsystem.      |
| **W2** | Core CMS Features           | General-purpose page creation and content management belong to the main CMS.                       |
| **W3** | Live Video Conferencing     | Real-time video-based classes or webinars are not part of the current scope.                       |
| **W4** | Gamification Elements       | Features like badges, leaderboards, or points for course activities are not planned for this phase. |
