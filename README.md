Software Requirements Specification (SRS) 
Online Food Delivery System (IEEE Format) 
1. Introduction 

1.1 Purpose 
The purpose of this SRS document is to define the functional and non-functional requirements 
for the Online Food Delivery System. This system enables customers to browse restaurants, 
place online food orders, make payments, and track deliveries in real-time. It also supports 
restaurant owners and delivery personnel in managing menus, orders, and delivery status. 

1.2 Scope 
The system allows customers to order food from multiple restaurants, make secure payments, 
track their orders, and provide ratings. Restaurants can manage menus, accept or reject orders, 
and assign delivery personnel. Delivery personnel can update delivery status and view assigned 
orders. The system ensures secure, efficient, and scalable order processing. 

1.3 Definitions, Acronyms, and Abbreviations 
 OFD – Online Food Delivery 
 ETA – Estimated Time of Arrival 
 API – Application Programming Interface 
 POS – Point of Sale 
 Payment Gateway – Third-party system for processing online transactions 

2. Overall Description 

2.1 Product Perspective 
The Online Food Delivery System is a web/mobile-based application consisting of three main 
components: 
 Frontend: Web and mobile user interfaces for customers, restaurants, and delivery 
personnel. 
 Backend: Application server handling business logic, payment processing, and database 
operations. 
 External Systems: Payment gateway, notification service (SMS/Email), and map/GPS 
service. 

2.2 User Classes and Characteristics 
User Class 
Description 
Customer 
Browses restaurants, places orders, makes payments, tracks delivery. 
Restaurant Owner/Staff Manages menu, accepts orders, monitors kitchen operations. 
Delivery Personnel 
Accepts delivery jobs and updates order delivery status. 
System Administrator Manages user accounts, system configuration, and monitors performance. 

2.3 Operating Environment 
 Web Browser (Chrome, Firefox, Edge) 
 Mobile Devices (Android/iOS) 
 Backend Server (Linux-based environment) 
 Database (MySQL/PostgreSQL) 
 Payment Gateway (Stripe, PayPal, etc.) 

2.4 Constraints 
 Must comply with digital payment and data protection regulations. 
 Requires stable internet connection for real-time tracking. 
 Payment gateway downtime may temporarily limit online payments. 

3. Functional Requirements 

3.1 Customer Functions 
 Description 
1 System shall allow customers to browse restaurants and available menus. 
2 System shall allow customers to place online food orders. 
3 System shall provide multiple payment options such as card, wallet, and COD. 
4 System shall allow customers to track order and delivery status in real time. 
5 System shall allow customers to rate food and delivery services. 
 
3.2 Restaurant Functions 
 Description 
1 System shall allow restaurants to manage menus (add, edit, delete items). 
2 System shall allow restaurants to accept or reject customer orders. 
3 System shall allow restaurants to assign delivery personnel. 
 
3.3 Delivery Personnel Functions 
 Description 
1 System shall allow delivery personnel to view assigned orders. 
2 System shall allow delivery personnel to update delivery status (Picked, On the way, Delivered). 

3.4 System Functions 
 Description 
1 System shall maintain an order history for all users. 
2 System shall integrate with a secure payment gateway for processing payments. 
3 System shall send notifications (Email/SMS/push) for order updates. 
 
4. Non-Functional Requirements 
4.1 Performance Requirements 
 
Description 
1 The system shall support at least 500 concurrent users without performance degradation. 
2 Payment processing shall complete within 5 seconds. 

4.2 Security Requirements 
 
Description 
1 All sensitive data shall be encrypted using AES-256 or TLS 1.2+. 
2 The system shall require authentication for all user roles. 
3 System shall comply with PCI-DSS standards for handling payment data. 
4.3 Usability Requirements 
 
Description 
1 The user interface shall be simple and mobile-friendly. 
2 System shall support multilingual options. 

4.4 Reliability & Availability 
 
Description 
1 The system shall ensure 99.9% uptime for ordering services. 
2 The system shall recover from failures within 2 minutes.
