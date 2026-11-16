🏥 SmartCare
Smart Hospital Management System
A centralized digital platform for smarter, faster and more efficient hospital operations.

     

📖 About SmartCare
SmartCare – Hospital Management System is a web-based application developed to digitize and streamline essential hospital operations through a centralized platform.

Traditional hospital operations often involve manual record keeping, disconnected information and difficulties in coordinating different activities. SmartCare aims to address these challenges by integrating multiple hospital functions into one application.

The system provides modules for managing patients, doctors, departments, appointments, wards, medical records, prescriptions, medicines, billing and payments.

Beyond basic hospital management, SmartCare demonstrates the practical implementation of Operating System and Database Management System concepts, including synchronization, scheduling, transaction management, concurrency control and deadlock handling.

The project combines web development, database engineering and operating system concepts to create a practical academic software solution.

🎯 Project Objectives
Digitize essential hospital operations.
Maintain organized and centralized hospital records.
Simplify patient registration and appointment booking.
Improve ward allocation and capacity management.
Provide controlled access to shared family health information.
Maintain activity history through an audit trail.
Demonstrate real-world applications of OS and DBMS concepts.
Ensure data consistency during concurrent database operations.
✨ Key Features
Hospital Operations
Module	Description
Dashboard	Displays important hospital statistics and information
Patient Management	Register, view and manage patient records
Doctor Management	Maintain doctor details and specializations
Department Management	Organize hospital departments
Appointment Management	Schedule and manage patient appointments
Ward Management	Manage wards, capacity and patient assignments
Medical Records	Maintain patient medical information
Prescriptions	Manage prescribed medicines
Medicine Management	Maintain medicine-related information
Billing	Generate and manage patient bills
Payments	Manage payment records
Advanced Functionalities
Family Health Sharing

Send and manage family health-sharing invitations.
Provide controlled access to shared health information.
Manage permissions and access revocation.
Audit Trail

Maintain records of important application activities.
Track changes and operations for better accountability.
Live Appointment Queue Analytics

Manage appointment queues.
Demonstrate FCFS and Priority Scheduling.
Display queue-related information.
Concurrency Control

Protect critical operations against conflicting concurrent updates.
Maintain correct ward capacity using database transactions and row-level locking.
🏗️ System Architecture
SmartCare follows a three-tier architecture.

       PRESENTATION LAYER
     HTML + CSS + JavaScript
               |
               | HTTP / REST API
               |
       APPLICATION LAYER
          Python Flask
               |
        Business Logic
        API Endpoints
        Validation
               |
               | SQL Queries
               |
         DATABASE LAYER
             MySQL
               |
      Relational Database
Architecture Components
Layer	Technology	Responsibility
Presentation	HTML, CSS, JavaScript	User interface and interaction
Application	Python Flask	APIs, business logic and validation
Database	MySQL	Data storage, relationships and transactions
🗄️ Database Design
The database is designed around 12 main hospital tables to organize and manage hospital information.

The database design uses:

Primary Keys
Foreign Keys
One-to-One Relationships
One-to-Many Relationships
SQL Joins
Constraints
Normalization Principles
Transaction Management
Referential Integrity
The database is structured to reduce unnecessary data duplication and maintain consistency across related hospital records.

⚙️ Operating System Concepts Implementation
One of the important aspects of SmartCare is the practical implementation of Operating System concepts.

OS Concept	Implementation in SmartCare
Mutex Lock	Synchronization during ward assignment within a Flask process
Semaphore	Restricts concurrent appointment operations to three within a Flask process
FCFS Scheduling	Appointment queue processing
Priority Scheduling	Priority-based appointment handling
Deadlock Handling	Demonstration of MySQL deadlock detection and transaction rollback
These implementations demonstrate how synchronization and scheduling concepts can be applied to real-world application workflows.

🔐 DBMS Concepts Implementation
SmartCare demonstrates important database concepts through practical implementation:

Transactions

Database transactions are used to maintain consistency during important operations, such as assigning patients to wards.

ACID Properties

Atomicity
Consistency
Isolation
Durability
Concurrency Control

Row-level locking using MySQL SELECT ... FOR UPDATE helps prevent conflicting updates during simultaneous ward assignments.

Deadlock Handling

The project includes a practical MySQL deadlock demonstration in which a deadlock is detected and the affected transaction is rolled back.

Normalization

Database design follows normalization principles to organize relational data and reduce redundancy.
