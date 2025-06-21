# User Story Documentation for E-Commerce System

This document outlines the user stories for the E-Commerce subsystem. These stories are derived from the functionalities available to "Customer," "Admin," "Owner," and "Staff" user roles, as detailed in the provided use case and entity-relationship diagrams.

---

### **MoSCoW Prioritization Overview**

The user stories are categorized using the MoSCoW method to guide the development lifecycle:

* **Must-Have (M):** Absolutely critical functionalities for the e-commerce platform to operate. The system cannot launch without these.
* **Should-Have (S):** Important functionalities that add significant value but are not essential for the initial launch.
* **Could-Have (C):** Desirable features that are less important and can be implemented if time and resources permit.
* **Won't-Have (W):** Functionalities that are explicitly out of scope for the current development phase of this subsystem.

---

### **1. Must-Have (M)**

These user stories represent the core transaction cycle of the E-Commerce system.

| ID    | User Story               | Role(s)                        | As a(n)...      | I want to...                                                                   | So that...                                                                   |
| :---- | :----------------------- | :----------------------------- | :-------------- | :----------------------------------------------------------------------------- | :--------------------------------------------------------------------------- |
| **M1** | Customer Registration    | Customer                       | new user        | register for an account                                                        | I can make purchases and track my orders.                                    |
| **M2** | User Login               | Customer, Admin, Owner, Staff  | user | log in to the system with my credentials                                       | I can access my role-specific functionalities.                               |
| **M3** | Browse & Search Products | Customer                       | Customer        | browse product categories and search for specific items                        | I can find the products I want to buy.                                       |
| **M4** | View Product Details     | Customer                       | Customer        | view detailed information, images, and the price of a product                  | I can make an informed decision before purchasing.                           |
| **M5** | Manage Shopping Cart     | Customer                       | Customer        | add products to my shopping cart, update quantities, and remove items          | I can prepare my order before proceeding to payment.                         |
| **M6** | Checkout and Payment     | Customer                       | Customer        | go through a checkout process and submit payment for the items in my cart      | I can complete my purchase successfully.                                     |
| **M7** | View Order History       | Customer                       | Customer        | view a list of my past and current orders and their status                     | I can keep track of my purchases.                                            |
| **M8** | Manage Products          | Admin, Owner                   | Admin/Owner     | add, edit, and delete products, including their name, description, price, and images | I can manage the product catalog available to customers.                     |
| **M9** | Manage Inventory         | Admin, Owner                   | Admin/Owner     | update the stock quantity for products                                         | we can accurately reflect product availability and prevent overselling.      |
| **M10** | Manage Orders            | Admin, Owner                   | Admin/Owner     | view all customer orders and their details                                     | I can oversee and manage the fulfillment process.                            |
| **M11** | Process Orders           | Staff                          | Staff           | confirm or reject new orders                                                   | I can process incoming orders to move them to the next stage of fulfillment. |
| **M12** | User Logout              | All Roles                      | user            | log out of the system                                                          | I can securely end my session.                                               |

---

### **2. Should-Have (S)**

These stories add significant value to the user experience and administrative control.

| ID    | User Story                 | Role(s)      | As a(n)...   | I want to...                                                                   | So that...                                                                   |
| :---- | :------------------------- | :----------- | :----------- | :----------------------------------------------------------------------------- | :--------------------------------------------------------------------------- |
| **S1** | Write Product Reviews      | Customer     | Customer     | write reviews and provide ratings for products I have purchased                | I can share my feedback with other potential buyers.                         |
| **S2** | Manage Product Reviews     | Admin, Owner | Admin/Owner  | view and manage (approve, delete) customer product reviews                     | I can ensure the reviews are appropriate and authentic.                      |
| **S3** | Manage Promotions          | Admin, Owner | Admin/Owner  | create and manage discount codes and promotions (e.g., percentage off, fixed amount) | I can run marketing campaigns to attract customers and increase sales.       |
| **S4** | Apply Discounts            | Customer     | Customer     | apply a discount or coupon code during checkout                                | I can get a better price on my purchase.                                     |
| **S5** | Request Returns/Refunds    | Customer     | Customer     | request a return or refund for an order                                        | I can get my money back for a product that didn't meet my expectations.      |
| **S6** | Manage Returns/Refunds     | Admin, Owner | Admin/Owner  | view and process customer requests for returns or refunds                      | I can manage the post-purchase customer experience and finances.             |
| **S7** | Manage User Accounts       | Admin        | Admin        | view and manage all user accounts in the system                                | I can handle customer support issues or manage system access.                |
| **S8** | Manage Product Categories  | Admin, Owner | Admin/Owner  | create, edit, and delete product categories                                  | I can organize the product catalog logically for easier browsing.            |
| **S9** | Manage Profile             | All Roles    | user         | manage my own profile information (e.g., name, password, address)              | I can keep my personal details and shipping information up to date.          |

---

### **3. Could-Have (C)**

These are desirable features that can be implemented in future iterations.

| ID    | User Story                     | Role(s)      | As a(n)...   | I want to...                                                                   | So that...                                                                   |
| :---- | :----------------------------- | :----------- | :----------- | :----------------------------------------------------------------------------- | :--------------------------------------------------------------------------- |
| **C1** | View Dashboard & Reports       | Admin, Owner | Admin/Owner  | view a dashboard with sales analytics and generate reports (e.g., top-selling products, revenue over time) | I can gain business intelligence to make strategic decisions.                |
| **C2** | Advanced Search Filters        | Customer     | Customer     | filter products by price, category, rating, and other attributes               | I can narrow down my search results to find exactly what I need more quickly.|
| **C3** | Wishlist Functionality         | Customer     | Customer     | save products to a personal wishlist                                           | I can keep track of items I'm interested in buying later.                    |
| **C4** | Automated Order Status Emails  | Customer     | Customer     | receive email notifications when my order status changes (e.g., confirmed, shipped, delivered) | I am proactively kept informed about my order's progress.                    |

---

### **4. Won't-Have (W)**

These functionalities are explicitly out of scope for the E-Commerce subsystem.

| ID    | User Story                   | Notes                                                                                                |
| :---- | :--------------------------- | :--------------------------------------------------------------------------------------------------- |
| **W1** | Core CMS Features            | Page creation, general content management, and other features belonging to the main Content Management System. |
| **W2** | Learning Management Features | Any functionality related to courses, lessons, or student progress, as this belongs to the LMS subsystem.    |
| **W3** | Multi-Vendor Marketplace     | The current scope is for a single-owner e-commerce store, not a marketplace where multiple vendors can sell products. |
| **W4** | Subscription-Based Services  | The system is designed for one-time purchases, not recurring subscriptions.                          |
