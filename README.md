Invoice Builder
Overview
The Invoice Builder is a full-stack application designed to help individuals and small businesses efficiently manage invoices and client data. It enables users to create, edit, and track invoices, manage client information, and generate reports, all through a modern and user-friendly interface.

Key Features
User Authentication:
Secure sign-up and login.
Invoice Management:
Create, view, update, and delete invoices.
Track invoice statuses (Paid, Pending).
Client Management:
Add, edit, and delete client details.
Payment Tracking:
Record payments and view outstanding amounts.
Reports:
Analyze revenue and unpaid invoices with filters for date ranges.
Dashboard:
Overview of total invoices, outstanding payments, and paid amounts.
Responsive Design:
Accessible from desktops and mobile devices.
System Architecture
Front-End: ReactJS
Interactive UI for seamless navigation and user experience.
Back-End: ASP.NET Web API
RESTful APIs for managing invoices, clients, and user data.
Database: SQL Server
Secure storage for structured data.
Installation and Setup
Prerequisites
Node.js (for running the React application)
SQL Server (for the database)
.NET SDK (for running the back-end)
Steps to Run the Project
1. Set Up the Database
Create the database using the SQL structure provided in the database/structure.sql file.
2. Run the Back-End
bash
Copy code
cd backend
dotnet restore
dotnet run
The server will start on http://localhost:5000.

3. Run the Front-End
bash
Copy code
cd frontend
npm install
npm start
The front-end will run on http://localhost:3000.

API Documentation
Authentication
POST /api/users/signup
Register a new user.
POST /api/users/login
Authenticate user credentials.
Invoices
GET /api/invoices
Fetch all invoices.
POST /api/invoices
Create a new invoice.
PUT /api/invoices/{id}
Update an existing invoice.
DELETE /api/invoices/{id}
Delete an invoice.
Clients
GET /api/clients
Fetch all clients.
POST /api/clients
Add a new client.
PUT /api/clients/{id}
Update a client.
DELETE /api/clients/{id}
Delete a client.
Payments
POST /api/payments
Record a payment.
GET /api/payments
Fetch payment history.
Folder Structure
Front-End
css
Copy code
frontend/
  ├── src/
      ├── components/
      ├── pages/
      ├── services/
Back-End
Copy code
backend/
  ├── Controllers/
  ├── Models/
  ├── Data/
Database
vbnet
Copy code
database/
  ├── structure.sql
Future Enhancements
Add multi-user support with role-based permissions.
Include invoice templates for PDF generation.
Enhance reporting features with charts and graphs.
Contributors
Kaushal - Full-stack Developer
