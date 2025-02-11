# Ecommerce-Follow-Along

Welcome to the Ecommerce Follow-Along project, a hands-on journey to build a full-fledged E-Commerce Application from scratch using the MERN stack (MongoDB, Express.js, React.js, and Node.js).

## Table of Contents
- [Project Overview](#project-overview)
- [Milestone 1: Project Overview](#milestone-1-project-overview)
- [Milestone 2: Project Setup and Login Page](#milestone-2-project-setup-and-login-page)
- [Milestone 3: Project Setup for Backend](#milestone-3-project-setup-for-backend)
- [Milestone 4: Creating User Model and Controller](#milestone-4-creating-user-model-and-controller)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [License](#license)

## Project Overview
The goal of this project is to provide a real-world experience in building a complete E-commerce application. Using the MERN stack, the project will cover various essential features, including user authentication, product management, and order handling.

---

## Milestone 1: Project Overview
In the first milestone, we set up the project's foundation:
- Introduced the overall structure of a MERN application.
- Initialized the GitHub repository.
- Provided a brief project overview and objectives for the upcoming milestones.

---

## Milestone 2: Project Setup and Login Page
In the second milestone, we did the following:
- Organized the project structure with separate frontend and backend directories.
- Set up a React app for the frontend.
- Configured a Node.js server for the backend.
- Implemented Tailwind CSS for styling.
- Developed a functional Login Page.

---

## Milestone 3: Project Setup for Backend
In the third milestone, we focused on backend development:
- Created a structured folder hierarchy for the backend code.
- Initialized the Node.js server and configured it to handle API requests.
- Connected the application to MongoDB.
- Implemented basic error handling.

---

## Milestone 4: Creating User Model and Controller
In the fourth milestone, we added more functionality:
- Created a User Model to define the structure of user data.
- Developed a User Controller to manage user-related operations.
- Enabled file uploads using Multer for handling user image uploads.

---

MILESTONE 5 :-
Created a Sign-Up Page in React.

Implemented form validation for: Name (required) Email (valid format required) Password (minimum 2 characters) Password Confirmation (must match password)

Used React Router for navigation.

Milestone 6 :-
Milestone 6: User Registration and Authentication
User Creation Endpoint (/create-user): Implemented an endpoint to create a new user. Validated the email to ensure the user doesn’t already exist. Successfully handled file uploads (e.g., avatar) using multer.

Password Hashing: Used bcryptjs to hash passwords before saving them to the database, ensuring secure password storage.

Error Handling: Incorporated centralized error handling using a custom ErrorHandler class. Applied catchAsyncErrors middleware to manage asynchronous errors in the routes.

User Data Storage: Stored user details (e.g., name, email, password, avatar) in MongoDB with encrypted password.

Email Notification (Optional): Integrated an email notification system to send a welcome email to the user after successful registration (using sendMail).

JWT Token Generation: Added a method to generate JWT tokens upon user login (for future use in authentication routes).


## Technologies Used
- **MongoDB**: NoSQL database for data storage.
- **Express.js**: Web application framework for Node.js.
- **React.js**: Frontend library for building user interfaces.
- **Node.js**: JavaScript runtime for server-side programming.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Multer**: Middleware for handling file uploads. 

---


## Installation
To get started with this project, clone the repository and install the required dependencies:

### Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/Ecommerce-Follow-Along.git
