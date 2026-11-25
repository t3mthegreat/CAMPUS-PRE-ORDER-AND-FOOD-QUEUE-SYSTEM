PRODUCT REQUIREMENTS DOCUMENT (PRD)

CAMPUS PRE-ORDER AND FOOD QUEUE SYSTEM

Course: COS 209
Group: Group 8
Institution: Babcock University
Target Users: Students and Campus Food Vendors

1. Introduction/Product overview

The Campus Pre-Order and Food Queue System is a web-based platform designed to help students order food from campus vendors without spending time standing in queues.

Students will be able to view available food vendors, check their menus, place orders and monitor their order statuses. Vendors will also be able to receive and manage orders through the system.

2. Problem Statement

Long queues are a common problem when students want to buy food on campus, especially during lunch breaks. Students sometimes spend too much time waiting, which can affect their lectures and other activities.

Food vendors also find it difficult to attend to many customers at the same time. This project aims to make the food ordering process easier for both students and vendors.

3. Project Objectives

The system is expected to:

1. Reduce the time students spend waiting for food.
2. Make ordering food easier.
3. Help vendors manage orders properly.
4. Allow students to check their order statuses.
5. Prevent food wastage from unclaimed orders through pre-order payment.
6. Provide real-time updates on food availability.
7. Improve communication between students and vendors.

4. Target Users

* Students: They will use the platform to view menus, order food and track their orders.
* Food Vendors: They will receive orders, update their statuses, and update their menu.
* Administrators: They will manage users and monitor the system.

5. Research and Investigation

We gathered information from students and food vendors through interviews to understand the problems they experienced when buying and selling food on campus.

5.3 Research Questions

The group will also investigate:

1. How long do students normally wait before getting their food?
2. What time of the day are queues usually longer?
3. What problems do vendors face when attending to customers?
4. Would students be interested in ordering food online?

6. Proposed Solution

We propose developing a web application that connects students with food vendors on campus.

Students will be able to:

* Create an account and log in.
* View food vendors and their menus.
* Select and order food.
* View the vendor's bank account details.
* Pay for the order once accepted.
* Provide payment receipts.
* Get an order ID.
* Check their order status.

Vendors will be able to:

* Log in to their accounts.
* Provide bank details for receiving payments.
* Upload and update food menus.
* Receive and accept customer orders.
* Verify payments.
* Update order status.
* Cancel unpaid orders.
* Reject incomplete or unavailable orders.

7. Minimum Viable Product (MVP)

The first version of the system will include:

1. Student registration and login.
2. Vendor registration and login.
3. List of available food vendors.
4. Food menus.
5. Food ordering.
6. Payment procedure.
7. Order ID generation.
8. Order status tracking.
9. Vendor dashboard.
10. Administrator dashboard.

8. Programming Language and Technologies

Selected Programming Language: JavaScript

We chose JavaScript because it can be used to develop both the frontend and backend of the application. It also supports interactive websites and has different tools that can make development easier.

Component	Technology
Frontend	HTML, CSS and JavaScript
Backend	Node.js and Express.js
Database	PostgreSQL
Code Editor	Visual Studio Code
Version Control	GitHub

9. System Workflow

Student: Login - Select Vendor - View Menu - Place Order - Get pending order ID - Vendor accepts - Make payment - Indicate Payment Success - Get Confirmed Order ID - Track Order Status - Collect Food.

Vendor: Login - Receive Order with Order ID- Accept Order - Verify Payment - Prepare Food - Update Status - Complete Order.

10. Project Scope

The system will focus on food ordering and order management for food vendors within the university.

Accepted orders that are not paid for within 10 minutes are automatically cancelled, and finished orders that have been paid for cannot be refunded if the student fails to pick them up.

Features such as food delivery and advanced analytics may be added in the future.

11. Success Criteria

We will measure the success of the system by looking at:

* How much waiting time is reduced.
* Number of students using the platform.
* Number of vendors registered.
* Number of orders completed successfully.
* Feedback from students and vendors.

12. Conclusion

The Campus Pre-Order and Food Queue System is intended to make buying food on campus easier and faster. It will help students avoid unnecessary waiting and allow food vendors to organize their orders better.

The project will be developed as a web application using JavaScript and the other technologies listed above.
