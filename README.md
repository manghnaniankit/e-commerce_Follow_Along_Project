# E-Commerce Follow-Along Project

This project is a full-stack e-commerce platform developed using the MERN stack: MongoDB, Express.js, React.js, and Node.js. It integrates scalable APIs, secure authentication, and robust product management functionalities to provide a seamless user experience.

## Features

### User Authentication
The platform includes secure login and registration functionalities with JSON Web Tokens (JWT). This ensures that user sessions are properly managed, and sensitive data is accessed only by authorized individuals.
- **Register**: Enables new users to sign up.
- **Login**: Authenticates users and provides a secure session using JWT tokens.

### Product Management
The product management system allows administrators to add, update, retrieve, and delete products efficiently.
- **Add Product**: Allows adding new products with necessary details.
- **Update Product**: Enables updating product details such as price, description, or images.
- **Retrieve Products**: Provides an easy way to fetch product listings.
- **Delete Product**: Removes products from the database when necessary.

### Order Management
The platform offers a comprehensive system to manage customer orders, ensuring a seamless purchasing experience.
- **Create Order**: Allows users to place orders for products.
- **Update Order**: Provides options to update order details (e.g., shipping address, quantity).
- **View Order**: Facilitates viewing order history and status.

### RESTful APIs
The platform uses RESTful API design, which organizes interactions between the client and server into standard HTTP methods (GET, POST, PUT, DELETE). This ensures a clean and scalable communication process with the database.

### Scalable Backend
The backend is developed using Node.js and Express.js, making it highly efficient in handling multiple concurrent requests.

### Responsive Frontend
The frontend is built using React.js, providing a dynamic and responsive user interface.

## Milestones

### Milestone 1: Initialize Project Repository
- Set up the GitHub repository and initialized it with a README file to serve as the central hub for the project.

### Milestone 2: Project Setup and Login Page
- Established the foundational structure and core functionalities, including setting up the React app, configuring Tailwind CSS, and designing the login page.

### Milestone 3: Backend Structure and Server Setup
- Organized backend files, set up the server using Node.js and Express, and integrated MongoDB for data storage.

### Milestone 4: User Management and File Upload
- Implemented user data handling and file upload functionality using Multer.

### Milestone 5: Signup Page and Validation
- Created a user-friendly Sign-Up page with form validation for email and password.

### Milestone 6: User Data Security and Password Encryption
- Enhanced user data security by implementing password encryption using bcrypt.

### Milestone 7: User Authentication and Login
- Implemented a secure login system by verifying user credentials and ensuring proper authentication.

### Milestone 8: Product Card Component and Display
- Designed and implemented a reusable card component to display products effectively.

### Milestone 9: Product Creation Form
- Built a form to collect product details and handle multiple image uploads.

### Milestone 10: Product Schema & API Endpoint
- Defined the product schema and created an API endpoint to validate and store product details in MongoDB.

### Milestone 11: Dynamic Product Display
- Made the home page dynamic by fetching and displaying product data from MongoDB.

### Milestone 12: My Products Page
- Displayed user-specific products by filtering them based on email.

### Milestone 13: Edit Uploaded Products
- Added functionality to edit uploaded products, allowing users to update details in the database.

### Milestone 14: Delete Products in MongoDB
- Implemented functionality to delete products from MongoDB.

### Milestone 15: Navbar Component
- Created a responsive Navbar component and added it to all pages for easy navigation.

### Milestone 16: Product Info Page
- Created a Product Info page to display product details, select quantity, and add items to the cart.

### Milestone 17: Add to Cart Backend
- Created a backend endpoint to add products to the cart and store them in the database.

### Milestone 18: Fetch Cart Items Backend
- Created a backend endpoint to retrieve all products in a user's cart for display on the cart page.

### Milestone 19: Cart Page Functionality
- Displayed products from the `/cart` endpoint and added functionality to adjust product quantities.

### Milestone 20: User Profile Page and Backend Endpoint
- Implemented a profile page to display user data and a backend endpoint to send user data via email.

### Milestone 21: Address Form Implementation
- Implemented an Address Form page to collect and store user address details.

### Milestone 22: Save Address in User Profile
- Created a backend endpoint to save the address inside the user profile in the database.

### Milestone 23: Select Address Page and Order Schema
- Added a "Place Order" button inside the cart page.
- Created a select address page to display all available addresses and allow users to select a delivery address.
- Wrote a Mongoose schema for storing order details.

### Milestone 24: Order Confirmation Page
- Created an order confirmation page to display:
  - Products being ordered.
  - Selected delivery address.
  - Total price of the cart.
- Added a "Place Order" button at the bottom.

### Milestone 25: Backend Endpoint for Placing Orders
- Created an endpoint to receive products, user, and address details and store order details in MongoDB.

### Milestone 26: Fetch User Orders
- Created an endpoint to fetch all orders of a user using their email.

### Milestone 27: My Orders Page
- Developed a frontend page to display all user orders.
- Integrated the My Orders page into the Navbar.

### Milestone 28: Cancel Order Functionality
- Added a "Cancel Order" button in My Orders.
- Created a backend endpoint to mark an order as canceled.

### Milestone 29: PayPal Payment Gateway Integration (Part 1)
- Added PayPal as an online payment option.
- Created sandbox PayPal accounts and retrieved the client ID.

### Milestone 30: PayPal Payment Gateway Integration (Part 2)
- Implemented online payment using PayPal API.
- Installed `react-paypal-js` and integrated PayPal buttons.

### Milestone 31: Global State Management with Redux
- Installed `react-redux`.
- Created a Redux store to store global state variables.
- Implemented state management for user email.

### Milestone 32: Accessing Global State with Redux
- Used Redux dispatch to store user email in the global state.
- Used `useSelector` to access the stored email in all pages.

### Milestone 33: JWT Token and Cookie Storage
- Installed `jsonwebtoken`.
- Created JWT tokens using user email and ID.
- Stored the token inside cookies for secure authentication.

## Technologies Used
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **File Upload**: Multer
- **Password Encryption**: Bcrypt
- **State Management**: Redux
- **Payment Gateway**: PayPal API
