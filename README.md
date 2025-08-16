# E-Shift-good-transfer-management-system
This is a windows form application for managing the good transfer of E-Shift with c# and sql databse.

System Overview
The E-Shift Goods Transfer Management System is a Windows-based application developed to address the operational needs of e-Shift, a household goods transportation company. The system is designed to streamline daily logistics activities such as job scheduling, transport unit assignment, customer communication, and employee coordination. Built using C# with a graphical user interface (GUI), the application supports multiple user roles including Admin, Customer, and Employee (Driver or Assistant), each with access to role-specific functionalities.
By integrating job booking, load management, resource allocation, and real-time feedback into a centralized platform, the system enables e-Shift to reduce manual errors, improve job turnaround times, and enhance customer satisfaction. The application uses a structured database to store and manage data, allowing secure access, reliable updates, and meaningful report generation.
Login & User Authentication
The system begins with a secure login process where each user is required to provide valid credentials. Based on the role Admin, Customer, or Employee the user is directed to their respective dashboard. Role-based authentication ensures that each user can only access the modules assigned to them, enhancing security and functionality segregation.
Admin Interface
The Admin Dashboard serves as the main control panel of the system. It provides an overview of the company’s transport operations, including active jobs, resource availability, pending tasks, and overall activity statistics. Admin users have the ability to manage all other system entities and interact with both customers and employees.
The Admin functionalities include:
•	Customer Management: Add, view, edit, or remove customer records to keep the customer database up to date.
•	Employee Management: Manage drivers and assistants by recording personal and professional details.
•	Job Management: View customer job requests, approve or decline them, assign transport units, and update job statuses.
•	Transport Unit Management: Create and assign transport units made up of lorries, drivers, assistants, and containers.
•	Load Management: Add and manage product load details such as weight, volume, and descriptions.
•	Lorry & Container Management: Maintain details like plate numbers, capacity, and dimensions for planning purposes.
•	Notification Management: Send system-generated messages or updates to customers and employees.
•	Report Generation: Generate printable and exportable reports on job performance, user activities, and completed tasks.
•	Feedback View: Review and respond to customer feedback for service improvement.
Customer Interface
Customers access the system through a registration form and secure login. Once logged in, they are presented with a personalized dashboard that displays job statuses, load progress, and options to manage their profile or submit queries.
The Customer functionalities include:
•	Registration Form: Submit personal details (NIC, contact, email, address) to create an account.
•	Customer Dashboard: View active and past transport jobs, along with relevant job status updates.
•	Job Management: Submit new job requests and monitor job statuses such as pending, approved, or completed.
•	Profile Management: Update personal and contact information.
•	Enquiry System: Submit service-related queries and receive responses from admins.
•	Feedback Submission: Provide feedback or ratings after job completion to evaluate service quality.
Employee Interface
Drivers and assistants (employees) also have dedicated access to the system. Upon logging in, they are presented with a dashboard that displays assigned tasks, route information, and scheduling details for the day.
The Employee functionalities include:
•	Employee Dashboard: View upcoming assignments, job schedules, and delivery locations.
•	Profile Management: Manage personal details; for drivers, license and assigned vehicle details are also included.
•	Task Details: View assigned jobs and associated load and route information.
Database Design Summary
The E-Shift system uses a relational database structure, incorporating primary and foreign keys to manage relationships between different entities. This ensures data integrity, easy access, and simplified data retrieval for all modules. The key entities and their relationships include:
•	Customer: Stores customer details linked to job requests.
•	Job: Records all transport requests, connecting customers and loads.
•	Load: Manages product details such as weight, volume, and description tied to specific jobs.
•	Transport Unit: Combines resources including lorry, driver, assistant, and container for each job.
•	Lorry, Driver, Assistant, Container: Individual entities with capacity and identification details.
•	Enquiry and Feedback: Used for customer engagement and quality control.
•	User: Manages login credentials and role-based access across all system users.
The E-Shift Goods Transfer Management System will be a robust and efficient logistics software solution that fulfils the operational needs of the e-Shift transport company. It will provide clearly defined user roles, intuitive interfaces, and centralized management of customers, employees, transport resources, and feedback. The system will be ensuring that each transport operation is properly scheduled, tracked, and recorded improving transparency and customer satisfaction. With the added ability to generate analytical reports and manage employee roles, the system will be laying a strong foundation for operational excellence and future scalability.
