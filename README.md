# Expense Tracker


The **Expense Tracker** is a web-based application designed to help users track and manage their daily expenses effortlessly. Built using the powerful **MERN stack** (MongoDB, Express.js, React.js, and Node.js), this system provides a scalable, responsive, and user-friendly platform for users to gain detailed insights into their spending patterns, optimize their budgets, and make smarter financial decisions.

---

## 🎯 Objectives

- **Simplify expense tracking** for both individuals and organizations.
- Provide **detailed insights** into spending patterns for better financial management.
- Enable management of **expenses and categories** (create, update, delete).
- Generate **comprehensive reports** based on user-defined time periods and categories.

---

## 🛠 Features

### 1. User Authentication and Authorization
- **Sign Up / Log In**: Secure user authentication with email/password login.
- **Role-based Access Control**: Administrative tasks can only be performed by users with admin roles.

### 2. Expense and Category Management
- **Create, Update, Delete**: Manage your expense entries and categories.
- **Expense Tracking**: Track your expenses by date, category, and description.
- **Receipt Upload**: Attach receipts or documents to each expense entry.

### 3. Dashboard and Reporting
- **Visual Dashboard**: Overview of your expenses, including total, categorized expenses, and recent transactions.
- **Comprehensive Reports**: Generate reports filtered by date and category, displayed through pie charts and bar graphs.

### 4. Responsive User Interface
- **Mobile-First**: A clean, responsive UI optimized for desktop, tablet, and mobile devices.
- **React.js**: Reusable UI components, smooth state management, and a seamless user experience.

---

## ⚙ Technical Architecture

### Frontend
- **React.js**: Building a dynamic, responsive user interface.
- **Libraries**:
  - **Tsparticle**: For awesome background effects.
  - **React-datepicker**: For easy date selection.
  - **Unique-names-generator**: For generating random unique names.
  - **Moment.js**: For date manipulation.
- **Responsive Design**: Using Bootstrap and Material-UI for a sleek, mobile-friendly design.

### Backend
- **Node.js & Express.js**: RESTful API handling client requests and backend logic.
- **Authentication**: Implemented JSON Web Tokens (JWT) for secure user authentication and authorization.
- **Middleware**: Protect sensitive endpoints with custom middleware.

### Database
- **MongoDB**: A NoSQL database to store all data (user info, expenses, categories).
- **Mongoose ORM**: For schema definition, validation, and easy querying of MongoDB.

---

## 🌐 Deployment

- **Frontend**: Deployed on **AWS**, ensuring fast load times and a secure, scalable environment.
- **Backend**: Deployed on **Render**, providing a reliable backend infrastructure.
- **CI/CD Pipeline**: Set up automated Continuous Integration and Continuous Deployment for smooth updates.

---

