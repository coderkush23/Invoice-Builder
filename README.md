# **Invoice Builder**

## **Overview**
The **Invoice Builder** is a full-stack application designed to help individuals and small businesses efficiently manage invoices and client data. It enables users to create, edit, and track invoices, manage client information, and generate reports, all through a modern and user-friendly interface.

---

## **Key Features**
- **User Authentication:**
  - Secure sign-up and login.
- **Invoice Management:**
  - Create, view, update, and delete invoices.
  - Track invoice statuses (Paid, Pending).
- **Client Management:**
  - Add, edit, and delete client details.
- **Payment Tracking:**
  - Record payments and view outstanding amounts.
- **Reports:**
  - Analyze revenue and unpaid invoices with filters for date ranges.
- **Dashboard:**
  - Overview of total invoices, outstanding payments, and paid amounts.
- **Responsive Design:**
  - Accessible from desktops and mobile devices.

---

## **System Architecture**
- **Front-End:** ReactJS  
  - Interactive UI for seamless navigation and user experience.
- **Back-End:** ASP.NET Web API  
  - RESTful APIs for managing invoices, clients, and user data.
- **Database:** SQL Server  
  - Secure storage for structured data.

---

## **Installation and Setup**

### **Prerequisites**
- **Node.js** (for running the React application)
- **SQL Server** (for the database)
- **.NET SDK** (for running the back-end)

### **Steps to Run the Project**
1. **Set Up the Database**  
   Create the database using the SQL structure provided in the `database/structure.sql` file.

2. **Run the Back-End**   
   cd backend
   dotnet restore
   dotnet run

The server will start on `http://localhost:5000`.

## **Run the Front-End**
cd frontend
npm install
npm start
