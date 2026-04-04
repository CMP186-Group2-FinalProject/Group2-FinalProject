🎓 Student & School Management System (Group 2 - Final Project)
📝 Project Description
The Student & School Management System is a comprehensive educational administrative platform designed to digitize academic management processes. It provides a seamless interface for both administrators and students to track academic progress and manage institutional data.

Key Features:

Institutional Management: Manage Departments, Classes, and Courses.

Student Profiles: Comprehensive digital records for every student.

Course Registration: Streamlined credit registration and enrollment management.

Academic Performance: Grade entry system, GPA calculation, and transcript management.

💻 Technologies Used
The project is built on the modern MERN Stack:

Backend: Node.js & Express.js (RESTful API & Server Logic).

Frontend: React.js (Interactive User Interface).

Database: MongoDB (Flexible NoSQL Data Storage).

ODM: Mongoose (Schema modeling and data validation).

Authentication: JSON Web Token (JWT) for secure access control.

🛠 Installation Guide
1. Prerequisites
Node.js (Version 18.x or higher)

MongoDB (Local instance or MongoDB Atlas)

Git

2. Backend Setup
Bash
# Navigate to the backend directory
cd backend

# Install dependencies
npm install

# Create a .env file and configure the following variables:
# PORT=5000
# MONGO_URI=mongodb://localhost:27017/student_db
# JWT_SECRET=your_secret_key

# Initialize Sample Data (Seed Data)
npm run seed

# Run the server in development mode
npm run dev
3. Frontend Setup
Bash
# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Start the React application
npm start
